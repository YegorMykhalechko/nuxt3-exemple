<template>
    <div>
        <p>Product details for {{ id }}</p>
        <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Rerum numquam dolorum autem aliquid similique, ducimus ipsa officia? Est eos magnam repellat eum, ad vero, ab numquam eaque, enim delectus ratione!</p>
    </div>
</template>

<script setup>
    const { id } = useRoute().params

    definePageMeta({
        layout: "products"
    })
</script>

<style scoped>

</style>