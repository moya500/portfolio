<script setup>
import image from "../assets/images/complexityposter.png"
import image1 from "../assets/images/kokenzonderwoorden.png"
</script>


<template>
  <div class="Works">
    <h1>Works</h1>
  
    <div>
      <h3> 
      Illustrations 
      </h3>
    </div>

    <div>
    <img :src="image">
    </div>

    <div>
    <img :src="image1">
    </div>

  </div>
    
</template>

<style>
/* @media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
} */

img{
  width: 600px;
}
</style>

