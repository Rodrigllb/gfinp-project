<template>
  <header>
    <img src="../assets/logo-gfinp.png" alt="logo gfinp">
    <ul>
      <li><a href="#">Dashboard</a></li>
      <li><a href="#">Compras</a></li>
      <li><a href="#">Despesas</a></li>
      <li><a href="#">Relatórios</a></li>
    </ul>

    <div class="area-de-busca-e-login">
      <input type="button" value="Comprar" id="realizar-compras">
      <img src="../assets/icon-user-avatar.png" alt="icone de usuario" id="avatar-usuario">
    </div>
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
  grid-template-columns: 1fr 8fr 1fr auto;
  width: 100%;
  height: 35px;
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
  margin: 0 18px;
}

.area-de-busca-e-login {
  display: flex;
  justify-content: space-around;
  flex-direction: row;
  align-items: center;
  width: 300px
}

#realizar-compras { /*Estilização do botão de compras.*/
  width: 100px;
  height: 27px;
  background-color: #2ebe2e;
  color: #ffff;
  border: none;
  border-radius: 5px;
}

#avatar-usuario { /*Estilização do avatar do usuario */
  width: 35px;
  height: 35px;
  border-radius: 50%;
  margin-left: 10px;
}
</style>
