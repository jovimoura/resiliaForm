<template>
    <footer>Orgulhosamente feito por <a href="https://portfolio-jovimoura.vercel.app/" target="_blank"> João Victor Moura</a></footer>
</template>

<script>
export default {
    name:'Footer'
}
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Archivo:wght@100;200&display=swap');

    footer {
        display: flex;
        align-items: center;
        justify-content: center;
        background-color: #0b0b0b;
        color: #fff;
        height: 3rem;
        width: 100%;
        font-family: 'Archivo', sans-serif;
        margin-top: 2rem
    }

    a {
        text-decoration: none;
        color: #fff;
        transition: ease-in-out .2s all;
        margin:.4rem
    }

    a:hover {
        color:#ffd000;
        cursor: pointer;
    }

    a:active {
        color: #33a1fd;
    }
</style>
