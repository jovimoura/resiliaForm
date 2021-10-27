<template>
    <main>
        <div id="box_titulo">
            <h1 id="titulo">
                Prepare-se para a
                experiência que vai
                <a id="sublinhado">mudar a sua vida!</a>
            </h1>
        </div>
        <div id="box_texto">
            <p id="texto">
                Quer começar de vez sua carreira na área Tech?
                
            </p>
            <p id="texto">
                Em 6 meses, você vai aprender TUDO que precisa para começar
                a trabalhar como <b>Dev Jr com a metodologia Resilia!</b>
            </p>
        </div>
        <svg id="figura" class="svg-home-line-hero" width="1100" height="167" viewBox="0 0 894 167" fill="none" xmlns="http://www.w3.org/2000/svg">
            <path d="M-3.5 73.3974C51.6359 80.7716 193 88.9839 219.875 51.2746C262.199 -8.11067 146 -39.3789 146 119C146 242.5 351.58 70.5774 468.736 51.2746C610 28 699.403 119.704 665 156C631.127 191.738 582.173 108.09 650.135 39.7104C704.505 -14.9932 834.366 49.7662 892.5 88.9839" stroke="#FFD000" stroke-width="4"></path>
        </svg>
    </main>
    
</template>

<script>
export default {
    name: 'Texto'
}
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Archivo:wght@100;200&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Archivo:wght@200&family=Roboto:wght@300&display=swap');

    #sublinhado {
        text-decoration: underline #ffd000;
    }
    main {
        display:flex;
        flex-direction: column;
        width: 45%;
        
    }

    h1 {
        font-family: 'Archivo', sans-serif;
        font-size: 2.7rem;
        font-weight: bolder;
        margin:1.5rem 0
    }

    p {
        color:#707070;
        font-family: 'Archivo', sans-serif;
        font-size: 1.1rem;
        margin:0
    }

    b {
        color:#0b0b0b
    }
    
    

    @media(max-width:974px){

        #figura {
            display: none;
        }

        main {
            width: 95%;
        }

        h1,p{
            text-align: center;
        }
    }
</style>