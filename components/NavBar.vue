<template>
    <div >
      <nav class="bg-white shadow-lg">
        <div class="max-w-6xl mx-auto px-4">
          <div class="flex justify-between">
            <div class="flex space-x-7">
              <div>
                <nuxt-link to="/" class="flex items-center py-4 px-2">
              <img src="~/assets/logo.png" alt="logo" class="h-8 w-8 mr-2" />
                </nuxt-link>
              </div>
              <!-- Primary navbar items -->
              <div class="hidden md:flex items-center space-x-1">
                <nuxt-link to="" class="py-4 px-2 text-green-500 border-green-500 font-semibold ">Home</nuxt-link>
                <nuxt-link to="" class="py-4 px-2 text-green-500 text-gray-500 font-semibold transition duration-300">About Me</nuxt-link>
                <nuxt-link to="" class="py-4 px-2 text-green-500 text-gray-500 font-semibold transition duration-300">Quotes</nuxt-link>
              </div>
            </div>
            <!-- secondary navbar items -->
            <div class="hidden md:flex items-center space-x-3">
              <nuxt-link to="" class="py-2 px-2 font-medium text-gray-500 rounded hover:bg-green-500 hover:text-white transition duration-300">Article</nuxt-link>
            </div>
            <!-- Mobile menu button -->
            <div class="md:hidden flex items-center">
              <button class="outline-none mobile-menu-button">
                <svg class=" w-6 h-6 text-gray-500 hover:text-green-500 "
							    x-show="!showMenu"
							    fill="none"
							    stroke-linecap="round"
							    stroke-linejoin="round"
							    stroke-width="2"
							    viewBox="0 0 24 24"
							    stroke="currentColor"
						    >
							  <path d="M4 6h16M4 12h16M4 18h16"></path>
						    </svg>
              </button>
            </div>
          </div>
        </div>
        <!-- mobile menu -->
        <div class="hidden mobile-menu">
          <ul class="">
            <li class="active"><nuxt-link to="" class="block text-sm px-2 py-4 text-white bg-green-500 font-semibold">Home</nuxt-link></li>
            <li><nuxt-link to="" class="block text-sm px-2 py-4 hover:bg-green-500 transition duration-300 ">Home</nuxt-link></li>
            <li><nuxt-link to="" class="block text-sm px-2 py-4 hover:bg-green-500 transition duration-300 ">Home</nuxt-link></li>
            <li><nuxt-link to="" class="block text-sm px-2 py-4 hover:bg-green-500 transition duration-300 ">Home</nuxt-link></li>
          </ul>
        </div>
      </nav>
    </div>
</template>

<script>
export default {
  setup() {
    
  },
  // mounted() {
  //   const btn = document.querySelector("button.mobile-menu-button");
  //   const menu = document.querySelector(".mobile-menu");
  //   btn.addEventListener("click", () => {
  //     menu.classList.toggle("hidden");
  //   });
  // }
  
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=B612+Mono&display=swap');
</style> 