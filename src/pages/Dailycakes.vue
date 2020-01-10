<template>
  <layout>
    <section>
      <section class="relative text-gray-100 bg-gray-900 md:h-screen">
        <g-image src="../../static/img/daily-cakes-in-oudtshoorn.webp" class="w-full h-full bg-gray-900 opacity-75 md:opacity-25 md:object-cover" />
        <section class="absolute w-full h-full top-0 left-0 flex flex-col items-center justify-start w-full md:h-full mt-20 md:justify-start md:mt-56">
          <h1 class="mx-6 font-semibold text-center uppercase md:text-4xl md:mx-128 md:mb-20">Visit the Sugar & Spice Cake Boutique cafe to taste our daily cakes</h1>
          <h3 class="mx-4 my-4 font-semibold text-center md:block md:text-2xl md:mx-110 md:mb-20">Come enjoy a coffee at our cafe in Oudtshoorn and have a slice of our daily cakes in rotation!</h3>
        </section>
      </section>
      <section class="flex flex-col justify-center items-center text-center">
        <h2 class="mt-8 mb-4 text-pink-600 font-semibold uppercase">Daily Cakes For Any Time</h2>
        <p class="mx-4 mb-4">Our cafe in Oudtshoorn hosts amazing cakes we bake daily to pleasure your taste buds while enjoying a fresh cup of coffee. So head over to Sugar & Spice Cake Boutique and treat yourself and a loved one to pure bliss.</p>
          <g-link to="/cakesinoudtshoorn"><button id="neuButtons1" class="py-4 px-8 mb-8 text-sm text-gray-100 bg-pink-600 font-semibold rounded-full uppercase shadow hover:bg-pink-400 focus:outline-none">Get A Cake</button></g-link>
        <section class="flex flex-wrap justify-around items-center">
          <g-image class="my-8 rounded" src="../../static/img/dailycakes/berry-blueberries-blueberry-cake-461431.webp" alt="" width="150" />
          <g-image class="my-8 rounded" src="../../static/img/dailycakes/butter-cookie-cake-toppings-with-fruits-1291712.webp" alt="" width="150" />
          <g-image class="my-8 rounded" src="../../static/img/dailycakes/cake-near-white-ceramic-plate-on-brown-wooden-table-804170.webp" alt="" width="150" />
          <g-image class="my-8 rounded" src="../../static/img/dailycakes/close-up-photography-of-sliced-cake-806363.webp" alt="" width="150" />
          <g-image class="my-8 rounded" src="../../static/img/dailycakes/photo-of-brown-and-white-icing-covered-cake-with-kiwi-1027811.webp" alt="" width="150" />
          <g-image class="my-8 rounded" src="../../static/img/dailycakes/photo-of-chocolate-cake-2144200.webp" alt="" width="150" />
          <g-image class="my-8 rounded" src="../../static/img/dailycakes/shallow-focus-photography-cake-with-red-strawberry-on-top-1120970.webp" alt="" width="150" />
          <g-image class="my-8 rounded" src="../../static/img/dailycakes/white-cheesecake-on-wooden-surface-219293.webp" alt="" width="150" />
        </section>
      </section>
      <section class="text-blue-300 flex flex-col justify-center items-center">
        <h2 class="mt-8 mb-4 text-pink-400 font-semibold uppercase">Also Check Out</h2>
        <section class="mb-8 flex justify-around items-center font-semibold">
          <g-link class="mr-4 hover:text-pink-400" to="/birthdaycakes">Birthday Cakes</g-link>
          <g-link class="mr-4 hover:text-pink-400" to="/weddingcakes">Wedding Cakes</g-link>
          <g-link class="hover:text-pink-400" to="/themedcakes">Themed Cakes</g-link>
        </section>
      </section>
    </section>
  </layout>
</template>