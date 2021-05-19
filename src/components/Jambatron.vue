<template>
<main>
 <div class="jambatron">
  <img src="/img/lupen.jpg" alt="">
  
 </div>
</main>
  
</template>

<script>
export default {
  name: 'main'

}
</script>

<style scoped>
.jambatron{
  width: 80%;
  height: 200px;
  margin: 0 auto;
  
}

.jambatron h1{
  text-align: center;
  line-height: 200px;
  color: rgb(107, 247, 107);
}

img{
  max-width: 100%;
  
}
img:hover{
   transition: all 5s;
    filter: sepia(90%);
    border-radius: 7%;
}






</style>