<template>
    <div class="projects-main  p-4 d-flex justify-content-center align-items-center flex-column">
        
        <div class="header text-light text-center">
                <p class="fw-bolder main-header">service</p>
                <p class="fs-4 fw-semibold sub-header">We can fix your digital problems via online.</p>
        </div>


        <div class="detail-card card container-fluid m-4">
            
            <h5 class="card-header fw-bolder card-name">Coffee Fusion</h5>
            
            <div class="card-body">
                <img class="img-fluid" src="../assets/profile_images/sample-project-image.png" alt="">
                <h5 class="card-title">About Us</h5>
                <p class="card-text">"Copy Fusion: Where Words Ignite. Join us to unleash your brand's impact. As a copywriter, I craft captivating narratives and compelling messaging. Let's embark on a journey of linguistic innovation together. Join the Copy Fusion community and spark connections through creative copywriting."</p>
                <a href="#" class="btn btn-primary">View The Site</a>
            </div>

        </div>

        <div class="detail-card card container-fluid m-4">
            
            <h5 class="card-header fw-bolder card-name">Coffee Fusion</h5>
            
            <div class="card-body">
                <img class="img-fluid" src="../assets/profile_images/sample-project-image.png" alt="">
                <h5 class="card-title">About Us</h5>
                <p class="card-text">"Copy Fusion: Where Words Ignite. Join us to unleash your brand's impact. As a copywriter, I craft captivating narratives and compelling messaging. Let's embark on a journey of linguistic innovation together. Join the Copy Fusion community and spark connections through creative copywriting."</p>
                <a href="#" class="btn btn-primary">View The Site</a>
            </div>

        </div>

        <div class="detail-card card container-fluid m-4">
            
            <h5 class="card-header fw-bolder card-name">Coffee Fusion</h5>
            
            <div class="card-body">
                <img class="img-fluid" src="../assets/profile_images/sample-project-image.png" alt="">
                <h5 class="card-title">About Us</h5>
                <p class="card-text">"Copy Fusion: Where Words Ignite. Join us to unleash your brand's impact. As a copywriter, I craft captivating narratives and compelling messaging. Let's embark on a journey of linguistic innovation together. Join the Copy Fusion community and spark connections through creative copywriting."</p>
                <a href="#" class="btn btn-primary">View The Site</a>
            </div>

        </div>

    
    </div>
</template>

<script>
export default {
    name : 'ProjectCard'
}
</script>

<style scoped>

.projects-main{
    widows: 100%;
    background: #000;
}
    .detail-card{
        /* width: 100%; */
        color: #fff;
        background: rgba(255, 255, 255, 0.2);
        border-radius: 16px;
        box-shadow: 0 4px 30px rgba(0, 0, 0, 0.1);
        backdrop-filter: blur(5px);
        -webkit-backdrop-filter: blur(5px);
        border: 1px solid rgba(255, 255, 255, 0.3);
        border-radius: 10px;

        margin: 20px 10px;
    }

    .main-header{
        color: #7900B2;
        
        position: relative;
    }

    .main-header::before,.main-header::after{
        content: '';
        width: 10px;
        height: 3px;
        border-radius: 5px;
        background-color: #7900B2;

        position: absolute;
        top: 10px;
    }

    .main-header::before{
        left: 40%;
    }

    .main-header::after{
        right: 40%;
    }
    
    .card-name{
        color: #fff;
        font-weight: bold;
        text-transform: uppercase;
    }

    img{
        width: 100%;
    }
</style>