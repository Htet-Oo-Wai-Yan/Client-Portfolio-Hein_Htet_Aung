<template>
    <div class="main container-fluid  p-4 d-flex align-items-center justify-content-evenly">
        
        <div class="description lh-lg" >
            <h1 class="fw-bolder fs-1">Lorem ipsum dolor sit amet</h1>
            <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Excepturi voluptates nulla enim optio a debitis quasi quam odio quod magni quos maxime, harum veritatis provident repudiandae commodi alias? Alias, delectus.</p>
            <button><a href="#" class="fw-bold">Contact Me</a></button>
        </div>

        <img class="profile-image" src="../assets/profile_images/profile.png" alt="profile image">
    </div>
</template>

<script>
export default {
    name: 'heroCompo'
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
.description{
    min-width: 250px;
    max-width: 450px;
    height: auto;
    color: #fff;

}

img{
    border-bottom: 0.2px solid #fff;

}
.description h1{
    color: #7900B2;
}

.description button {
  background: #7900B2;
  font-family: inherit;
  padding: 0.6em 1.3em;
  font-weight: 900;
  font-size: 18px;
  border: 3px solid white;
  border-radius: 0.4em;
  box-shadow: 0.1em 0.1em white;
}

.description button:hover {
  transform: translate(-0.05em, -0.05em);
  box-shadow: 0.15em 0.15em white;
}

.description button:active {
  transform: translate(0.05em, 0.05em);
  box-shadow: 0.05em 0.05em white;
}

.description button a{
    text-decoration: none;
    color: #fff;
    text-transform: uppercase;
    font-size: 16px;
}

</style>