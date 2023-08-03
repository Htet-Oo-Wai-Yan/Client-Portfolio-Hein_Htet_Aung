<template>

    <div class="testimonial-main container row-0 d-flex align-items-center m-4 py-4">
        
        <div class="client col-4 d-flex justify-content-evenly align-items-center">
            <img src="../assets//profile_images/client.jpg" alt="client">
            
            <div class="client-info fw-bold lh-sm">
                <p class="name">John Doe</p>
                <p>Marketing Manager</p>
            </div>
        </div>

        <div class="testi-text col-8 lh-lg">
            <p>
                Lorem ipsum dolor sit amet consectetur, adipisicing elit. Voluptas repellendus consectetur perferendis! Obcaecati blanditiis sapiente est harum nisi? Quis dolores exercitationem quod sequi? Saepe, odio. Quibusdam dicta asperiores nesciunt neque.
                Lorem ipsum, dolor sit amet consectetur adipisicing elit. Explicabo, dignissimos, adipisci ex earum vero odio, excepturi error ducimus incidunt expedita possimus rem! Rerum dolor modi voluptatem facilis quidem dolorum quo.
            </p>
        </div>

    </div>
    
</template>

<script>
export default {
    name : 'reviewcard'
}
</script>

<style scoped>

.testimonial-main{
    border-bottom: 1px solid #fff;
}

.client-info{
    color: #7900b2;
    font-size: 20px;
}

img{
        width: 80px;
        height: 80px;
        border-radius: 9999px;
}

.testi-text {
    color: #fff;
}
</style>