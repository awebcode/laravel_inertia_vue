<template>
    <div>
        <h1 class="text-8xl text-gray-800">Another Test {{ Data }}</h1>
    </div>
</template>

<script setup>
defineProps({
    Data:String
})
</script>

<style lang="css" scoped>
 .text-8xl {
     font-size: 10rem;
     text-wrap: nowrap;
 }
</style>