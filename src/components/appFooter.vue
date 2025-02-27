<template>
    <footer>
        <h3>GFINP</h3>
        <section class="seçaolinks">
            <div class="links-rapidos">
                <a href="#">Termos de uso</a>
                <a href="#">Termos de privacidade</a>
                <a href="#">Política de cookies</a>

            </div>
        </section>
        <section class="icons-footer">
            <a href="#"><img src="../assets/icon-gith.png" alt="github icon"></a>
            <a href="#"><img src="../assets/icon-isnt.png" alt="instagram icon"></a>
            <a href="#"><img src="../assets/icon-wpp.png" alt="whatsapp icon"></a>
        </section>
        <section class="seçao-direitos-autorais">
            <small>© 2025 GFINP - Todos os direitos reservados</small>
        </section>
       
    </footer>

</template>

<script>
    export default {
        name: 'appFooter',
    }
</script>

<style scoped>
    footer { /*Rodapé geral do site */
        display: flex;
        align-items: center;
        justify-content: center;
        text-align: center;
        flex-direction: column;
        width: auto;
        height: 103px;
        border-top: 1px solid #ffffff46;
        padding: 12px;
    }

    .seçaolinks { /*Seção onde os links serão agrupados um ao lado do outro */
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
        width: 100%;
        height: 100%;
        color: #ffff;
    }

    .links-rapidos { /*Termos referente ao uso dos dados do usuário. */
        display: flex;
        flex-direction: row;
        text-align: left;
    }

    .links-rapidos a { /*Seção para posicionamento dos links rapidos */
        font-size: 9pt;
        margin: 0 10px;
        color: #ffff;
        text-decoration: none;
    }

    .icons-footer { /*Icones das redes sociais da empresa */
        display: flex;
        align-items: center;
        justify-content: center;
        width: 100%;
        height: 100%;
        margin: 10px 0;
    }
    .icons-footer a { /*Seção referente aos links e suas estilizações. */
        margin: 0 10px;
    }

    .seçao-direitos-autorais {
        display: flex;
        align-items: center;
        justify-content: center;
        width: 100%;
        height: 100%;
        background-color: #0e0e0e;
    }

</style>