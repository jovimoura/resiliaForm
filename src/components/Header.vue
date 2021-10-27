<template>
    <div id="cabecalho">
        <div id="box_titulo">
            <h1 id="titulo">RESILIA</h1>
        </div>
        <nav>
            <ul id="navegacao">
                <li>
                    <a href="https://www.linkedin.com/school/resilia-educacao/" target="_blank" >
                        <img src="https://img.icons8.com/ios-glyphs/90/000000/linkedin.png" alt="LinkedIn">
                    </a>
                </li>
                <li>
                    <a href="https://resilia.medium.com/" target="_blank">
                        <img src="https://img.icons8.com/ios-glyphs/90/000000/medium-monogram.png" alt="Medium">
                    </a>
                </li>
                <li>
                    <a href="https://www.facebook.com/resilia.br" target="_blank">
                        <img src="https://img.icons8.com/ios-glyphs/90/000000/facebook.png" alt="Facebook">
                    </a>
                </li>
                <li>
                    <a href="https://www.instagram.com/resilia.br/" target="_blank">
                        <img src="https://img.icons8.com/material-outlined/96/000000/instagram-new--v1.png" alt="Instagram">
                    </a>
                </li>
            </ul>
        </nav>
    </div>
</template>

<script>
export default {
    name: 'Header',

}
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Archivo:wght@100;200&family=Fira+Sans:wght@500&display=swap');

    #cabecalho {
        margin: 1rem;
    }
    
    h1 {
        font-family: 'Fira Sans', sans-serif;
        color: #ffd000;
    }

    #cabecalho {
        display: flex;
        align-items: center;
        justify-content: space-between;
    }

    #navegacao {
        display: flex;
        align-items: center;
        list-style: none;
    }

    img {
        width:2rem;
        height: 2rem;
        transition: ease-in-out .4s all;
        margin:.1rem
    }

    img:hover {
        transform: scale(1.2);
    }
</style>