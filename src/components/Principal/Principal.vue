<template>
    <main>
        <Texto />
        <form action="" >
            <div id="boxTextual">
                <h2 id="titulo">
                Formação WebDev Resilia
                </h2>
                <p id="texto">
                    Aprenda programação de verdade, de uma forma diferente e do zero! Últimas turmas do ano!
                </p>
            </div>
            
            <div id="inputs">
                <div id="inputs_nome">
                    <label for="nome">Nome Completo</label>
                    <input required placeholder="Nome" type="text" id="nome">
                </div>
                <div id="inputs_email">
                    <label for="email">E-mail(você usará o mesmo durante todo o processo)</label>
                    <input required placeholder="E-mail" type="email" name="email" id="email" >
                </div>
                <div id="inputs_celular">
                    <label for="celular">Celular/WhatsApp</label>
                    <input required placeholder="Celular" type="number" id="celular">
                </div>
                <div id="inputs_comoSoube">
                    <label for="comoSoube">Como Você conheceu a Resilia?</label>
                    <select name="comoSoube" id="comoSoube">
                        <option value="vazio">---</option>
                        <option value="fbIg">Anuncio no Facebook/Instagram</option>
                        <option value="google">Anuncio no Google ou outros</option>
                        <option value="empresa">Divulgação de alguma empresa parceira</option>
                        <option value="imprensa">Imprensa(jornais,TV,revistas)</option>
                        <option value="amigo">Indicação de um amigo</option>
                        <option value="panfleto">Panfleto</option>
                        <option value="pesquisa">Pesquisa no Google</option>
                    </select>
                </div>
                <div id="inputs_privacidade">
                    <label for="privacidade">
                    Você concorda com a nossa <a href="https://www.inscricoes.resilia.dev/politica-de-privacidade/">Política de privacidade</a>?
                    </label>
                    <select name="privacidade" id="privacidade">
                        <option value="sim">Sim</option>
                        <option value="Não">Não</option>
                    </select>
                </div>
                
            </div>
            <div id="inscricao-btn">
                <button>Quero Me Inscrever!</button>
            </div>
        </form>
    </main>
    

</template>

<script>
import Texto from './Texto.vue'
export default {
    name:'Principal',
    components: {
        Texto
    }
}
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Archivo&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Archivo:wght@200&family=Roboto:wght@300&display=swap');


    main {
        display: flex;
        align-items: center;
        justify-content: space-between;
        padding: 2rem;

    }

    h2 {
        font-family: 'Archivo', sans-serif;
        font-size: 2.7rem;
        font-weight: bolder;
        margin:1.5rem 0
    }

    form {
        display:flex;
        align-items: center;
        flex-direction: column;
        justify-content: center;
        width:35%;
        height: 100%;
        background-color: #fff;
        border: 2px solid transparent;
        border-radius: 35px;
        box-shadow: 0px 0px 50px -4px rgb(0 0 0 / 60%);
        padding:3rem 1.8rem ;
        text-align: left;
        margin-bottom: 2rem
    }

    #inputs {
        width:100%
    }

    #inputs div {
        display: flex;
        justify-content: center;
        flex-direction: column;
        margin: 1rem;
        
    }

    label {
        margin-bottom: .2rem;
        color:#707070
    }

    p {
        color:#707070
    }

    input,select {
        background-color: #D6D6D64D;
        color:#707070;
        padding: .5rem .8rem;
        border: 2px solid transparent;
        border-radius: 10px ;
        font-size: 15px;
        
    }

    input {
        transition: ease-in-out .4s all;
        -webkit-transition: 0.5s;
        transition: 0.5s;
        outline: none;
    }

    input:focus {
        border:2px solid #fad11d;
        background-color: #f5e396;
    }

    select {
        color:#0b0b0b
    }

    p,input,select,label {
        font-family: 'Archivo', sans-serif;
        font-size: 1.1rem;
    }

    button {
        background-color: #FFD000;
        border:2px solid transparent;
        border-radius:12px;
        padding: .8rem 4.5rem;
        font-size: 1.1rem;
        font-family: 'Archivo', sans-serif;
        transition: ease-in-out .4s all;
    }

    button:hover {
        cursor:pointer;
        border-color: #FFD000;
        background-color: #fff;
        color:#FFD000;
        transform: scale(1.1)
    }

    
    
    @media(max-width:768px){

        main {
            flex-direction: column;
        }
    }

    @media(max-width:974px){

        main {
            flex-direction: column;
        }

        form {
            width: 90%;
        }
    }
</style>