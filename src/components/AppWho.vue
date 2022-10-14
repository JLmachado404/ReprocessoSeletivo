
<template>
    <div class="whoWeAre">
        <section class="quemSomos section" id="quemSomos">
            <h1 class="quemSomos">Quem Somos</h1>
            <div class="containerCard">
                <div class="card">
                    <h1>Missão</h1>
                    <div class="img">
                        <Icon icon="akar-icons:flag" width="200" height="200"/>
                    </div>
                    <div class="content">
                        <p>Lorem Ipsum is simply dummy text of the pri.</p>
                    </div>
                </div>
                <div class="card">
                    <h1>Visão</h1>
                    <div class="img"><Icon icon="akar-icons:eye" width="200" height="200" />
                    </div>
                    <div class="content">
                        <p>Lorem Ipsum is simply dummy text of the pri.</p>
                    </div>
                </div>
                <div class="card">
                    <h1>Valores</h1>
                    <div class="img">
                        <Icon icon="akar-icons:star" width="200" height="200"/>
                    </div>
                    <div class="content">
                        <p>Lorem Ipsum is simply dummy text of the pri.</p>
                    </div>
                </div>
            </div>
        </section>
    </div>
</template>


<script>
import { Icon } from '@iconify/vue';

export default {
  components:{ 
    Icon,
  }
    
    
}
</script>

<style scoped>

.quemSomos{
    text-align: center;
    color: #F4f4f4;
    margin-top: 220px;
    font-size: 50px;
}

section{
  background-color:#1f1f1f;
}
.containerCard{
    width: 1150px;
    padding: 20px;
    display: flex;
    align-items: center;
    justify-content: center;
    flex-wrap: wrap;
    margin-left: 330px;
    color: #E50914;
    
  }

  .containerCard .card{
    position: relative;
    padding: 10px;
    width: 300px;
    background-color: #1B1B1B;
    margin: 20px;
    border: 1px solid #E50914;
    border-radius: 20px;
    overflow: hidden;
    transition: 0.5s;
    text-align: center;
  }

  .containerCard .card .img{
    transition: 0.5s;
    margin-top: 10px;
  }

  .containerCard .card h1{
    font-size: 2rem;
  }

  .containerCard .card .content{
    padding: 20px;
    text-align: center;
  }

  .containerCard .card .content{
    transition: 0.5s;
  }

  .containerCard .card .content p{
    font-size: 2.5rem;
  }

  .containerCard .card:hover{
    background-color: #E50914;
    color: #1B1B1B;
    margin-top: 30px;
    box-shadow: 2px 20px 25px #6A080D;
  }

  .containerCard .card:hover img{
    filter: invert(1);
  }

</style>