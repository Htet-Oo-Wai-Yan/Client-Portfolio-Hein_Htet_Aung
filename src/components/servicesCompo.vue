<template>
    <div class="main container-fluid p-4 description d-flex justiy-content-evenly align-items-center flex-column">
        <div class="header text-center">
            <p class="fw-bolder d-inline">services</p>
            <h3 class="fw-bold my-3">We Can Fix your digital problems online..</h3>
        </div>

        <div class="description-con mx-auto grid row p-4">
            <servicecard class="col-lg-3 col-md-6 col-sm-12"></servicecard>
            <servicecard class="col-lg-3 col-md-6 col-sm-12"></servicecard>
            <servicecard class="col-lg-3 col-md-6 col-sm-12"></servicecard>
            <servicecard class="col-lg-3 col-md-6 col-sm-12 last"></servicecard>
        </div>
    </div>
</template>

<script>
// @ is an alias to /src
import servicecard from '@/subcomponents/servicecard.vue';


export default {
  name: 'serviceCompo',
  components: {
    servicecard
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

    .description-con{
        margin-top: 2em;
    }
</style>