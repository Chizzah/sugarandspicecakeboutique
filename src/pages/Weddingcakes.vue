<template>
  <layout>
    <section class="sm:text-xl lg:text-2xl">
      <section class="relative text-gray-100 bg-gray-900 lg:h-128">
        <g-image src="../../static/img/wedding-cakes-in-oudtshoorn.webp" class="w-full h-full bg-gray-900 opacity-50 lg:object-fill" />
        <section class="mt-20 absolute w-full h-full top-0 left-0 flex flex-col items-center justify-start w-full lg:h-full lg:justify-start lg:mt-8">
          <h1 class="font-semibold text-center uppercase sm:mt-32 sm:text-2xl lg:text-4xl lg:mb-8">Find the perfect wedding cake for <br> your special day</h1>
          <h3 class="mx-4 my-4 font-semibold text-center lg:block lg:text-2xl lg:mb-20">Sugar & Spice Cake Boutique in Oudtshoorn makes cakes that fit great on your wedding day!</h3>
        </section>
      </section>
      <section class="flex flex-col justify-center items-center text-center">
        <h2 class="mt-8 mb-4 text-pink-500 font-semibold uppercase sm:mt-20 sm:mb-12 sm:text-2xl lg:text-3xl lg:mb-16">Wedding Cakes For Any Theme</h2>
        <p class="mx-4 mb-4 sm:mb-12 lg:mb-16 lg:w-256">Whether its traditional fondant, white butter icing or naked cakes you need in Oudtshoorn. Sugar & Spice Cake Boutique is sure to make your special day even more special!</p>
          <g-link to="/cakesinoudtshoorn"><button class="py-4 px-8 mb-8 text-sm text-gray-100 bg-pink-500 font-semibold rounded-full uppercase shadow hover:bg-pink-400 focus:outline-none sm:mb-20 sm:text-lg lg:text-xl">Get A Cake</button></g-link>
        <section class="flex flex-wrap justify-around items-center">
          <g-image class="my-8 rounded" src="../../static/img/weddingcakes/3-layer-cake-with-flowers-2337818.webp" alt="" width="480" />
          <g-image class="my-8 rounded" src="../../static/img/weddingcakes/bloom-blooming-blossom-blur-460075.webp" alt="" width="480" />
          <g-image class="my-8 rounded" src="../../static/img/weddingcakes/bride-and-groom-cutting-a-huge-5-layered-wedding-cake-3018810.webp" alt="" width="480" />
          <g-image class="my-8 rounded" src="../../static/img/weddingcakes/close-up-photo-of-two-layered-cake-1869342.webp" alt="" width="480" />
          <g-image class="my-8 rounded" src="../../static/img/weddingcakes/people-cutting-cake-2038258.webp" alt="" width="480" />
          <g-image class="my-8 rounded" src="../../static/img/weddingcakes/person-holding-knife-slicing-3-layer-cake-1345574.webp" alt="" width="480" />
          <g-image class="my-8 rounded" src="../../static/img/weddingcakes/white-fondant-icings-and-champagne-flute-glass-1405494.webp" alt="" width="480" />
          <g-image class="my-8 rounded" src="../../static/img/weddingcakes/white-icing-cover-cake-1702373.webp" alt="" width="480" />
        </section>
      </section>
      <section class="text-blue-400 flex flex-col justify-center items-center">
        <h2 class="mt-8 mb-4 text-pink-400 font-semibold uppercase">Also Check Out</h2>
        <section class="mb-8 flex justify-around items-center font-semibold">
          <g-link class="mr-4 hover:text-pink-400" to="/dailycakes">Daily Cakes</g-link>
          <g-link class="mr-4 hover:text-pink-400" to="/birthdaycakes">Birthday Cakes</g-link>
          <g-link class="hover:text-pink-400" to="/themedcakes">Themed Cakes</g-link>
        </section>
      </section>
    </section>
  </layout>
</template>