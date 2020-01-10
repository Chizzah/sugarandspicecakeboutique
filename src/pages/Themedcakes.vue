<template>
  <layout>
    <section>
      <section class="relative text-gray-100 bg-gray-900 md:h-screen">
        <g-image src="../../static/img/themed-cakes-in-oudtshoorn.webp" class="w-full h-full bg-gray-900 opacity-75 md:opacity-25 md:object-cover" />
        <section class="absolute w-full h-full top-0 left-0 flex flex-col items-center justify-start w-full md:h-full mt-20 md:justify-start md:mt-56">
          <h1 class="mx-12 font-semibold text-center uppercase md:text-4xl md:mx-128 md:mb-20">Make the day even better with epic themed cakes!</h1>
          <h3 class="mx-4 my-4 font-semibold text-center md:block md:text-2xl md:mx-110 md:mb-20">Blow away all your guests or get the perfect Insta-Ready Cake for your special occasion in Oudtshoorn.</h3>
        </section>
      </section>
      <section class="flex flex-col justify-center items-center text-center">
        <h2 class="mt-8 mb-4 text-pink-600 font-semibold uppercase">Themed Cakes For All Occasions</h2>
        <p class="mx-4 mb-4">Find your dream themed cake at Sugar & Spice Cake Boutique and wow the world from sunny Oudtshoorn.</p>
          <g-link to="/cakesinoudtshoorn"><button id="neuButtons1" class="py-4 px-8 mb-8 text-sm text-gray-100 bg-pink-600 font-semibold rounded-full uppercase shadow hover:bg-pink-400 focus:outline-none">Get A Cake</button></g-link>
        <section class="flex flex-wrap justify-around items-center">
          <g-image class="my-8 rounded" src="../../static/img/themedcakes/dessert-table-1682509.webp" alt="" width="150" />
          <g-image class="my-8 rounded" src="../../static/img/themedcakes/pink-flamingo-on-top-of-a-cake-1359294 1.webp" alt="" width="150" />
          <g-image class="my-8 rounded" src="../../static/img/themedcakes/pratiksha-mohanty-SxHxyNx-6YI-unsplash.webp" alt="" width="150" />
          <g-image class="my-8 rounded" src="../../static/img/themedcakes/tim-cooper-TZbuwdps0rw-unsplash.webp" alt="" width="150" />
          <g-image class="my-8 rounded" src="../../static/img/themedcakes/unicorn-fondant-cake-2274464.webp" alt="" width="150" />
          <g-image class="my-8 rounded" src="../../static/img/themedcakes/white-cake-pops-2274473.webp" alt="" width="150" />
        </section>
      </section>
      <section class="text-blue-300 flex flex-col justify-center items-center">
        <h2 class="mt-8 mb-4 text-pink-400 font-semibold uppercase">Also Check Out</h2>
        <section class="mb-8 flex justify-around items-center font-semibold">
          <g-link class="mr-4 hover:text-pink-400" to="/dailycakes">Daily Cakes</g-link>
          <g-link class="mr-4 hover:text-pink-400" to="/birthdaycakes">Birthday Cakes</g-link>
          <g-link class="hover:text-pink-400" to="/weddingcakes">Wedding Cakes</g-link>
        </section>
      </section>
    </section>
  </layout>
</template>