<template>
    <main>
        <div>
        <div class="cabeçalho-login">
            <h1>Login</h1>
            <small>Preencha com suas credenciais.</small>
        </div>
        
        <form>
            <label for="email">Email</label>
            <input type="email" id="email" name="email" required>
            <label for="password">Senha</label>
            <input type="password" id="password" name="password" required>
            <button type="submit">Iniciar Sessão</button>
        </form>
        <div class="links-rapidos">
            <small>Não tem conta? <a href="#" target="_blank" rel="noopener noreferrer">Criar sua conta aqui</a></small>
            <small>Se esqueceu a senha, clique <a href="#" target="_blank" rel="noopener noreferrer">aqui</a></small>
        </div>   
    </div>
    </main>
    
</template>


<script>    
export default {
    name: 'UserLogin',
    components: {
        
    }
}
</script>

<style scoped>

    main {
        display: flex;
        justify-content: center;
        align-items: center;
        height: 89vh;
        background-color: #1a1a1a;
    }
    div { /*Centralização dos itens internos da div para estilização da página de login.*/
        display: flex;
        flex-direction: column;
        margin: 0 auto;
        width: 500px;
        background-color: #222222;
        border-radius: 25px;
        color: #b8b8b8;
    }
    
    .cabeçalho-login { /*Estilização do cabeçalho da página de login.*/
        text-align: center;
        margin: 12px 0;
    }

    .cabeçalho-login small {
        color: #b8b8b8;
    }

    h1 { /*Estilização do titulo da página de login. */
        margin: 0;
        color: #e0b700;
    }

    form { /*Estilização do formulário */
        display: flex;
        flex-direction: column; 
        justify-content: left;
        margin: 12px 0;
        padding: 32px;
    }

    input, button { /*Estilização das entradas do usuário  */
        padding: 16px;
        margin: 6px 0;
        border-radius: 45px;
        border: none;
    }

    button { /*Estilização do botão de login */
        background-color: #e0b700;
        color: #1a1a1a;
        font-weight: 600;
    }

    .links-rapidos { /*Estilização dos links rapidos.*/
        display: flex;
        justify-content: space-around;
        text-align: center;
        margin: 12px 0;
    }
    .links-rapidos a { /*Estilização dos links rapidos.*/
        color: #e0b700;
        text-decoration: none;  
    }
</style>