<template>
    <div class="flex flex-wrap gap-4 p-4">
        <div v-for="(item, index) in 3" :key="'item-' + index"
            class="relative card w-1/4 h-60 bg-cyan-600 text-white p-4 rounded shadow">
            <img src="/sp.png" alt="Item Image" class="absolute top-0 right-0 w-12 h-12 m-2" />
            <p class="text-center text-black ">Item {{ index + 1 }}</p>
            <p class="justify-center mt-5">Create web servers with all necessary features and deploy them wherever
                you prefer.
            </p>
        </div>


        <div v-for="(image, index) in 3" :key="index"
            class="relative card w-1/4 h-40 bg-green-600 text-white p-4 rounded shadow">
            <p class="text-center text-blue-700 ">Product Image {{ index + 1 }}</p>
            <p class="flex justify-center mt-3">Create web servers with all necessary features and deploy them wherever
                you prefer.
            </p>
            <img src="/GR.png" alt="Product Image" class="absolute bottom-0 right-0 w-12 h-12 m-2" />
        </div>
    </div>
</template>