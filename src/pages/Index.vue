<template>
  <Layout>
    <section class="sm:text-xl lg:text-2xl">
      <section class="relative text-gray-100 bg-gray-900 lg:h-128">
        <g-image src="../../static/img/cake-shop-and-restaurant-in-oudtshoorn.webp" class="w-full h-full bg-gray-900 opacity-50 lg:object-cover" />
        <section class="mt-20 absolute w-full h-full top-0 left-0 flex flex-col items-center justify-start w-full lg:h-full lg:justify-start lg:mt-8">
          <h1 class="font-semibold text-center uppercase sm:mt-32 sm:text-2xl lg:text-4xl lg:mb-8">Delightful cake shop & restaurant <br> in Oudtshoorn</h1>
          <h3 class="mx-4 my-4 font-semibold text-center sm:text-xl lg:block lg:text-3xl lg:mx-110 lg:mb-20">Enjoy the best coffee and cakes in Oudtshoorn, Klein Karoo.</h3>
        </section>
      </section>
      <section class="flex flex-col justify-center items-center text-center">
        <h2 class="mt-8 mb-4 text-pink-500 font-semibold uppercase sm:mt-20 sm:mb-12 sm:text-2xl lg:text-3xl lg:mb-16">Pleasure your tastebuds <br> at Sugar & Spice Cake Boutique</h2>
        <p class="mx-4 mb-4 sm:mb-12 lg:w-128">Come visit us in Oudtshoorn and enjoy a delicious coffee and a slice of decadent cake. You can even order a cake or book our venue for a special occation!</p>
        <g-link to="/cakesinoudtshoorn"><button class="py-4 px-8 mb-8 text-sm text-gray-100 bg-pink-500 font-semibold rounded-full uppercase shadow hover:bg-pink-400 focus:outline-none sm:mb-20 sm:text-lg lg:text-xl">Get A Cake</button></g-link>
      </section>
      <section class="py-8 bg-pink-100 sm:py-16">
        <h2 class="mt-2 mb-8 text-blue-400 font-semibold text-center uppercase sm:mb-12 sm:text-2xl lg:text-3xl lg:mb-16">Browse our delicious and decadent <br> selection of cakes</h2>
        <section class="lg:flex lg:justify-center lg:items-center lg:text-center">
          <section class="mb-8 flex justify-around items-center lg:mb-0">
            <section class="relative bg-black rounded-full border-4 border-solid border-blue-400 sm:ml-12">
              <g-link to="/dailycakes"><g-image class="opacity-75 rounded-full" src="../../static/img/sugar-and-spice-cake-boutique-in-oudtshoorn-daily-cakes.webp" alt="" width="150" />
              <section class="absolute w-full h-full top-0 left-0 flex justify-center items-center">
                <h3 class="text-gray-100 font-semibold">Daily Cakes</h3>
              </section></g-link>
            </section>
            <section class="relative bg-black rounded-full border-4 border-solid border-blue-400 sm:mr-12 lg:mr-0 lg:ml-16">
              <g-link to="/birthdaycakes"><g-image class="opacity-75 rounded-full" src="../../static/img/sugar-and-spice-cake-boutique-in-oudtshoorn-birthday-cakes.webp" alt="" width="150" />
              <section class="absolute w-full h-full top-0 left-0 flex justify-center items-center">
                <h3 class="text-gray-100 font-semibold">Birthday Cakes</h3>
              </section></g-link>
            </section>
          </section>
          <section class="flex justify-around items-center">
            <section class="relative bg-black rounded-full border-4 border-solid border-blue-400 sm:ml-12 lg:ml-16">
              <g-link to="/weddingcakes"><g-image class="opacity-75 rounded-full" src="../../static/img/sugar-and-spice-cake-boutique-in-oudtshoorn-wedding-cakes.webp" alt="" width="150" />
              <section class="absolute w-full h-full top-0 left-0 flex justify-center items-center">
                <h3 class="text-gray-100 font-semibold">Wedding Cakes</h3>
              </section></g-link>
            </section>
            <section class="relative bg-black rounded-full border-4 border-solid border-blue-400 sm:mr-12 lg:mr-0 lg:ml-16">
              <g-link to="/themedcakes"><g-image class="opacity-75 rounded-full" src="../../static/img/sugar-and-spice-cake-boutique-in-oudtshoorn-themed-cakes.webp" alt="" width="150" />
              <section class="absolute w-full h-full top-0 left-0 flex justify-center items-center">
                <h3 class="text-gray-100 font-semibold">Themed Cakes</h3>
              </section></g-link>
            </section>
          </section>
        </section>
      </section>
      <section class="py-8 flex flex-col justify-center items-center sm:py-16">
        <h2 class="mt-2 mb-8 text-pink-500 font-semibold text-center uppercase sm:text-2xl lg:text-3xl lg:mb-16">See what our customers <br> have to say!</h2>
        <section>
          <section class="flex flex-col justify-center items-center sm:flex-row">
            <g-image class="rounded-full border-4 border-solid border-pink-500" src="../../static/img/testimonial1.webp" alt="" width="125" />
            <p class="mx-4 my-8 text-center sm:w-96 sm:ml-12"><span class="text-blue-400">"</span>Goeie diens die vrou doen moeite al is sy toe onder werk help sy as sy kan dankie dat jy op n besige naweek vir my kan help jy is tops kan jou aanbeveel vir ander<span class="text-blue-400">"</span> <br> - <span class="text-blue-400">Zwanai Botha</span></p>
          </section>
          <section class="flex flex-col justify-center items-center sm:mb-8 sm:flex-row">
            <g-image class="rounded-full border-4 border-solid border-pink-500" src="../../static/img/testimonial2.webp" alt="" width="125" />
            <p class="mx-4 my-8 text-center sm:w-96 sm:ml-12"><span class="text-blue-400">"</span>Beautiful and creative also the cakes are amazing<span class="text-blue-400">"</span> <br> - <span class="text-blue-400">Aneen Lewis</span></p>
          </section>
          <section class="flex flex-col justify-center items-center sm:flex-row">
            <g-image class="rounded-full border-4 border-solid border-pink-500" src="../../static/img/testimonial3.webp" alt="" width="125" />
            <p class="mx-4 my-8 text-center sm:w-96 sm:ml-12"><span class="text-blue-400">"</span>Lorem ipsum dolor sit amet consectetur adipisicing elit. Minima minus architecto nemo nihil numquam.<span class="text-blue-400">"</span> <br> - <span class="text-blue-400">Random</span></p>
          </section>
        </section>
      </section>
      <section class="py-8 bg-pink-100 flex flex-col justify-center items-center text-center">
        <h2 class="mt-8 mb-8 text-blue-400 font-semibold text-center uppercase">Need to find us?</h2>
        <p class="mx-4 mb-8">Check out our contact page to get in touch with us via phone or to find our location</p>
        <g-link to="/contact"><button class="py-4 px-8 mb-8 text-sm text-gray-100 bg-blue-400 font-semibold rounded-full uppercase shadow focus:outline-none">Contact Us</button></g-link>
      </section>
    </section>
  </Layout>
</template>

<script>
export default {
  metaInfo: {
    title: "Beautiful and Delicious Cakes in Oudtshoorn | Sugar And Spice Cake Boutique",
    meta: [
      {
        name:"description",
        content: "Make a loved one's day with one of our amazing cakes for any occasion or come enjoy a coffe and slice at our restaurant in Oudtshoorn",
      }
    ]
  },
}
</script>