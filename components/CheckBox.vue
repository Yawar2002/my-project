<template>
    <div class="flex flex-wrap m-5">
        <div v-for="box in 2"  class="border bg-yellow-700 w-1/5 h-20 p-3 text-white text-2xl rounded-3xl">
            {{ props.title }} <br>
            {{ props.likes }}
        </div>
    </div>
</template>
<script setup>

const props = defineProps({
    title: String,
    likes: Number
})

</script>
