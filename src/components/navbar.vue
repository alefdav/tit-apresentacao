<template>
  <nav>
      <div class="container">
          <img src="http://titcs.com.br/wp-content/uploads/2018/10/cropped-logo_TITcs.png" class="logo" alt="">

          <nav>
              <ul>
                  <li>Nossa empresa</li>
                  <li>Inovação</li>
                  <li>Serviços de TI</li>
                  <li>Soluções</li>
                  <li>Notícias</li>
                  <button class="btnVagas">Vagas abertas</button>
              </ul>
          </nav>
      </div>
      
        <div class="navMobile">
            <img src="http://titcs.com.br/wp-content/uploads/2018/10/cropped-logo_TITcs.png" class="logo" alt="">
            <i class="fas fa-chevron-down"></i>
                <nav>
                    <ul>
                        <li>Nossa empresa</li>
                        <li>Inovação</li>
                        <li>Serviços de TI</li>
                        <li>Soluções</li>
                        <li>Notícias</li>
                        <button class="btnVagas">Vagas abertas</button>
                    </ul>
                </nav>
        </div>

      <div class="divisor">
          
      </div>
  </nav>

  
</template>

<script>
export default {
  name: 'navbar',
  props: {
    msg: String
  }
}


</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

    .navMobile{
        display: none;
    }
    .container, .container nav ul{
        display: flex;
        flex-direction: row;
        color: #a30401;
        justify-content: center;
        align-items: center
    }
    .container img{
        margin-right: 3vw;
    }

    nav ul li{
        list-style: none;
        padding: 10px;
        cursor: pointer;
    }

    .btnVagas{
        border-radius: 10px;
        border: none;
        background-color: #a30401;
        color: white;
        padding: 8px;
        cursor: pointer;
    }

    .divisor{
        border-bottom: 4px solid #a30401;
        padding-bottom: 50px;
        text-align: center;
        margin-bottom: 50px;
    }

    @media(max-width: 800px){
        .container{
            display: none;
        }

        .navMobile{
            display: flex;
            flex-direction: column;
            align-items: center;
        }

        .navMobile i{
            margin-top: 3vh;
            font-size: 8vh;
            color: #a30401;
        }

        .navMobile nav{
            display: none;
        }

        
    }
</style>
