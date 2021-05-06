<template>
    <div class="bg-blue-500 font-semibold">
        <div class="mx-auto flex justify-between items-center py-4 px-4">
            <div class="flex">
                <LogoSmall />
                <nuxt-link class="text-white no-underline hover:text-grey-light" to="/">Report Daily Activity</nuxt-link>
            </div>
            <div class="flex gap-4">
                <nuxt-link class="text-white no-underline hover:text-grey-light" to="/">Home</nuxt-link>
                <nuxt-link class="text-white no-underline hover:text-grey-light" to="/about">About</nuxt-link>
                <nuxt-link class="text-white no-underline hover:text-grey-light" to="/dashboard">Dashboard</nuxt-link>
            </div>
        </div>
    </div>
</template>