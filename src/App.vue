<template>
  <div id="app">
    <img alt="Vue logo" src="https://vuejs.org/images/logo.png" />
    <ColorPicker />
  </div>
</template>

<script>
import ColorPicker from './components/ColorPicker.vue';
//https://www.npmjs.com/package/qrcode
export default {
  name: 'App',
  components: {
    ColorPicker,
  },
};
</script>

<style>
#app1 {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
img {
  width: 5em;
}
</style>
