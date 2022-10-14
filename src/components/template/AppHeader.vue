<template>
    <div class="header">
        <header class="header">
    <nav class="header-nav">
    <a class="logo" href="#home">Life Weight</a>
    <div class="mobile-menu">
        <div class="line1"></div>
        <div class="line2"></div>
        <div class="line3"></div>
    </div>
    <ul class="nav-list">
        <li><a class="navQuemSomos" id="logo" href="#quemSomos">Quem somos</a></li>
        <li><a  class="navDepoimento" id="logo" href="#depoimentos">Depoimentos</a></li>
        <li><a class="navFundadores" id="logo" href="#fundadores">Fundadores</a></li>
        <li><a  class="navPlanos" id="logo" href="#pricing">Nossos planos</a></li>
        <li><a  class = "navContato" id="logo" href="#contato">Contato</a></li>
        <button type="button" class="sistema">sistema</button>
    </ul>
</nav>
    </header>
    </div>
    
</template>


<script>
export default {
    
}
</script>

<style scoped>

*{
    margin: 0;
    padding: 0;
    font-family: 'impact', arial, helvetica;
}

body{
    background-color: #1f1f1f;
    position: relative;
}

#logo{
    color: #F4f4f4;
    text-decoration: none;
    transition: 0.3s;
}

#logo:hover{
    opacity: 0.7;
}


.logo{
    font-size: 24px;
    text-transform: uppercase;
    letter-spacing: 4px;
    color: #E50914;
    text-decoration: none;
}

.header-nav{
    display: flex;
    justify-content: space-around;
    align-items: center;
    height: 8vh;
}

.header{
    box-shadow: 0 0 0 0.20rem #E50914;
    background-color: #1f1f1f;
    top: 0;
    width: 100%;
    position: fixed;
    z-index: 2;
    right: 0px;
}

.nav-list{
    list-style: none;
    display: flex;
    position: relative;
}

.nav-list li{
    letter-spacing: 3px;
    margin-left: 32px;
    margin-top: 10px;
    position: relative;
}

.nav-list .sistema{
    border: none;
    width: 100px;
    height: 40px;
    text-decoration: none;
    font-size: 20px;
    cursor: pointer;
    transition: background .3s;
    border-radius: 15px;
    margin-left: 32px;
    background-color: #E50914;
    outline: none;
    color: #F4f4f4;
}

.sistema:hover{
    background-color: #6A080D;
    color: #B6ADAD;
}



</style>