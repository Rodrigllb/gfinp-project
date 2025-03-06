<template>
  <UserLogin></UserLogin>
</template>

<script>
import UserLogin from './pages/userLogin.vue';

export default {
  name: 'App',
  components: {
      UserLogin,

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
