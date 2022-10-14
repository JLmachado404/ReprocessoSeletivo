<template>
    <div class="pricing">
        <section class="pricing section" id="pricing">
            <div class="container">
                <div class="section__data">
                    <h2 class="section__subtitle">Nossos planos</h2>
                </div>
                <div class="pricing__container grid">
                    <article class="pricing__card">
                        <header class="pricing__header">
                            <h1 class="pricing__title">GRANDE</h1>
                            <h2 class="pricing__number">R$90</h2>
                            
                        </header>
                        <ul class="pricing__list">
                            <li class="pricing__item">
                                <i class="ri-checkbox-circle-line"></i> Musculação
                            </li>
                            <li class="pricing__item pricing__item-opacity">
                                <i class="ri-checkbox-circle-line"></i> Personal Trainer
                            </li>
                            <li class="pricing__item pricing__item-opacity">
                                <i class="ri-checkbox-circle-line"></i> Sheikeira Whey
                            </li>
                            <li class="pricing__item pricing__item-opacity">
                                <i class="ri-checkbox-circle-line"></i> Creatina 150g
                            </li>
                            <li class="pricing__item pricing__item-opacity">
                                <i class="ri-checkbox-circle-line"></i> Treino com os fundadores
                            </li>
                        </ul>
                        <a class="button button__flex pricing__button">Adquira AGORA! <i class="ri-arrow-right-line"></i></a>
                    </article>
                    <article class="pricing__card pricing__card-active">
                        <header class="pricing__header">
                        <h1 class="pricing__title">GIGA</h1>
                        <h2 class="pricing__number">R$100</h2>
                        </header>
                        <ul class="pricing__list">
                            <li class="pricing__item">
                                <i class="ri-checkbox-circle-line"></i> Musculação
                            </li>
                            <li class="pricing__item">
                                <i class="ri-checkbox-circle-line"></i> Personal Trainer
                            </li>
                            <li class="pricing__item">
                                <i class="ri-checkbox-circle-line"></i> Sheikeira Whey
                            </li>
                            <li class="pricing__item pricing__item-opacity">
                                <i class="ri-checkbox-circle-line"></i> Creatina 150g
                            </li>
                            <li class="pricing__item pricing__item-opacity">
                                <i class="ri-checkbox-circle-line"></i> Treino com os fundadores
                            </li>
                        </ul>
                        <a class="button button__flex pricing__button">Adquira AGORA! <i class="ri-arrow-right-line"></i></a>
                    </article>
                    <article class="pricing__card">
                        <header class="pricing__header">
                        <h1 class="pricing__title">BODYBUILDER</h1>
                        <h2 class="pricing__number">R$110</h2>
                        </header>
                        <ul class="pricing__list">
                            <li class="pricing__item">
                                <i class="ri-checkbox-circle-line"></i> Musculação
                            </li>
                            <li class="pricing__item">
                                <i class="ri-checkbox-circle-line"></i> Personal Trainer
                            </li>
                            <li class="pricing__item">
                                <i class="ri-checkbox-circle-line"></i> Sheikeira Whey
                            </li>
                            <li class="pricing__item">
                                <i class="ri-checkbox-circle-line"></i> Creatina 150g
                            </li>
                            <li class="pricing__item">
                                <i class="ri-checkbox-circle-line"></i> Treino com os fundadores
                            </li>
                        </ul>
                        <a class="button button__flex pricing__button">Adquira AGORA! <i class="ri-arrow-right-line"></i></a>
                    </article>
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
.pricing__card,.pricing__shape,.pricing__list{
  display: inline-block;
}

.pricing__container{ 
  padding-top: 0.5rem;
  padding: 50px;
  width: 10000px;
}


.pricing__card{
  row-gap: 1rem;
  background-color: #272727;
  padding: 2rem 3.5rem;
  border-radius: 10%;
  width: 200px;
  padding: 75px;
  height: 300px;
  margin-left: 175px;
}

.pricing__title{
  font-size: var(--h3-font-size);
  color: #f4f4f4;
  margin-bottom: 1rem;
  align-items: center;
}

.pricing__number{
  font-size: var(--h1-font-size);
  color: #f4f4f4;
  align-items: center;
}

.pricing__list{
  row-gap: 2rem;
  margin-bottom: 20px;
  margin-top: 20px;
  align-items: center;
}

.pricing__item{
  display: flex;
  column-gap: .5rem;
  align-items: center;
  text-align: center;
  font-size: var(--smal-font-size);
  color:#E50914
}

.pricing__item i{
  font-size: 1.25rem;
  color:#E50914
}

.pricing__item-opacity{
  opacity: .3;
}

.pricing__card-active{
  background-color: #131011;


}

.section__subtitle{
  text-align: center;
  color: #F4f4f4;
  margin-top: 170px;
  font-size: 50px;
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