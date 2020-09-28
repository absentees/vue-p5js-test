<template>
    <div id="app">
      <Canvas></Canvas>
    </div>
</template>

<script>
import Canvas from './components/Canvas';

export default {
    name: "App",
    components: {
      Canvas
    },
    
    methods: {

    }
};
</script>

<style>
html, body {
  margin: 0;
  padding: 0;
}

#app {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
}
</style>
