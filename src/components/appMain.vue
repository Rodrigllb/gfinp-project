<template>
    <main>  

        <article>

            <section class="informaçoes-boasvindas-e-direcionamento">
                <section>
                    <h1>Bem vindo, Usuário!</h1>
                    <h2>Como podemos te ajudar hoje?</h2>
                    <small>Ao lado podemos te ajudar a começar com umas dicas iniciais!</small>
                </section>
                <section class="card-dashboard">
                    <h3>Gerencie tudo!</h3>
                    <p>Ao clicar no link abaixo você pode ser direcionando ao seu dashboard pessoal e gerir melhor o que você gastou no mês! O que acha de gerenciar melhor teus gastos e receitas mensais?</p>
                    <a href="#">Ir para o dashboard.</a>
                </section>

                <section class="card-compras">
                    <h3>Comprou hoje?</h3>
                    <p>Aqui você pode ser direcionado para a página de compras. Lá você preenche corretamente as paradas compradas e todos esses dados preenchidos serão enviados para seu levantamento mensal. Corre lá!</p>
                    <a href="#">Ir para as compras.</a>
                </section>

                <section class="card-gerar-relatorio">
                    <h3>Relatórios</h3>
                    <p>Quer saber como você está indo no mês? Clique no link abaixo e veja como você está indo no mês. Lá você pode ver gráficos, tabelas e muito mais!</p>
                    <a href="#">Ir para os relatórios.</a>
                </section>
                    
            </section>

            <section class="dashboard-pagina-inicial">
                <section class="grafico-dashboard">

                </section>
                
            </section>
            
        </article>

    </main>
</template>

<script>

    export default {
        name: 'appMain',

    }
</script>

<style scoped>
    main { /*Estilização global do corpo do site*/
        width: 100%;
        height: 100%;
    }

    main article { /*Estilização do article do site */
        display: flex;
        flex-direction: column;
        width: 100%;
        height: 100%;
        margin-top: 50px;

    }

    main h1 { /*Estilização do titulo para tamanho de fonte 24 */
        font-size: 22pt;
    }

    .informaçoes-boasvindas-e-direcionamento {/*Estilização geral das informações, boas vindas e guia inicial para o usuário*/
        display: grid;
        grid-template-columns: 1fr 1fr 1fr 1fr;
        align-items: center;
        justify-content: center;
        width: 1050px;
        height: auto;
        margin: 0 auto;
        padding: 0px 23px 0px 45px;	
        
        border: none;
        border-radius: 23px;
    }

    .informaçoes-boasvindas-e-direcionamento h1 { /*Estilização do titulo h1 do container de boas vindas e guia inicial.*/
        font-weight: 900;
        font-size: 34pt;
        margin: 0;
        color: #f0b90b;
        margin: 0px;
    }

    .informaçoes-boasvindas-e-direcionamento a { /*Estilização geral dos links pertencentes a esse container. */
        color: #f0b90b;
    }

    /*Abaixo inicia-se a estilização da barra de guias iniciais para o usuário, onde as informações apresentadas tem como intuito
    de guiar, direcionar e sugerir para aonde o usuário possivelmente irá fazer na plataforma.*/

    .card-dashboard, .card-compras, .card-gerar-relatorio {
        height: 390px;
        background-color: #9e9e9e17;
        padding: 20px;
        margin: 0px 20px 0px 20px ;
    }

    .card-gerenciar-compras p {
        text-align: left;
    }




   
    
    

</style>
