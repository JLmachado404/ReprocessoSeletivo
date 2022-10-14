<template>
    <div class="footer">
      <head>
        <link href="https://cdn.jsdelivr.net/npm/remixicon@2.5.0/fonts/remixicon.css" rel="stylesheet"/>
      </head>
      <footer>
            <h1 class="copyright">&copy; Todos os direitos reservados</h1>
            <div class="sociais">
                <a  href="/" class="linkedin"><i class="ri-linkedin-box-fill"></i></a>
                <a href="/" class="twitter"><i class="ri-twitter-fill"></i></a>
                <a href="/" class="facebook"><i class="ri-facebook-circle-fill"></i></a>
                <a href="/" class="instagram"><i class="ri-instagram-fill"></i></a>
            </div>

        </footer>
    </div>
    
</template>


<script>

export default {
    components: {
    }
    
}
</script>


<style scoped>

footer{
  text-align: center;
  margin-top: 100px;
  font-family: 'roboto' sans-serif;
  background-color:#1f1f1f;
}

.copyright{
  color: #E50914;
  margin-bottom: 10px;
}

.sociais a{
  text-decoration: none;
  color: #E50914;
  height: 1000px;
  font-size: 3.25rem;
}

</style>