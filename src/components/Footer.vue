<template>
  <footer class="text-gray-500 bg-blue-400 lg:rounded-lg lg:mb-16 lg:max-w-6xl lg:mx-auto">
    <section class="mt-8 border-b border-gray-600 border-solid lg:ml-24 lg:mt-16">
      <h4 class="pt-16 mx-8 mb-4 text-xs text-gray-100 font-semibold uppercase lg:text-lg">Cakes that delight</h4>
      <h2 class="mx-8 mb-6 text-gray-900 text-lg lg:text-3xl">Pleasure your tastebuds at Sugar And Spice Cake Boutique in Oudtshoorn, Klein Karoo!</h2>
      <h3 class="mx-8 mr-6 text-sm text-gray-100 lg:text-xl">Make a loved one's day even more special with our luxury cakes or come and treat yourself to a decadent slice and coffee at our cafe.</h3>
      <g-link to="/cakesinoudtshoorn"><button class="ml-8 my-8 py-4 px-8 text-gray-100 bg-pink-500 font-semibold rounded-full uppercase hover:bg-pink-400 focus:outline-none">Get A Cake</button></g-link>
    </section>
    <section class="flex flex-row items-start justify-around mb-8 text-sm text-left lg:justify-end lg:w-full lg:text-lg">
      <section class="my-8 ml-1 lg:mr-20">
        <h3 class="text-gray-900 font-semibold">Navigation</h3>
        <ul class="text-gray-100 rounded list-reset" v-for="navItem in navItems" :key="navItem.title">
          <li class="my-3">
            <g-link :to="`${navItem.route}`">{{ navItem.title }}</g-link>
          </li>
        </ul>
      </section>
      <section class="mt-8 lg:mr-16">
        <h3 class="text-gray-900 font-semibold">Cakes</h3>
        <ul class="text-gray-100 rounded list-reset" v-for="cakeItem in cakeItems" :key="cakeItem.title">
          <li class="my-3">
            <g-link :to="`${cakeItem.route}`">{{ cakeItem.title }}</g-link>
          </li>
        </ul>
      </section>
      <section class="mt-8 mr-2 lg:mr-16">
        <h3 class="text-gray-900 font-semibold">Get in touch</h3>
        <ul class="text-gray-100 rounded list-reset" v-for="contactItem in contactItems" :key="contactItem.title">
          <li class="my-3">
            <g-link :to="`${contactItem.route}`">{{ contactItem.title }}</g-link>
          </li>
        </ul>
      </section>
    </section>
    <section class="py-2 mx-4 text-gray-900 text-xs text-center border-solid lg:order-2">
      <p class="mb-4 lg:ml-16">JAMstack Website by <a href="http://chaddwebdesign.co.za" target="_blank"><span class="font-semibold hover:text-green-400">Chadd Web Design</span></a></p>
      <p class="mb-2 lg:ml-8 lg:mb-8">Copyright &copy; {{ new Date().getFullYear() }} Sugar And Spice Cake Boutique. All rights reserved.</p>
    </section>
  </footer>
</template>

<script>
export default {
  data() {
    return {
      navItems: [
        { title:'Home', route:'/' },
        { title:'About', route:'/about' },
        { title:'Blog', route:'/blog' },
        { title:'Privacy', route:'/privacypolicy' },
      ],
      cakeItems: [
        { title:'Daily Cakes', route:'/dailycakes' },
        { title:'Birthday Cakes', route:'/birthdaycakes' },
        { title:'Wedding Cakes', route:'/weddingcakes' },
        { title:'Themed Cakes', route:'/themedcakes' }
      ],
      contactItems: [
        { title:'Get A Cake', route:'/cakesinoudtshoorn' },
        { title:'Contact Us', route:'/contact' },
      ],
      isOpen: false,
    }
  }
}
</script>

<style lang="postcss">
  #neuButtons2 {
    box-shadow: 
    -12px -12px 12px 0 rgba(255,255,255,1),
    12px 12px 12px 0 rgba(255,255,255,1),
  }
</style>