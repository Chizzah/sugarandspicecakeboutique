<template>
  <layout>
    <section class="sm:text-xl lg:text-2xl">
      <section class="relative text-gray-100 bg-gray-900 lg:h-128">
        <g-image src="../../static/img/themed-cakes-in-oudtshoorn.webp" class="w-full h-full bg-gray-900 opacity-50 lg:object-fill" />
        <section class="mt-20 absolute w-full h-full top-0 left-0 flex flex-col items-center justify-start w-full lg:h-full lg:justify-start lg:mt-8">
          <h1 class="font-semibold text-center uppercase sm:mt-32 sm:text-2xl lg:text-4xl lg:mb-8">Make the day even better with epic <br> themed cakes!</h1>
          <h3 class="mx-4 my-4 font-semibold text-center lg:block lg:text-2xl lg:mb-20">Blow away all your guests or get the perfect Insta-Ready Cake for your <br> special occasion in Oudtshoorn.</h3>
        </section>
      </section>
      <section class="flex flex-col justify-center items-center text-center">
        <h2 class="mt-8 mb-4 text-pink-500 font-semibold uppercase sm:mt-20 sm:mb-12 sm:text-2xl lg:text-3xl lg:mb-16">Themed Cakes For All Occasions</h2>
        <p class="mx-4 mb-4 sm:mb-12 lg:mb-16 lg:w-256">Find your dream themed cake at Sugar & Spice Cake Boutique and wow the world from sunny Oudtshoorn.</p>
          <g-link to="/cakesinoudtshoorn"><button class="py-4 px-8 mb-8 text-sm text-gray-100 bg-pink-500 font-semibold rounded-full uppercase shadow hover:bg-pink-400 focus:outline-none sm:mb-20 sm:text-lg lg:text-xl">Get A Cake</button></g-link>
        <section class="flex flex-wrap justify-around items-center">
          <g-image class="my-8 rounded" src="../../static/img/themedcakes/dessert-table-1682509.webp" alt="" width="480" />
          <g-image class="my-8 rounded" src="../../static/img/themedcakes/pink-flamingo-on-top-of-a-cake-1359294 1.webp" alt="" width="480" />
          <g-image class="my-8 rounded" src="../../static/img/themedcakes/pratiksha-mohanty-SxHxyNx-6YI-unsplash.webp" alt="" width="480" />
          <g-image class="my-8 rounded" src="../../static/img/themedcakes/tim-cooper-TZbuwdps0rw-unsplash.webp" alt="" width="480" />
          <g-image class="my-8 rounded" src="../../static/img/themedcakes/unicorn-fondant-cake-2274464.webp" alt="" width="480" />
          <g-image class="my-8 rounded" src="../../static/img/themedcakes/white-cake-pops-2274473.webp" alt="" width="480" />
        </section>
      </section>
      <section class="text-blue-400 flex flex-col justify-center items-center">
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