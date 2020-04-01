<template>
    <div class="full-width center-content">
        <h1>O Cafe</h1>
        <p>Custom Drinks at Your Fingertips</p>
        <menu-component coffeeType="Espresso" />
    </div>
</template>

<script>
import Menu from './components/Menu.vue'
export default {
    components: {
        Menu
    }
}
</script>

<style lang="stylus" scoped>
h1
  color red
</style>