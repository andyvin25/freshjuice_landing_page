<template>
  <nav :class="{ 'inset-0': isOpened }" class="bg-white dark:bg-gray-900 fixed w-full z-50 top-0">
    <div class="w-[92%] flex flex-wrap items-center justify-end mx-auto p-4">
      <a href="https://flowbite.com/" class="flex items-center flex-end mr-auto">
          <h1 class="self-center text-5xl font-bold whitespace-nowrap dark:text-white">Fresh Juice</h1>
      </a>
      <div class="flex md:order-2 space-x-3 md:space-x-0">
          
          <button @click="toggle" data-collapse-toggle="navbar-default" type="button" class="inline-flex items-center p-2 w-10 h-10 justify-center text-sm text-gray-500 rounded-lg md:hidden hover:bg-gray-100 focus:outline-none focus:ring-gray-200 dark:text-gray-400 dark:hover:bg-gray-700 dark:focus:ring-gray-600" aria-controls="navbar-default" aria-expanded="false">
          <span  class="sr-only">Open main menu</span>
          <svg class="w-5 h-5" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 17 14">
              <path stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M1 1h15M1 7h15M1 13h15"/>
          </svg>
      </button>
      </div>
      <div :class="{ 
            'hidden': !isOpened
          }" class="w-full md:flex items-center justify-center md:w-auto" id="navbar-default">
        <ul class="font-medium flex flex-col w-full items-center justify-center content-center p-4 md:p-0 mt-4 rounded-lg md:flex-row md:mt-0 md:border-0 md:bg-white md:dark:bg-gray-900 dark:border-gray-700" style="gap: clamp(16px, calc(10.182px + 1.818vw), 32px);">
          <li class="w-full text-center">
            <a href="#" class="text-base block text-gray-900 rounded-sm hover:bg-gray-100 md:hover:bg-transparent md:border-0 md:hover:text-blue-700 p-2 md:p-0 dark:text-white md:dark:hover:text-blue-500 dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent" aria-current="page">Home</a>
          </li>
          <li class="w-full text-center">
            <a href="#" class="text-base block text-gray-900 rounded-sm hover:bg-gray-100 md:hover:bg-transparent md:border-0 md:hover:text-blue-700 p-2 md:p-0 dark:text-white md:dark:hover:text-blue-500 dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent">About</a>
          </li>
          <li class="w-full text-center">
            <a href="#" class="text-base block text-gray-900 rounded-sm hover:bg-gray-100 md:hover:bg-transparent md:border-0 md:hover:text-blue-700 p-2 md:p-0 dark:text-white md:dark:hover:text-blue-500 dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent">Services</a>
          </li>
          <li class="w-full text-center">
            <a href="#" class="text-base block text-gray-900 rounded-sm hover:bg-gray-100 md:hover:bg-transparent md:border-0 md:hover:text-blue-700 p-2 md:p-0 dark:text-white md:dark:hover:text-blue-500 dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent">Pricing</a>
          </li>
          <li class="w-full text-center">
            <a href="#" class="text-base block text-gray-900 rounded-sm hover:bg-gray-100 md:hover:bg-transparent md:border-0 md:hover:text-blue-700 p-2 md:p-0 dark:text-white md:dark:hover:text-blue-500 dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent">Contact</a>
          </li>
          <li class="w-full flex items-center justify-center md:hidden ml-auto">
            <button type="button" class="p-2 w-full text-white bg-violet-400 hover:bg-blue-800 focus:ring-4 focus:outline-none focus:ring-blue-300 font-medium rounded-md text-sm dark:hover:bg-blue-700">Order now</button>
          </li>
        </ul>
      </div>
      <div class="hidden md:block md:ml-auto">
          <a class="text-4xl text-white bg-black hover:bg-blue-800 focus:outline-none font-medium rounded-lg px-4 py-2 text-center dark:hover:bg-blue-700">Order now</a>
      </div>
    </div>
  </nav>

</template>

<script lang="ts" setup>
import { ref } from 'vue';

  const isOpened = ref(false)

  function toggle() {
    isOpened.value = !isOpened.value
    console.log(isOpened.value)
  }
</script>