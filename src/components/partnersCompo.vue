<template>
    <div class="main container-fluid p-4 description d-flex justiy-content-evenly align-items-center flex-column">
        <div class="header text-center">
            <p class="fw-bolder d-inline">Our Partners</p>
            <h3 class="fw-bold my-3">Our trustworthy Partners</h3>
        </div>

        <div class="partners-logo d-flex justify-content-center align-items-center my-4 mx-auto row">
            <img class="logo col-sm-12 col-lg-4 my-4" src="../assets/project_imges/amazing.png" alt="partner-logo"/>
            <img class="logo col-sm-12 col-lg-4 my-4" src="../assets/project_imges/Dope.png" alt="partner-logo"/>
            <img class="logo col-sm-12 col-lg-4 my-4" src="../assets/project_imges/FIggy.png" alt="partner-logo"/>
            <img class="logo col-sm-12 col-lg-4 my-4" src="../assets/project_imges/wow.png" alt="partner-logo"/>
            <img class="logo col-sm-12 col-lg-4 my-4" src="../assets/project_imges/grim-reaper.png" alt="partner-logo"/>
            <img class="logo col-sm-12 col-lg-4 my-4" src="../assets/project_imges/toonnet.png" alt="partner-logo"/>
            <img class="logo col-sm-12 col-lg-4 my-4" src="../assets/project_imges/Chill.png" alt="partner-logo"/>
            <img class="logo col-sm-12 col-lg-4 my-4" src="../assets/project_imges/copy-fusion.jpg" alt="partner-logo"/>
        </div>
    </div>
</template>

<script>
export default {
    name: 'partnersCompo'
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

    img{
        width: 120px;

        margin: 0 3rem;
    }
</style>