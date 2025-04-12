<template>
    <div class="border bg-red-500 w-1/2 h-screen text-white text-2xl">
        {{ props.title }} <br>
        {{ props.likes }}
    </div>
</template>
<script setup>

const props = defineProps({
    title: String,
    likes: Number
})

</script>