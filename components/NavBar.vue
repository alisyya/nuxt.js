<template>
    <div>
        <nav class="font-sans flex flex-col text-center content-center sm:flex-row sm:text-left sm:justify-between py-2 px-6 shadow sm:items-center w-full">
  <div class="mb-0 sm:mb-0">
    <nuxt-link to="/">
    <img src="~/assets/logo.png" >
    </nuxt-link>
  </div>
  <div>
    <nuxt-link class="text-lg no-underline text-grey-darkest hover:text-blue-dark ml-2" to="/Experience">Experience</nuxt-link>
    <nuxt-link class="text-lg no-underline text-grey-darkest hover:text-blue-dark ml-2" to="/about">About</nuxt-link>
    <nuxt-link class="text-lg no-underline text-grey-darkest hover:text-blue-dark ml-2" to="/quotes">Quotes</nuxt-link>
  </div>
</nav>
    </div>
</template>

<script>
export default {
    
}
</script>