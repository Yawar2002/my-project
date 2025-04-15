<template>
    <div>
        <header class="shadow-sm m-4 bg-white">
            <nav class="container mx-auto p-4 flex justify-between text-red-600">
                <nuxt-link to="/" class="font-bold">NuxtDot</nuxt-link>
                <ul class="flex gap-4">
                    <li>
                        <nuxt-link to="/product" class=" hover:text-blue-500">product</nuxt-link>
                    </li>
                    <li>
                        <nuxt-link to="/about" class=" hover:text-blue-500">About</nuxt-link>
                    </li>
                    <li>
                        <nuxt-link to="/Home" class=" hover:text-blue-500">Home</nuxt-link>
                    </li>
                </ul>
            </nav>

        </header>

    </div>
</template>