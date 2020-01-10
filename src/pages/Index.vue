<template>
  <Layout>
    <section>
      <section class="relative text-gray-100 bg-gray-900 md:h-screen">
        <g-image src="../../static/img/cake-shop-and-restaurant-in-oudtshoorn.webp" class="w-full h-full bg-gray-900 opacity-75 md:opacity-25 md:object-cover" />
        <section class="absolute w-full h-full top-0 left-0 flex flex-col items-center justify-start w-full md:h-full mt-20 md:justify-start md:mt-56">
          <h1 class="mx-12 font-semibold text-center uppercase md:text-4xl md:mx-128 md:mb-20">Delightful cake shop & restaurant in Oudtshoorn</h1>
          <h3 class="mx-4 my-4 font-semibold text-center md:block md:text-2xl md:mx-110 md:mb-20">Enjoy the best coffee and cakes in Oudtshoorn, Klein Karoo</h3>
        </section>
      </section>
      <section class="flex flex-col justify-center items-center text-center">
        <h2 class="mt-8 mb-4 text-pink-600 font-semibold uppercase">Pleasure your tastebuds at <br> Sugar & Spice</h2>
        <p class="mx-4 mb-4">Come visit us in Oudtshoorn and enjoy a delicious coffee and a slice of decadent cake. You can even order a cake or book our venue for a special occation!</p>
        <g-link to="/cakesinoudtshoorn"><button id="neuButtons1" class="py-4 px-8 mb-8 text-sm text-gray-100 bg-pink-600 font-semibold rounded-full uppercase shadow hover:bg-pink-400 focus:outline-none">Get A Cake</button></g-link>
      </section>
      <section class="py-8 bg-pink-100">
        <h2 id="blue-300" class="mt-2 mb-8 mx-12 text-blue-300 font-semibold text-center uppercase">Browse our delicious selection of cakes</h2>
        <section>
          <section class="mb-8 flex justify-around items-center">
            <section class="relative bg-black rounded-full border-4 border-solid border-blue-300">
              <g-link to="/dailycakes"><g-image class="opacity-75 rounded-full" src="../../static/img/sugar-and-spice-cake-boutique-in-oudtshoorn-daily-cakes.webp" alt="" width="150" />
              <section class="absolute w-full h-full top-0 left-0 flex justify-center items-center">
                <h3 class="text-gray-100 font-semibold">Daily Cakes</h3>
              </section></g-link>
            </section>
            <section class="relative bg-black rounded-full border-4 border-solid border-blue-300">
              <g-link to="/birthdaycakes"><g-image class="opacity-75 rounded-full" src="../../static/img/sugar-and-spice-cake-boutique-in-oudtshoorn-birthday-cakes.webp" alt="" width="150" />
              <section class="absolute w-full h-full top-0 left-0 flex justify-center items-center">
                <h3 class="text-gray-100 font-semibold">Birthday Cakes</h3>
              </section></g-link>
            </section>
          </section>
          <section class="flex justify-around items-center">
            <section class="relative bg-black rounded-full border-4 border-solid border-blue-300">
              <g-link to="/weddingcakes"><g-image class="opacity-75 rounded-full" src="../../static/img/sugar-and-spice-cake-boutique-in-oudtshoorn-wedding-cakes.webp" alt="" width="150" />
              <section class="absolute w-full h-full top-0 left-0 flex justify-center items-center">
                <h3 class="text-gray-100 font-semibold">Wedding Cakes</h3>
              </section></g-link>
            </section>
            <section class="relative bg-black rounded-full border-4 border-solid border-blue-300">
              <g-link to="/themedcakes"><g-image class="opacity-75 rounded-full" src="../../static/img/sugar-and-spice-cake-boutique-in-oudtshoorn-themed-cakes.webp" alt="" width="150" />
              <section class="absolute w-full h-full top-0 left-0 flex justify-center items-center">
                <h3 class="text-gray-100 font-semibold">Themed Cakes</h3>
              </section></g-link>
            </section>
          </section>
        </section>
      </section>
      <section class="py-8 flex flex-col justify-center items-center">
        <h2 class="mt-2 mb-8 mx-12 text-pink-600 font-semibold text-center uppercase">See what our customers have to say!</h2>
        <section>
          <section class="flex flex-col justify-center items-center">
            <g-image class="rounded-full border-4 border-solid border-pink-600" src="../../static/img/testimonial1.webp" alt="" width="125" />
            <p class="mx-4 my-8 text-center">Zwanai Botha - "Goeie diens die vrou doen moeite al is sy toe onder werk help sy as sy kan dankie dat jy op n besige naweek vir my kan help jy is tops kan jou aanbeveel vir ander"</p>
          </section>
          <section class="flex flex-col justify-center items-center">
            <g-image class="rounded-full border-4 border-solid border-pink-600" src="../../static/img/testimonial2.webp" alt="" width="125" />
            <p class="mx-4 my-8 text-center">Aneen Lewis - "Beautiful and creative also the cakes are amazing"</p>
          </section>
          <section class="flex flex-col justify-center items-center">
            <g-image class="rounded-full border-4 border-solid border-pink-600" src="../../static/img/testimonial3.webp" alt="" width="125" />
            <p class="mx-4 my-8 text-center">Random - "Lorem ipsum dolor sit amet consectetur adipisicing elit. Minima minus architecto nemo nihil numquam."</p>
          </section>
        </section>
      </section>
      <section class="py-8 bg-pink-100 flex flex-col justify-center items-center text-center">
        <h2 class="mt-8 mb-8 mx-12 text-blue-300 font-semibold text-center uppercase">Need to find us?</h2>
        <p class="mx-4 mb-8">Check out our contact page to get in touch with us via phone or to find our location</p>
        <g-link to="/contact"><button id="neuButtons1" class="py-4 px-8 mb-8 text-sm text-gray-100 bg-blue-300 font-semibold rounded-full uppercase shadow focus:outline-none">Contact Us</button></g-link>
      </section>
    </section>
  </Layout>
</template>