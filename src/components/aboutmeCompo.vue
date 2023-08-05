<template>
    <div class="main container-fluid p-4 description d-lg-flex justiy-content-lg-evenly align-items-lg-center flex-column ">
        <div class="header text-center">
            <p class="fw-bolder d-inline">About Me</p>
            <h3 class="fw-bold my-3">A little bit about my goal & vision</h3>
        </div>
        <div class="description d-flex justiy-content-center align-items-center p-3 m-2 row">
            <div class="col-lg-5 col-md-12 my-4">
                <img class="img-fluid rounded d-block mx-auto" src="../assets/profile_images/tempo_profile2.jpg" alt="profile2">
            </div>
           
            <div class="container-fluid col-lg-5 col-md-12 about-me-desc mx-auto lh-lg">
                <p>
                    Lorem ipsum dolor sit amet consectetur, adipisicing elit. Voluptates, debitis nihil! Qui provident, deleniti consequuntur iste quisquam aut facere eaque assumenda excepturi, dolor odio, quasi aliquid rerum eum dolore repellendus?
                </p>

                <p>
                    Lorem ipsum, dolor sit amet consectetur adipisicing elit. Maiores odio aliquam voluptas ex officiis quidem sed sint inventore magni? Explicabo iure nemo expedita accusamus facere quaerat nam impedit sed illum!
                    Lorem ipsum dolor sit amet consectetur adipisicing elit. Assumenda, magni. Blanditiis explicabo repudiandae doloribus eius assumenda alias vitae consequuntur. A, quaerat sed consequatur explicabo vitae sit at adipisci? Commodi, similique?
                </p>
           </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'aboutmeCompo'
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
        width: 350px;
    }

    .about-me-desc{
        width: 450px;
        color: #fff;
    }


</style>