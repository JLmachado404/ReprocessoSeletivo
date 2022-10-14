<template>
  <head>
        <link href="https://cdn.jsdelivr.net/npm/remixicon@2.5.0/fonts/remixicon.css" rel="stylesheet"/>
  </head>
<body>
  <AppHeader/>
  <AppHome />
  <AppWho />
  <AppFundadores />
  <AppAcademia />
  <AppPricing />
  <AppContact />
  <AppFooter/>
</body>
</template>

<script>
import AppHeader from './components/template/AppHeader.vue'
import AppFooter from './components/template/AppFooter.vue'
import AppHome from './components/AppHome.vue'
import AppWho from './components/AppWho.vue'
import AppFundadores from './components/AppFundadores.vue'
import AppAcademia from './components/AppAcademia.vue'
import AppPricing from './components/AppPricing.vue'
import AppContact from './components/AppContact.vue'

export default {
  name: 'App',
  components: {
    AppHeader,
    AppFooter,
    AppHome,
    AppWho,
    AppFundadores,
    AppAcademia,
    AppPricing,
    AppContact,
  }
}
</script>

<style>

:root{
    --cor--primaria-vermelho: #E50914;
    --cor-hover-vermelho: #6A080D;
    --cor-branco-padrao: #f4f4f4;
    --cor-branco-hover: #B6ADAD;
    --bigger-font-size: 3.5rem;
    --biggest-font-size: 6rem;
    --title-color: hsl(180,4%,72%);
    --font-black: 900;
    --first-color-gray: rgb(94, 95, 91);
    --h3-font-size: 1.25rem;
    --h1-font-size: 2.25rem;
    --smal-font-size: 0.813rem;
}

body{
  background-color: #1f1f1f;
}



*{
    margin: 0;
    padding: 0;
    font-family: 'impact', arial, helvetica;
}

</style>
