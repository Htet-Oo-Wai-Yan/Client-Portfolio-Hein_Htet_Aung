<template>
    <div class="main container-fluid p-4 description d-flex justiy-content-evenly align-items-center text-center flex-column">
        <div class="header text-center">
            <p class="fw-bolder d-inline">contact me</p>
            <h3 class="fw-bold my-3">Contact Me If You wanna solve your Problems</h3>
        </div>

    <div class="description d-flex justify-content-between align-items-center">
        
        <div class="form">
            <form action="#" class="">

                <label class="d-flex flex-column p-2">
                    <input type="text" required/>
                    <span>Your Name</span>
                </label>

                <label class="d-flex flex-column p-2">
                    <input type="number" required/>
                    <span>Your Phone Number</span>
                </label>
                
                <label class="d-flex flex-column p-2">
                    <input type="email" required/>
                    <span>Your Email</span>
                </label>

                <label class="my-4 d-flex flex-column p-2">
                    <textarea class="rounded" cols="80" rows="0" aria-required="true" aria-invalid="false" placeholder="Add up any informations as you want.." required></textarea>
                </label>

            </form>

            <button>
                <input type="submit" value="Send" />
            </button>
        </div>

    </div>

    </div>
</template>

<script>
export default {
    name: 'contactCompo'
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

    label{
        margin: 2rem;
        color: #7900b2;
        
        position: relative;
    }

    input{
        border: none;
        background-color: #000;
        border-bottom: 2px solid #fff;
        color: #fff;
        
        padding: 10px 3rem;
        
        outline: 0;

        transition: border-bottom ease-in .3s;

    }

    input:focus{
        border-bottom: 2px solid #7900B2;
        outline: 0;
    }

    input[type=number]::-webkit-inner-spin-button, 
    input[type=number]::-webkit-outer-spin-button { 
        -webkit-appearance: none; 
        margin: 0; 
    }

    label input + span{
        font-size: 0.9em;
        color: gray;

        cursor: text;

        position: absolute;
        top: 20px;
        left: 10px;

        transition: .3s ease-in;
    }

    label input:focus + span,
    label input:valid + span{
        top: 60px;
        font-size: 0.7em;
        font-weight: 600;
    }

    label input:valid + span{
        color: green;
    }

    label input:valid{
        border-bottom-color: green;
    }

    label textarea{
        height: 150px;
        background-color: transparent;
        border: 2px solid #fff;
        color: #fff;

        outline: 0;

        padding: 30px;

        transition: border .3s ease-in;
    }

    label textarea:focus{
        border: 2px solid #7900B2;
        outline: 0;
    }

    label textarea:valid{
        border-color: green;
    }

    button {
        background: #7900B2;
        font-family: inherit;
        padding: 0.3em 1.3em;
        font-weight: 900;
        font-size: 18px;
        border: 3px solid white;
        border-radius: 0.4em;
        box-shadow: 0.1em 0.1em white;
    }

    button:hover {
        transform: translate(-0.05em, -0.05em);
        box-shadow: 0.15em 0.15em white;
    }

    button:active {
        transform: translate(0.05em, 0.05em);
        box-shadow: 0.05em 0.05em white;
    }
    
    input[type="submit"]{
        background-color: #7900B2;
        color: #fff;
        border: none;
    }
</style>