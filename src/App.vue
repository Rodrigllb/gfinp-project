<template>
  <appHeader></appHeader>
  <appMain></appMain>
  <appFooter></appFooter>
</template>

<script>
import appHeader from './components/appHeader.vue';
import appMain from './components/appMain.vue';
import appFooter from './components/appFooter.vue';

export default {
  name: 'App',
  components: {
    appHeader,
    appMain,
    appFooter,
  }
} 
</script>

<style>
body {
  background-color: #1a1a1a;
}
#app { /*Estilização global*/
  font-family: "Poppins", Avenir, Helvetica, Arial, sans-serif;
  font-weight: 300;
  color: #ffffff;
  margin: 12px;
}
</style>
