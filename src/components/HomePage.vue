<template>
    <div class="home p-4 d-flex justify-content-center align-items-center">
        <div class="about-me container-fluid d-flex justify-content-space-between align-items-center flex-row" >
            <div class="about-me-info">
                <p class="display-2 fw-bold header">Who am I?</p>
                <p class="text-light fs-sm-6">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aut error quam doloremque veritatis laudantium modi commodi deleniti beatae fuga! Deleniti beatae nisi consequuntur eos aspernatur ea hic expedita odio atque.</p>
                <button type="button" class="btn btn-primary p-2">View More</button>
            </div>

            <div class="profile">
                <img class="rounded img-thumbnail" src="../assets//profile_images/tempo_profile.jpg" alt="profile-image" />
            </div>            

        </div>
    </div>
</template>

<script>
export default {
    name: 'HomePage'
}
</script>

<style scoped>
.home{
    width: 100%;
    height: 100vh;

    background: #3a7bd5;  
    background: -webkit-linear-gradient(to right, #3a6073, #3a7bd5);  
    background: linear-gradient(to right, #3a6073, #3a7bd5); 
}

.header{
    color: #000;
}



.more-btn{
    color: #fff;
    background-color: #7900B2;
    border-bottom: 3px solid #7900B2;

    transform: translateY(0);
}

.more-btn:hover{
    background-color: #fff;
    color: #7900B2;
    border-bottom: 3px solid #000;

    transition: all .4s;
}

.more-btn:active{
    transform: translateY(3px);

    transition: transform .3s;
}

</style>