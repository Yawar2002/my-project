<template>
    <div class="border bg-yellow-700 w-1/5 h-20 p-3 text-white text-2xl">
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
