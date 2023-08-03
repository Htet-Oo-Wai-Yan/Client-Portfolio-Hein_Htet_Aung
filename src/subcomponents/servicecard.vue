<template>
    
    <div class="service-main container rounded">
        <h4 class="fs-3">Copy Fusion</h4>
        <img src="https://www.searchenginejournal.com/wp-content/uploads/2021/12/seo-copywriting-61ded65aa6f8e-sej.png" alt="copy fusion image">

        <div class="project-desc m-4 text-left lh-lg">
            <p>
                Lorem ipsum dolor sit amet consectetur, adipisicing elit. Autem itaque alias, aliquam aperiam iusto, provident ad iste non rerum labore tempora, consequatur optio aliquid. Vitae corrupti commodi delectus incidunt ab?
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Maiores, eum! Amet ea possimus reprehenderit sunt mollitia, sequi perferendis cumque. Hic laudantium aliquid ex non? Maxime officiis suscipit reiciendis placeat voluptatum?
            </p>
        </div>

        <button class=" button mx-auto p-2">
            <a href="#" class="text fw-bold">View Website</a>
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><g data-name="Double Arrow"><path d="M12 17a1 1 0 0 1-.707-1.707L14.586 12l-3.293-3.293a1 1 0 1 1 1.414-1.414l4 4a1 1 0 0 1 0 1.414l-4 4A1 1 0 0 1 12 17z"/><path d="M8 17a1 1 0 0 1-.707-1.707L10.586 12 7.293 8.707a1 1 0 1 1 1.414-1.414l4 4a1 1 0 0 1 0 1.414l-4 4A1 1 0 0 1 8 17z"/></g></svg>
        </button>
    </div>

</template>

<script>
export default {
    name: 'servicecard'
}
</script>

<style scoped>

.service-main{
    color: #fff;
}

h4{
    color: #fff;
}
    
img{
    width: 300px;
}

.text{
    text-decoration: none;
    color: #000;
    font-size: 16px;
}

.button svg{
    width: 30px;
    height: 30px;
    fill: #7900B2;
}

.button {
    gap: 15px;
    background-color: #000;
    outline: 3px #7900B2 solid;
    outline-offset: -3px;
    border-radius: 5px;
    border: none;
    
    display: flex;
    justify-content: space-between;
    align-items: center;
  
    cursor: pointer;
  
    transition: 400ms;
}

.button .text {
  color: #7900B2;
  font-weight: 700;
  transition: 400ms;

  padding-left: 10px;
}

.button svg path {
  transition: 400ms;
}

.button:hover {
  background-color: #7900B2;
}

.button:hover .text {
  color: #fff;
}

.button:hover svg path {
  fill: #fff;
}

.button:active {
  transform: translate(0.05em, 0.05em);
  box-shadow: 0.05em 0.05em white;
}
</style>