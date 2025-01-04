<template>
  <appHeader></appHeader>
  <appMain></appMain>
</template>

<script>
import appHeader from './components/appHeader.vue';
import appMain from './components/appMain.vue';

export default {
  name: 'App',
  components: {
    appHeader,
    appMain,
  }
} 
</script>

<style>
body {
  background-color: #1a1a1a;
}
#app { /*Estilização global*/
  font-family: "Roboto Condensed", Avenir, Helvetica, Arial, sans-serif;
  color: #ffffff;
  margin: 12px;
}
</style>
