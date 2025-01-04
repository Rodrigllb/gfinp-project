<template>
  <header>
    <img src="../assets/logo-gfinp.png" alt="logo gfinp">
    <ul>
      <li><a href="#">Dashboard</a></li>
      <li><a href="#">Compras</a></li>
      <li><a href="#">Despesas</a></li>
      <li><a href="#">Relatórios</a></li>
    </ul>

    <img src="../assets/icon-user-avatar.png" alt="icone de usuario" id="avatar-usuario">
  </header>
</template>

<script>
export default {
  name: 'appHeader',

}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
header { /*Estilização geral do cabeçalho*/
  display: grid;
  grid-template-columns: 1fr 10fr auto;
  width: 100%;
  height: 42px;
  align-items: center;

}

header a { /*Estilização de links*/
  text-decoration: none;
  color: #ffffff;
}

header ul { /*Estilização de listas */
  display: flex;
  justify-content: start;
  align-items: center;
  list-style: none;
}

header li { /*Alinhamento das linhas da lista*/
  margin: 0 30px;
}

</style>
