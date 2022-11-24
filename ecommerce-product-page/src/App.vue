<script setup>
import ProductLightBox from './components/ProductLightBox.vue';

export default {
  data() {
    return {
      viewing: false
    }
  }
}
</script>

<template>
  <body>
    <ProductLightBox v-if="viewing"></ProductLightBox>
    <main>
      Collections
        Men
        Women
        About
        Contact

        Sneaker Company

        Fall Limited Edition Sneakers

        These low-profile sneakers are your perfect casual wear companion. Featuring a 
        durable rubber outer sole, they’ll withstand everything the weather can offer.

        $125.00
        50%
        $250.00

        0
        Add to cart
    </main>
    <footer>
      <div class="attribution">
        <p>Challenge by <a href="https://www.frontendmentor.io?ref=challenge" target="_blank">Frontend Mentor</a>.</p>
        <p>Coded by <a href="#">Your Name Here</a>.</p> 
      </div>
    </footer>
  </body>
</template>
