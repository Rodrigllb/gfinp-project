<template>
    <main>  

        <article>

            <section class="informaçoes-dashboard">
                    <h1>Dashboard</h1>

                    <div class="fundos-do-usuario">

                        <img src="../assets/icon-cifrao.png" alt="cifrão icone">

                        <div>
                            <output id="saldo-em-conta">R$ 0.00</output>
                            <small>Saldo em conta</small>
                        </div>

                    </div>

                    <div class="despesas-do-usuario">
                        <img src="../assets/icon-despesas.png" alt="cifrão negativo icone">

                        <div>
                            <output id="despesas-em-conta">R$ 0.00</output>
                            <small>Despesas totais</small>
                        </div>


                    </div>

                    <input type="button" value="Comprar" id="realizar-compras">
                    
            </section>

            <section class="dashboard-pagina-inicial">
                
                
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

    .informaçoes-dashboard {/*Estilização do container de informações do dashboard */
        display: grid;
        grid-template-columns: 1fr 1fr 1fr 1fr;
        align-items: center;
        justify-content: center;
        width: 1050px;
        height: auto;
        margin: 0 auto;
        padding: 0px 23px 0px 45px;	
    
    }

    .fundos-do-usuario { /*Estilização do container de fundos do usuario */
        display: grid;
        grid-template-columns: 45px 50px;
        align-items: center;
        justify-content: center;
        width: 100%;
        height: 100%;
    }

    .fundos-do-usuario div { /*Estilização dos elementos do container dos fundos do usuario.*/
        display: flex;
        flex-direction: column;
    }

    .fundos-do-usuario small { /*Estilização do texto pequeno */
        text-align: left;
        font-size: 8pt;
    }

    .despesas-do-usuario { /*Estilização do container referente aos campos das despesas do usuario. */
        display: grid;
        grid-template-columns: 45px 50px;
        align-items: center;
        justify-content: center;
        width: 100%;
        height: 100%;

    }

    .despesas-do-usuario div { /*Estilização dos elementos do container de despesas*/
        display: flex;
        flex-direction: column;
    }

    .despesas-do-usuario small { /*Estilização do texto pequeno */
        text-align: left;
        font-size: 8pt;
    }   

    #realizar-compras { /*Estilização do botão de compras.*/
        width: auto;
        height: 50px;
        background-color: #2ebe2e;
        color: #ffff;
        border: none;
        border-radius: 5px;
    }


    
    

</style>
