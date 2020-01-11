<template>
  <header class="lg:text-xl">
    <nav class="flex items-center justify-between w-full py-2 text-gray-900">
      <div class="flex items-center justify-between py-2">
        <g-link to="/"><h1 class="flex ml-4 font-semibold text-lg text-blue-400 uppercase lg:text-3xl"><span class="flex text-pink-500 mr-1">Sugar <g-image src="../../static/svg/cupcake.svg" width="25" /> Spice</span> Cake Boutique</h1></g-link>
      </div>
      <div class="hidden lg:uppercase lg:font-semibold lg:flex lg:text-lg lg:items-center">
        <ul class="mr-4" v-for="menuItem in menuItems" :key="menuItem.title">
          <li class="lg:px-2">
            <g-link class="text-blue-400 hover:text-pink-400" :to="menuItem.route">{{ menuItem.title }}</g-link>
          </li>
        </ul>
        <g-link to="/cakesinoudtshoorn"><button class="px-4 py-3 mr-4 mr-8 text-sm font-semibold text-gray-100 bg-pink-400 shadow rounded-full uppercase focus:outline-none">Get A Cake</button></g-link>
      </div>
      <div class="px-4 py-2 lg:hidden">
        <button @click="isOpen = !isOpen" type="button" class="block focus:outline-none">
          <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><line x1="1" y1="12" x2="21" y2="12"></line><line x1="1" y1="6" x2="21" y2="6"></line><line x1="1" y1="18" x2="21" y2="18"></line></svg>
        </button>
      </div>
    </nav>
    <nav :class="isOpen ? 'block' : 'hidden'" class="z-50 flex flex-col items-center justify-center block w-full py-4 text-sm font-semibold uppercase lg:p-0">
      <div class="mb-2 ml-8">
        <ul class="rounded list-reset lg:hidden" v-for="menuItem in menuItems" :key="menuItem.title">
          <li class="py-2">
            <g-link class="text-blue-400 hover:text-pink-400" :to="menuItem.route">{{ menuItem.title }}</g-link>
          </li>
        </ul>
      </div>
    </nav>
  </header>
</template>

<script>
export default {
  data() {
    return {
      menuItems: [
        { title:'Home', route:'/' },
        { title:'About', route:'/about' },
        { title:'Blog', route:'/blog' },
        { title:'Contact', route:'/Contact' }
      ],
      isOpen: false,
    }
  }
}
</script>