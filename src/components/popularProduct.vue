<script lang="ts" setup>
    import berry from '@/assets/berry.jpg'
    import greenJuiceImg   from '@/assets/green_juice.jpg';
    import citrusImg       from '@/assets/pexels-berkncn-31546996.jpg';
    import watermelonImg   from '@/assets/watermelon.jpg';
    import tropicalImg     from '@/assets/drink2.jpg';
    import detoxImg        from '@/assets/orange.jpg';

    const drinks = [
        {
            id: 1,
            title: "Berry Smoothie Bowl",
            description: "Mixed berries blended with yogurt and topped with granola",
            price: "$7.99",
            rate: 4.9,
            imageUrl: berry
        }, 
        {
            id: 2,
            title: "Green Juice",
            description: "Spinach, kale, cucumber, and apple for ultimate refreshment",
            price: "$4.99",
            rate: 4.7,
            imageUrl: greenJuiceImg

        }, 
        {
            id: 3,
            title: "Citrus Juice",
            description: "Orange, grapefruit, and lemon for a zesty morning boost",
            price: "$5.99",
            rate: 4.8,
            imageUrl: citrusImg

        }, 
        {
            id: 4,
            title: "Watermelon Refresher",
            description: "Fresh watermelon juice with a hint of mint and lime",
            price: "$7.99",
            rate: 4.8,
            imageUrl: watermelonImg

        }, 
        {
            id: 5,
            title: "Tropical Blend",
            description: "Pineapple, mango, and coconut water blended to perfection",
            price: "$7.99",
            rate: 4.8,
            imageUrl: tropicalImg

        }, 
        {
            id: 6,
            title: "Detox Elixir",
            description: "Cucumber, celery, ginger, and green apple for cleansing",
            price: "$7.99",
            rate: 4.8,
            imageUrl: detoxImg

        }, 
    ]

    // drinks.forEach(drink => {
    //     console.log(drink.imageUrl)
    // })
    console.log(drinks)
// import { ref } from 'vue';

    // const isLifted = ref(false)
    // function toogle() {
    //     isLifted.value = !isLifted.value
    // }
</script>

<template>
    <div class="flex flex-col items-center justify center">
        <h1 class="text-5xl font-bold mb-10">Our Popular Drinks</h1>
        <p class="text-xl">Handcrafted with love and the freshest ingredients. Every sip is a journey to flavor paradise.</p>
    </div>
    <div class="mt-20 mb-30 grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 place-items-center gap-20">
    <div
      v-for="drink in drinks"
      :key="drink.id"
      :ref="drink.id === 1 ? 'target' : undefined"
      class="w-full transition-all duration-500 ease-in-out focus:shadow-xl/30 active:-translate-y-2 focus:-translate-y-2 hover:shadow-xl/30 hover:-translate-y-2 bg-white rounded-2xl shadow-sm dark:bg-gray-800"
    >
      <div class="relative overflow-hidden rounded-t-2xl h-120">
        <!-- Badge (only if defined) -->
        <div
          :class="drink.id == 1 ? 'absolute left-5 top-5 z-20 px-5 rounded-4xl bg-orange-300 text-sm font-medium' : 'hidden'"
        >
        Best Seller
        </div>
        <div
          :class="drink.id == 2 ? 'absolute left-5 top-5 z-20 px-5 rounded-4xl bg-orange-300 text-sm font-medium' : 'hidden'"
        >
        New
        </div>

        <picture>
          <img
            fetchpriority="high"
            decoding="async"
            loading="lazy"
            role="presentation"
            class="w-full h-full object-cover hover:scale-110 transition-transform duration-300"
            :src="drink.imageUrl"
            :alt="drink.title"

          />
        </picture>
      </div>

      <div class="p-5">
        <div class="flex items-center justify-between">
          <h5 class="mb-2 text-lg font-bold tracking-tight text-gray-900 dark:text-white">
            {{ drink.title }}
          </h5>
          <h5 class="text-gray-900 dark:text-white">{{ drink.rate }}</h5>
        </div>

        <p class="mb-3 font-normal text-gray-700 dark:text-gray-400">
          {{ drink.description }}
        </p>

        <div class="flex items-center justify-between">
          <span class="text-gray-900 dark:text-white">{{ drink.price }}</span>
          <button
            class="inline-flex items-center gap-2 px-3 py-2 text-sm font-medium text-center text-white bg-blue-700 rounded-lg hover:bg-blue-800 focus:outline-none focus:ring-4 focus:ring-blue-300 dark:bg-slate-950 dark:hover:bg-blue-700 dark:focus:ring-blue-800"
          >
            <img
              width="25"
              height="25"
              src="https://img.icons8.com/sf-ultralight-filled/25/FFFFFF/shopping-cart.png"
              alt="shopping-cart"
            />
            Add
          </button>
        </div>
      </div>
    </div>
        

  </div>
</template>