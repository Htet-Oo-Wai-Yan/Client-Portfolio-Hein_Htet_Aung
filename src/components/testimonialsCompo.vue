<template>
    <div class="main container-fluid p-4">
        <div class="header text-center">
            <p class="fw-bolder d-inline">Feed Back</p>
            <h3 class="fw-bold my-3">Honest Reviews From my clients</h3>
        </div>

        <div class="description  d-flex justiy-content-evenly align-items-center flex-column">
            <reviewcard></reviewcard>
            <reviewcard></reviewcard>
            <reviewcard class="last"></reviewcard>
        </div>
    </div>
</template>

<script>

import reviewcard from '@/subcomponents/reviewcard.vue';

export default {
    name: 'testimonialsCompo',
    components: {
    reviewcard
  }
}
</script>



<style scoped>
    @import url('https://fonts.googleapis.com/css2?family=REM&display=swap');

*{
    box-sizing: border-box;
}

    .main{
        background-color: #000;
        font-family: 'REM', sans-serif;
    }

    .header p{
        color: #7900B2;
        text-transform: lowercase;
        font-size: 20px;

        position: relative;
    }
    .header p::before{
        content: '';
        width: 15px;
        height: 3px;
        background-color: #7900B2;

        position: absolute;
        top: 13px;
        left: -22px;
    }

    .header p::after{
        content: '';
        width: 15px;
        height: 3px;
        background-color: #7900B2;

        position: absolute;
        top: 13px;
        right: -22px;
    }

    .header h3{
        color: #fff;
    }

    .last{
        border-bottom: none;
    }

</style>