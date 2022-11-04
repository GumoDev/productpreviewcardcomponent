<script setup>
import { ref } from 'vue';

let message = ref('Happy Coding !!!')
</script>

<template>
  <main class="flex flex-col justify-center items-center bg-[hsl(30,38%,92%)] text-white h-screen">
    
    <section class="transition card-preview bg-white text-black w-11/12 max-w-[375px] md:w-11/12 md:max-w-[768px] md:h-[528px] rounded-xl overflow-hidden md:flex">
      
      <header class="card-img md:w-1/2">

        <div>
          <img class="md:hidden" src="../assets/image-product-mobile.jpg" alt="">
        </div>
        <div>
          <img class="hidden md:flex w-full " src="../assets/image-product-desktop.jpg" alt="">
        </div>  

      </header>

      <section class="card-info p-8 md:w-1/2 md:p-10">
        <span class="text-[hsl(228,12%,48%)] font-[Montserrat] flex my-1 uppercase tracking-[.3rem] text-sm md:text-lg">
          Perfume
        </span>
        <h1 class="text-[hsl(212,21%,14%)] font-[Fraunces] text-3xl my-5 font-bold md:text-4xl">
          Gabrielle <br class="hidden md:flex"> Essence <br class="flex md:hidden">
          Eau <br class="hidden md:flex"> De Parfum
        </h1>
        <p class="text-[hsl(228,12%,48%)] font-[Montserrat] text-sm w-full my-3 md:text-lg">
          A floral, solar and voluptuous <br>
          interpretation composed by <br class="hidden md:flex"> Olivier <br class="md:hidden flex">
          Polge, Perfumer-Creator <br class="hidden md:flex"> for the House of <br class="md:hidden flex">
          CHANEL.
        </p>

        <div class="price flex items-center my-5">
          <span class="font-[Fraunces] text-[hsl(158,36%,37%)] text-3xl md:text-4xl">
            $149.99
          </span>
          <span class="text-[hsl(228,12%,48%)] font-[Montserrat] text-sm ml-5 line-through md:text-lg">
            $169.99
          </span>
        </div>

        <a class="hover:bg-[hsl(157,38%,23%)] bg-[hsl(158,36%,37%)] flex items-center justify-center gap-3 text-white h-12 rounded-lg" href="#">
          <img src="../assets/icon-cart.svg" alt="">
          <span class="md:text-lg font-[Montserrat]">
            Add to  Cart
          </span>
        </a>
      </section>

    </section>

    <footer class="attribution">
      Challenge by <a href="https://www.frontendmentor.io?ref=challenge" target="_blank">Frontend Mentor</a>.
      Coded by <a href="https://github.com/GumoDev/productpreviewcardcomponent">GumoDev</a>.
    </footer>
  </main>
</template>

<style>
/* 
font-family: 'Fraunces', serif;
font-family: 'Montserrat', sans-serif; */
</style>