<template>
    <div>
        <p>Product detail for {{ id }}</p>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Numquam, aut?</p>
    </div>
</template>
<script setup>
    const { id } = useRoute().params
    definePageMeta({
        layout: 'products'
    })
</script>
<style scoped>
    
</style>