<template>
    <div id="app">
        <menu-test></menu-test>
    </div>
</template>

<script>
    import HelloWorld from './components/HelloWorld'
    import MenuTest from "./components/MenuTest.vue";

    export default {
        name: 'App',
        components: {
            MenuTest,
            HelloWorld
        }
    }
</script>

<style>
    #app {
        font-family: 'Avenir', Helvetica, Arial, sans-serif;
        -webkit-font-smoothing: antialiased;
        -moz-osx-font-smoothing: grayscale;
        text-align: center;
        color: #2c3e50;
    }
</style>
