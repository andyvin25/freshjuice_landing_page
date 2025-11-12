<template>
    <div class="pt-40 pb-30 mx-auto w-[90%]">
        <div class="grid md:grid-cols-2 place-items-center" style="gap: clamp(16px, calc(10.182px + 1.818vw), 32px);">
            <div class="mb-5" style="gap: clamp(16px, calc(10.182px + 1.818vw), 32px);">
                    <button type="button" class="text-orange-400 focus:outline-none focus:ring-4 focus:ring-orange-300 font-medium rounded-full text-s px-5 py-2 text-center mb-12 border-1 border-orange-400 rounded-full dark:focus:ring-orange-800">100% fresh & natural</button>
                    <h1 class="text-5xl font-bold mb-15">
                        Refresh Your Day with
                    </h1>
                    <p class="text-2xl mb-10">Discover our handcrafted selection of fresh juices, smoothies, and beverages made from the finest natural ingredients.</p>
                    <div class="block md:flex mb-10" style="gap: clamp(5px, calc(10.182px + 1.818vw), 32px);">
                        <button type="button" class="w-full md:w-full text-2xl text-white bg-gray-800 hover:bg-gray-900 focus:outline-none focus:ring-4 focus:ring-gray-300 font-medium rounded-lg text-md px-5 py-2.5 me-2 mb-2 dark:bg-gray-800 dark:hover:bg-gray-700 dark:focus:ring-gray-700 dark:border-gray-700">Shop now</button>
                        <button type="button" class="w-full md:w-full text-2xl text-gray-900 hover:text-white border border-gray-800 hover:bg-gray-900 focus:ring-4 focus:outline-none focus:ring-gray-300 font-medium rounded-lg text-md px-5 py-2.5 text-center me-2 mb-2 dark:border-gray-600 dark:text-gray-400 dark:hover:text-white dark:hover:bg-gray-600 dark:focus:ring-gray-800">View Menu</button>
                    </div>
                    <div class="border border-gray-400 mb-15"></div>
                    <div class="grid grid-cols-3 " style="gap: clamp(16px, calc(10.182px + 1.818vw), 32px);">
                        <div class="flex flex-col ">
                            <span class="text-xl">500+</span>
                            <span class="text-gray-500">happy customers</span>
                        </div>
                        <div class="flex flex-col">
                            <span class="text-xl">50+</span>
                            <span class="text-gray-500">Drink Varieties</span>
                        </div>
                        <div class="flex flex-col">
                            <span class="text-xl">100%</span>
                            <span class="text-gray-500">natural</span>
                        </div>
                        <!-- <span class="text-xl"><b>500+</b> <br><span class="text-gray-500">happy customers</span> </span>
                        <span class="text-xl"><b>50+</b> <span><span class="text-gray-500">Drink Varieties</span></span> </span>
                        <span class="text-xl"><b>100%</b><br><span class="text-gray-500">Natural</span></span> -->
                    </div>
            </div>
            <picture class="mx-auto flex items-center justify-center">
                
                <img
                    fetchpriority="high"
                    decoding="async" 
                    loading="lazy" 
                    role="presentation" 
                    class="rounded-4xl block object-center shadow-xl/30" src="../assets/drink.jpg" style="max-inline-size: 100%; width: min(1000px, 80%);" alt="drink">
            </picture>
                <!-- <div class="bg-[url('./assets/drink.jpg/')] bg-cover bg-center rounded-4xl block w-[100%]" style=""></div> -->
                
        </div>
    </div>

</template>