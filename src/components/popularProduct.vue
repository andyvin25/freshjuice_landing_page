<template>
    <div class="flex flex-col items-center justify center">
        <h1 class="text-5xl font-bold mb-10">Our Popular Drinks</h1>
        <p class="text-xl">Handcrafted with love and the freshest ingredients. Every sip is a journey to flavor paradise.</p>
    </div>
    <div class="mt-20 mb-30 grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 place-items-center gap-20">
    <!-- Card 1: Berry Smoothie Bowl -->
        <div class="w-full transition-shadow duration-300 ease-in-out 
             hover:shadow-xl/30 hover:shadow-xl/30 bg-white rounded-2xl shadow-sm dark:bg-gray-800">
            <div class="relative overflow-hidden rounded-t-2xl h-120">
                <div class="absolute left-5 top-5 z-20 px-5 rounded-4xl bg-orange-300 text-sm font-medium">Best Seller</div>
                <img
                class="w-full h-full object-cover hover:scale-110 transition-transform duration-300"
                src="../assets/berry.jpg"
                alt="Berry Smoothie Bowl"
                />
            </div>
            <div class="p-5">
                <div class="flex items-center justify-between">
                <h5 class="mb-2 text-lg font-bold tracking-tight text-gray-900 dark:text-white">Berry Smoothie Bowl</h5>
                <h5 class="text-gray-900 dark:text-white">4.8</h5>
                </div>
                <p class="mb-3 font-normal text-gray-700 dark:text-gray-400">Mixed berries blended with yogurt and topped with granola</p>
                <div class="flex items-center justify-between">
                <span class="text-gray-900 dark:text-white">$7.99</span>
                <button class="inline-flex items-center gap-2 px-3 py-2 text-sm font-medium text-center text-white bg-blue-700 rounded-lg hover:bg-blue-800 focus:ring-4 focus:outline-none focus:ring-blue-300 dark:bg-slate-950 dark:hover:bg-blue-700 dark:focus:ring-blue-800">
                    <img width="25" height="25" src="https://img.icons8.com/sf-ultralight-filled/25/FFFFFF/shopping-cart.png" alt="shopping-cart" />
                    Add
                </button>
                </div>
            </div>
        </div>

        <!-- Card 2: Green Juice -->
        <div class="w-full transition-shadow duration-300 ease-in-out 
             hover:shadow-xl/30 hover:shadow-xl/30 bg-white rounded-2xl shadow-sm dark:bg-gray-800">
            <div class="relative overflow-hidden rounded-t-2xl h-120">
                <div class="absolute left-5 top-5 z-20 px-5 rounded-4xl bg-orange-300 text-sm font-medium">New</div>
                <img
                class="w-full h-full object-cover hover:scale-110 transition-transform duration-300"
                src="../assets/green_juice.jpg"
                alt="Green Juice"
                />
            </div>
            <div class="p-5">
                <div class="flex items-center justify-between">
                <h5 class="mb-2 text-lg font-bold tracking-tight text-gray-900 dark:text-white">Green Juice</h5>
                <h5 class="text-gray-900 dark:text-white">4.8</h5>
                </div>
                <p class="mb-3 font-normal text-gray-700 dark:text-gray-400">Spinach, kale, cucumber, and apple for ultimate refreshment</p>
                <div class="flex items-center justify-between">
                <span class="text-gray-900 dark:text-white">$6.49</span>
                <button class="inline-flex items-center gap-2 px-3 py-2 text-sm font-medium text-center text-white bg-blue-700 rounded-lg hover:bg-blue-800 focus:ring-4 focus:outline-none focus:ring-blue-300 dark:bg-slate-950 dark:hover:bg-blue-700 dark:focus:ring-blue-800">
                    <img width="25" height="25" src="https://img.icons8.com/sf-ultralight-filled/25/FFFFFF/shopping-cart.png" alt="shopping-cart" />
                    Add
                </button>
                </div>
            </div>
        </div>

        <!-- Card 3: Citrus Juice -->
        <div class="w-full transition-shadow duration-300 ease-in-out 
             hover:shadow-xl/30 hover:shadow-xl/30 bg-white rounded-2xl shadow-sm dark:bg-gray-800">
            <div class="relative overflow-hidden rounded-t-2xl h-120">
                <img
                class="w-full h-full object-cover hover:scale-110 transition-transform duration-300"
                src="../assets/pexels-berkncn-31546996.jpg"
                alt="Citrus Juice"
                />
            </div>
            <div class="p-5">
                <div class="flex items-center justify-between">
                <h5 class="mb-2 text-lg font-bold tracking-tight text-gray-900 dark:text-white">Citrus Juice</h5>
                <h5 class="text-gray-900 dark:text-white">4.8</h5>
                </div>
                <p class="mb-3 font-normal text-gray-700 dark:text-gray-400">Orange, grapefruit, and lemon for a zesty morning boost</p>
                <div class="flex items-center justify-between">
                <span class="text-gray-900 dark:text-white">$5.99</span>
                <button class="inline-flex items-center gap-2 px-3 py-2 text-sm font-medium text-center text-white bg-blue-700 rounded-lg hover:bg-blue-800 focus:ring-4 focus:outline-none focus:ring-blue-300 dark:bg-slate-950 dark:hover:bg-blue-700 dark:focus:ring-blue-800">
                    <img width="25" height="25" src="https://img.icons8.com/sf-ultralight-filled/25/FFFFFF/shopping-cart.png" alt="shopping-cart" />
                    Add
                </button>
                </div>
            </div>
        </div>

        <!-- Card 4: Watermelon Drink -->
        <div class="w-full transition-shadow duration-300 ease-in-out 
             hover:shadow-xl/30 hover:shadow-xl/30 bg-white rounded-2xl shadow-sm dark:bg-gray-800">
            <div class="relative overflow-hidden rounded-t-2xl h-120">
                <img
                class="w-full h-full object-cover hover:scale-110 transition-transform duration-300"
                src="../assets/watermelon.jpg"
                alt="Watermelon Drink"
                />
            </div>
            <div class="p-5">
                <div class="flex items-center justify-between">
                <h5 class="mb-2 text-lg font-bold tracking-tight text-gray-900 dark:text-white">Watermelon Refresher</h5>
                <h5 class="text-gray-900 dark:text-white">4.7</h5>
                </div>
                <p class="mb-3 font-normal text-gray-700 dark:text-gray-400">Fresh watermelon juice with a hint of mint and lime</p>
                <div class="flex items-center justify-between">
                <span class="text-gray-900 dark:text-white">$5.49</span>
                <button class="inline-flex items-center gap-2 px-3 py-2 text-sm font-medium text-center text-white bg-blue-700 rounded-lg hover:bg-blue-800 focus:ring-4 focus:outline-none focus:ring-blue-300 dark:bg-slate-950 dark:hover:bg-blue-700 dark:focus:ring-blue-800">
                    <img width="25" height="25" src="https://img.icons8.com/sf-ultralight-filled/25/FFFFFF/shopping-cart.png" alt="shopping-cart" />
                    Add
                </button>
                </div>
            </div>
        </div>

        <!-- Card 5: Tropical Blend -->
        <div class="w-full transition-shadow duration-300 ease-in-out 
             hover:shadow-xl/30 hover:shadow-xl/30 bg-white rounded-2xl shadow-sm dark:bg-gray-800">
            <div class="relative overflow-hidden rounded-t-2xl h-120">
                <img
                class="w-full h-full object-cover hover:scale-110 transition-transform duration-300"
                src="../assets/drink2.jpg"
                alt="Tropical Blend"
                />
            </div>
            <div class="p-5">
                <div class="flex items-center justify-between">
                <h5 class="mb-2 text-lg font-bold tracking-tight text-gray-900 dark:text-white">Tropical Blend</h5>
                <h5 class="text-gray-900 dark:text-white">4.9</h5>
                </div>
                <p class="mb-3 font-normal text-gray-700 dark:text-gray-400">Pineapple, mango, and coconut water blended to perfection</p>
                <div class="flex items-center justify-between">
                <span class="text-gray-900 dark:text-white">$6.99</span>
                <button class="inline-flex items-center gap-2 px-3 py-2 text-sm font-medium text-center text-white bg-blue-700 rounded-lg hover:bg-blue-800 focus:ring-4 focus:outline-none focus:ring-blue-300 dark:bg-slate-950 dark:hover:bg-blue-700 dark:focus:ring-blue-800">
                    <img width="25" height="25" src="https://img.icons8.com/sf-ultralight-filled/25/FFFFFF/shopping-cart.png" alt="shopping-cart" />
                    Add
                </button>
                </div>
            </div>
        </div>

        <!-- Card 6: Detox Elixir -->
        <div class="w-full transition-shadow duration-300 ease-in-out 
             hover:shadow-xl/30 hover:shadow-xl/30 bg-white rounded-2xl shadow-sm dark:bg-gray-800">
            <div class="relative overflow-hidden rounded-t-2xl h-120">
                <img
                class="w-full h-full object-cover hover:scale-110 transition-transform duration-300"
                src="../assets/orange.jpg"
                alt="Detox Elixir"
                />
            </div>
            <div class="p-5">
                <div class="flex items-center justify-between">
                <h5 class="mb-2 text-lg font-bold tracking-tight text-gray-900 dark:text-white">Detox Elixir</h5>
                <h5 class="text-gray-900 dark:text-white">4.6</h5>
                </div>
                <p class="mb-3 font-normal text-gray-700 dark:text-gray-400">Cucumber, celery, ginger, and green apple for cleansing</p>
                <div class="flex items-center justify-between">
                <span class="text-gray-900 dark:text-white">$7.49</span>
                <button class="inline-flex items-center gap-2 px-3 py-2 text-sm font-medium text-center text-white bg-blue-700 rounded-lg hover:bg-blue-800 focus:ring-4 focus:outline-none focus:ring-blue-300 dark:bg-slate-950 dark:hover:bg-blue-700 dark:focus:ring-blue-800">
                    <img width="25" height="25" src="https://img.icons8.com/sf-ultralight-filled/25/FFFFFF/shopping-cart.png" alt="shopping-cart" />
                    Add
                </button>
                </div>
            </div>
        </div>
  </div>
</template>