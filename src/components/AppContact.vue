<template>
    <div class="contact">
        <section class="contato" id="contato">
            <div class="contato-quadrado">
                <h1 class="duvida">Alguma dúvida?</h1>
                <h2 class="contatenos">Fale Conosco!</h2>
                <a class="button">Contato</a>
            </div>
        </section>

    </div>
    
</template>


<script>
export default {
    
}
</script>


<style scoped>
.contato-quadrado{
  text-align: center;
  font-size: 30px;
  margin-top: 30px;
  background-color: #272727;
  align-items: center;
  padding: 20px;
}

.duvida{
  color: #F4f4f4;
  margin: auto;;
}

.contatenos{
  color: #E50914;
  margin-top: 10px;
  margin-bottom: 30px;
}

.button{
    display: inline-block;
    background-color: #E50914;
    padding: 18px 32px;
    border: none;
    color: var(--cor-branco-padrao);
    cursor: pointer;
    transition: background .3s;
    text-decoration: none;
    border-radius: 20px;
}

.button:hover{
    background-color: var(--cor-hover-vermelho);
}

.button i{
    font-size: 1.25rem;
    transition: transform .3s;
}

.button__flex{
    display: inline-flex;
    align-items: center;
    justify-content: center;
    column-gap: .5rem;
}

.button__flex:hover i{
    transform: translateX(.25rem);
}

</style>