<script setup lang="ts">
  import Navbar from './components/navbar.vue';
  import Branding from './components/branding.vue';
  import PopularProduct from './components/popularProduct.vue';
  import Why_choose from './components/why_choose.vue';
  import Offer from './components/offer.vue';
  import About from './components/about.vue';
</script>

<template>
  <div class="font-serif">
    <div class="bg-orange-100">
      <Navbar />
      <Branding />
    </div>
      <section class="mt-40 flex flex-col w-[90%] mx-auto text-white dark:text-black">
        <PopularProduct/>
      </section>
    <section class="mt-20 flex flex-col w-[100%] mx-auto text-white dark:text-black bg-green-500">
      <Why_choose />
    </section>
    <section class="flex flex-col w-[100%] mx-auto text-white dark:text-black">
      <Offer />
    </section>
    <footer class="w-[100%] py-20 bg-orange-400">
      <section class="w-[100%]">
        <About />
        <div class="flex w-[90%] mx-auto items-center justify-end">
          <span>© 2025 Fresh Juice. All rights reserved.</span>
          <ul class="flex items-center justify-center ml-auto gap-10">
            <li><a href="">Privacy policy</a></li>
            <li><a href=""></a>Terms of Service</li>
            <li><a href=""></a>Cookie policy</li>
          </ul>
        </div>
      </section>
    </footer>
  </div>
</template>

<style scoped></style>
