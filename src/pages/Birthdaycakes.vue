<template>
  <layout>
    <section>
      <section class="relative text-gray-100 bg-gray-900 md:h-screen">
        <g-image src="../../static/img/birthday-cakes-in-oudtshoorn.webp" class="w-full h-full bg-gray-900 opacity-75 md:opacity-25 md:object-cover" />
        <section class="absolute w-full h-full top-0 left-0 flex flex-col items-center justify-start w-full md:h-full mt-20 md:justify-start md:mt-56">
          <h1 class="mx-12 font-semibold text-center uppercase md:text-4xl md:mx-128 md:mb-20">What's a birthday without a birthday cake?</h1>
          <h3 class="mx-4 my-4 font-semibold text-center md:block md:text-2xl md:mx-110 md:mb-20">Get a loved one an amazing birthday cake at Sugar & Spice Cake Boutique in Oudtshoorn, Klein Karoo.</h3>
        </section>
      </section>
      <section class="flex flex-col justify-center items-center text-center">
        <h2 class="mt-8 mb-4 text-pink-500 font-semibold uppercase">Birthday Cakes For Loved Ones</h2>
        <p class="mx-4 mb-4">Make their day even more amazing with the most delicious cake in Oudtshoorn. Only at Sugar & Spice Cake Boutique!</p>
          <g-link to="/cakesinoudtshoorn"><button id="neuButtons1" class="py-4 px-8 mb-8 text-sm text-gray-100 bg-pink-500 font-semibold rounded-full uppercase shadow hover:bg-pink-500 focus:outline-none">Get A Cake</button></g-link>
        <section class="flex flex-wrap justify-around items-center">
          <g-image class="my-8 rounded" src="../../static/img/birthdaycakes/baby-boy-cake-child-961192.webp" alt="" width="150" />
          <g-image class="my-8 rounded" src="../../static/img/birthdaycakes/baby-eating-cake-2116103 1.webp" alt="" width="150" />
          <g-image class="my-8 rounded" src="../../static/img/birthdaycakes/beautiful-birthday-cake.webp" alt="" width="150" />
          <g-image class="my-8 rounded" src="../../static/img/birthdaycakes/lighted-candles-on-white-icing-covered-cake-1729808 1.webp" alt="" width="150" />
          <g-image class="my-8 rounded" src="../../static/img/birthdaycakes/birthday-cake-in-men-s-hands-6203 1.webp" alt="" width="150" />
          <g-image class="my-8 rounded" src="../../static/img/birthdaycakes/close-up-photography-of-pink-birthday-cake-851204 1.webp" alt="" width="150" />
          <g-image class="my-8 rounded" src="../../static/img/birthdaycakes/baked-cake-on-gray-cake-stand-on-glass-table-1835765 1.webp" alt="" width="150" />
          <g-image class="my-8 rounded" src="../../static/img/birthdaycakes/man-and-woman-holding-a-child-3234124.webp" alt="" width="150" />
        </section>
      </section>
      <section class="text-blue-400 flex flex-col justify-center items-center">
        <h2 class="mt-8 mb-4 text-pink-500 font-semibold uppercase">Also Check Out</h2>
        <section class="mb-8 flex justify-around items-center font-semibold">
          <g-link class="mr-4 hover:text-pink-500" to="/dailycakes">Daily Cakes</g-link>
          <g-link class="mr-4 hover:text-pink-500" to="/weddingcakes">Wedding Cakes</g-link>
          <g-link class="hover:text-pink-500" to="/themedcakes">Themed Cakes</g-link>
        </section>
      </section>
    </section>
  </layout>
</template>