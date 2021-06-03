<template>
  <div class="bodyText">
    <h2 class="titulo">Estamos prontos <br> <strong>para te atender.</strong></h2>
    <br>
    <span class="subtitulo">Nossa experiência em mercado comprova a nossa qualidade. Temos soluções completas, para atender você e sua empresa.</span>
    <br>
    <h3 class="subtitulo2">Canal de <strong>denúncia</strong></h3>
    <br>
    <span class="texto">Este canal pode ser acessado pelo e-mail denuncias@titcs.com.br, pelo
      telefone +55 (61) 3711-7353 ou via correspondência para o endereço:
      Diretoria de Inspeção CEP: 70610-410 SIG Quadra 1 Lote 385 - Edifício
      Platinum Office 3º Andar - Sala 315 Brasília / DF. As denúncias podem ser
      feitas de forma anônima e neste caso o denunciante não será identificado em
      hipótese alguma. O anonimato e o sigilo estarão sempre garantidos,
      confirmando-se ou não as denúncias apontadas. Não haverá o registro dos IPs
      dos computadores dos usuários do sistema via internet e nem dos telefones.
      Todas denúncias serão analisadas individualmente, com confidencialidade e
      profissionalismo.</span>
    </div>
</template>

<script>
export default {
  name: 'corpo',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

  .bodyText{
    width: 60%;
    margin-left: 15vw;
  }
  .titulo{
    font-size: 9.6vh;
    line-height: 8.48vh;
    letter-spacing: -0.14705882352941177vw;
    margin: 0;
  }

  .titulo strong, .subtitulo2 strong{
    color: #a30401;
  }

  .titulo ::after{
    content: '';
    background-color: #a30401;
    width: 5.294117647058823vw;
    height: 0.8vh;
    display: block;
    margin-top:2.4vh ;
  }


  .subtitulo{
    font-size: 2.72vh;
    width: 80%;
    margin-bottom: 0;
  }

  .subtitulo2{
    font-size: 3.52vh;
    display: block;
    margin-bottom: 0;
  }

  .texto{
    font-size: 2.72vh;
    margin-bottom: 0;
  }

  @media(max-width: 800px){
    .bodyText{
      margin: 10px;
      width: 90%;
      text-align: left;
    }

    .titulo ::after{
    content: '';
    background-color: #a30401;
    width: 25vw;
    height: 0.8vh;
    display: block;
    margin-top:2.4vh ;
  }
  }
</style>
