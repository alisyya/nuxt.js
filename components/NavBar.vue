<template>
    <div >
        <nav class="fixed top-0 font-sans flex flex-col h-20 content-center sm:flex-row  sm:justify-between shadow sm:items-center w-full z-20">
  <div>
    <nuxt-link to="/">
    <img class="h-12 w-14 pl-4" clas src="~/assets/logo.png" >
    </nuxt-link>
  </div>
  <div>
    <nuxt-link class="text-lg no-underline text-grey-darkest hover:text-blue-dark ml-2" to="/Experience">Experience</nuxt-link>
    <nuxt-link class="text-lg no-underline text-grey-darkest hover:text-blue-dark ml-2" to="/p2">About</nuxt-link>
    <nuxt-link class="text-lg no-underline text-grey-darkest hover:text-blue-dark ml-2" to="/p3">Quotes</nuxt-link>
  </div>
</nav>
    </div>
</template>

<script>
export default {
    
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=B612+Mono&display=swap');
</style> 