<template>
    <div>
    <nav class="font-sans flex flex-col text-center content-center sm:flex-row sm:text-left sm:justify-between py-2 px-6 bg-white shadow sm:items-baseline w-full">
        <div class="mb-2 sm:mb-0 flex flex-row">
            <div class="h-10 w-10 self-center mr-2">
                <img class="h-10 w-10 self-center" src="~/assets/logo.png" />
            </div>
        </div>
        <div class="mb-2 sm:mb-0 flex flex-row">
            <nuxt-link to="/"></nuxt-link>
            <nuxt-link to="/Experience">Experience</nuxt-link>
            <nuxt-link to="/about">About</nuxt-link>
            <nuxt-link to="/quotes">Quotes</nuxt-link>
        </div> 
        <Nuxt/>
    </nav>
    </div>
</template>

<script>
export default {
    css: '~/assets/styles/navbar.css'
}
</script>