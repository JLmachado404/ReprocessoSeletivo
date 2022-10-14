<template>
    <div class="home">
        <section class="home section" id="home">
            <div class="home__container container grid">
                <div class="home__data">
                    <h2 class="home__subtitle">AQUI É</h2>
                    <h1 class="home__title">CONSTRUIDO FIBRA</h1>
                    <p class="home__description">
                        Proporcionamos um atendimento de alta qualidade, oferecendo saúde, bem-estar e motivação em um ambiente descontraído, agradável, familiar onde as pessoas criam amizades e praticam atividade fisica (E FICAM GIGANTES!).
                    </p>
                    <a href="#" class="button button__flex">Comece AGORA <i class="ri-arrow-right-line"></i></a>
                </div>
                <div class="home__images">
                    <img src="../assets/ronnie.png" class="home__img">

                    <div class="home__triangle home__triangle-1"></div>
                    <div class="home__triangle home__triangle-2"></div>
                    <div class="home__triangle home__triangle-3"></div>

                </div>
            </div>
        </section>
    </div>



</template>


<script>
export default {
    
}
</script>


<style scoped>



.home{
    position: relative;
    padding-bottom: 0;
    margin-left: auto;
    margin-right: auto;
    background-color:#1f1f1f;
}

.home__container{
    grid-template-columns: repeat(2,1fr);
    padding-top: 4rem;
    row-gap: 3rem;
    display: flex;
}

.home__data{
    text-align: center;
}

.home__subtitle{
    margin-top: 30px;
    font-size: var(--bigger-font-size);
    -webkit-text-stroke: 1px var(--title-color);
    color: transparent;
}

.home__title{
    font-size: var(--biggest-font-size);
    font-weight: 1000;
    margin: .75rem 0 1.25rem;
    color:#F4f4f4;
}

.home__subtitle,.home__title{
    letter-spacing: 1.5px;
}

.home__description{
    margin-bottom: 3rem;
    color:#F4f4f4;
}

.home__triangle{
    height: 925px;
    position: absolute;
    right: 0;
    bottom: 0;
    clip-path: polygon(100% 0,0 100%,100% 100%);
}

.home__triangle-1{
    width: 645px;
    background-color: #E50914;
}

.home__triangle-2{
    width: 845px;
    background-color: #E50914;
}

.home__triangle-3{
    width: 1045px;
    background-color: #E50914;
}

.home__img{
    display: block;
    position: relative;
    z-index: 1;
    width: 550px;
    margin: 0 auto;
    transform: translateX(-6rem);
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