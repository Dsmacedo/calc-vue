<script>
import Calculator from './components/Calculator.vue'

export default {
    name: 'app',
    components: {
        Calculator
    }
}
</script>

<template>
    <div id="app">
        <Calculator />
    </div>
</template>

<style>
#app {
    font-family: Arial, Helvetica, sans-serif;
    text-align: center;
}
</style>
