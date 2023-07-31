<script setup>
const props = defineProps({
    cocktail:{
        type: Object,
        required: true
    }
})
</script>

<template>
    <div class="root">
        <div class="pic"></div>
        <div class="name">{{ cocktail.strDrink }}</div>
    </div>
</template>

<style lang="sass" scoped>
@import '../assets/styles/main'
</style>