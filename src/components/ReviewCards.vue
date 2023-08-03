<template>
    <div class="main p-4 d-flex justify-content-center align-items-center">
        <div class="review-cards container-fluid p-4 m-2 d-flex justify-content-center align-items-center flex-column text-center">

            <div class="header">
                <p class="fw-bolder main-header">Feed Back</p>
                <p class="fs-4 fw-semibold sub-header text-light">Honest Reviews From My Clients</p>
            </div>

            <div class="review p-3 rounded text-dark">
                <p class="text-start fw-medium">
                    Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ullam consequatur, recusandae, ducimus voluptatibus, quia aliquam sed ipsam impedit modi minus asperiores? Aut pariatur officiis dignissimos? Deserunt maiores officia recusandae? Commodi?
                    Lorem ipsum dolor sit amet consectetur, adipisicing elit. Ducimus, non voluptatibus. Voluptatum praesentium earum, dignissimos corrupti saepe incidunt, unde obcaecati quos iure eveniet dicta cum quod perspiciatis odio ad minima?
                </p>

                <div class="d-flex clients align-items-center">
                    <img class="client-image" src="../assets/profile_images/client.jpg" alt="client image" />
                    <div class="clients-details text-start p-3 my-auto fw-bold">
                        <p>John Doe</p>
                        <p>Marketing Manager</p>
                    </div>
                </div>
                
            </div>

        </div>
    </div>
</template>

<script>
export default {
    name: 'ReviewCards'
}
</script>

<style scoped>

.main{
    width: 100%;
    /* height: 100vh; */
    background-color: #000;

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
        left: 35%;
    }

    .main-header::after{
        right: 35%;
    }

    .review{
        background-color: #fff;
    }

    img{
        width: 100px;
        height: 100px;
        border: 3px solid #000;
        border-radius: 50%;
    }
</style>