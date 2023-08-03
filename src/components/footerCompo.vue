<template>
    <div class="main container-fluid  d-flex justify-content-center align-items-center flex-column">
        <div>
            <h3>A collection of branding 
                and problem solving, 
                partnering with companies
                doing great things to help 
                and grow your online
                bussiness.....
            </h3>
        </div>

        <div class="header  m-4 text-center">
            <p class="fw-bolder d-inline">Socail Contacts</p>

            <ul class="d-flex mx-auto">
                <li>
                    <a href="#">facebook</a>
                </li>
                
                <li>
                    <a href="#">viber</a>
                </li>
                
                <li>
                    <a href="#">linkedin</a>
                </li>
            </ul>
        </div>

        <!-- <img src="../assets/profile_images/tempo_profile.jpg" alt="image"> -->
    </div>
</template>

<script>
export default {
    name: 'footerCompo'
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

        padding-top: 3rem;
    }

    h3{
        width: 500px;
        color: #fff;
        line-height: 35px;

        margin: 60px 0 0 0;
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

    .header ul{
        padding: 0;

    }

    .header ul li{
        font-size: 18px;
        list-style: none;
        
        margin: 20px;
        padding: 5px 10px; 

    }
    .header ul li a{
        text-decoration: none;
        color: #7900B2;
        font-weight: bold;
        text-transform: uppercase;
        letter-spacing: 2px;
        font-size: 16px;

        transition: color .3s ease-in-out;
    }

    .header ul li a:hover{
        color: #fff;
    }
    
    img{
        width: 100px;
        height: 100px;
        border-radius: 50%;
    }
</style>