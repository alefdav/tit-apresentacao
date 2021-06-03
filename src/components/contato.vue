<template>

 <section>

     <div class="contato">

     <div class="infos">
         <span>Onde <strong>estamos</strong></span>
         <p><i class="fas fa-map-marker-alt"></i>SIG Quadra 1 Lote 385 - Edifício Platinum</p>
         <p>Office 3º Andar - Sala 315 Brasília / DF</p>
         
         <span><strong>Contato</strong></span>
         <p><i class="fas fa-phone-alt"></i>+55 (61) 3711-7353</p>
         <p><i class="fas fa-envelope"></i>contato@titcs.com.br</p>

         <div class="redes">
             <a href="https://www.instagram.com/titcs/" target="_blank"><i class="fab fa-instagram"></i></a>
             <a href="https://www.facebook.com/titcs" target="_blank" ><i class="fab fa-facebook-square"></i></a>
             <a href="https://www.linkedin.com/company/tit-consultoria-&-servi-os/" target="_blank"><i class="fab fa-linkedin-in"></i></a>
         </div>
     </div>

     <div class="dadosContato">
         <p>Entre em <strong>contato</strong></p>
         <form action="">
             <label for="">Nome:</label>
             <input type="text" placeholder="escreva seu nome">

             <label for="">Email:</label>
             <input type="text" placeholder="escreva seu nome">

             <label for="">Telefone:</label>
             <input type="text" placeholder="escreva seu nome">

             <label for="">Serviço desejado:</label>
             <select name="" id="">
                 <option value="">Selecione</option>
                 <option value="">Desenvolvimento de Sistemas</option>
                 <option value="">Consultoria</option>
                 <option value="">Segurança da informação</option>
                 <option value="">Outsourcing</option>
                 <option value="">Transformação Digital</option>
                 <option value="">Inteligência Artificial</option>
                 <option value="">Automação & Robotização</option>
             </select>
             
             <label for="">Mensagem:</label>
             <textarea name="" id="" cols="40" rows="10" placeholder="Deixe sua mensagem"></textarea>

             <button type="submit"><strong>Enviar</strong></button>
         </form>
     </div>
     
     </div>

 </section>

</template>

<script>
export default {
  name: 'contato',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
    section{
        background-color: #a30401;
        color: white;
        margin-top: 7vh;
    }

   .contato{
       width: 80%;
       display: flex;
       flex-direction: row;
       margin-left: 15vw;
       margin-top: 20px;
   }

   .infos{
       margin-right: 20vw;
       margin-top: 7vh;
   }

   .infos span{
       font-size: 4vh;
   }

   .infos i{
       margin-right: 0.5vw;
   }

   .redes{
       font-size: 5vh;
   } 

   .redes a{
       margin-right: 1vw;
       
       color: white;
   }
   .dadosContato{
       display: flex;
       flex-direction: column;
       margin-top: 7vh;
       margin-bottom: 6vh;
   }

   .dadosContato p{
       margin-top: 0;
       margin-bottom: 1vh;
       font-size: 4vh;
   }
   .dadosContato form{
       display: flex;
       flex-direction: column;
       border: 1px solid white;
       padding: 20px;
   }

   .dadosContato form input, select{
       padding: 1.5vh;
       border-radius: 10px;
       border: none;
       margin-bottom: 10px;
   }

   .dadosContato button{
       padding: 10px;
       border-radius: 20px;
       border: none;
       width: 40%;
       color: #a30401;
       margin: auto;
       margin-top: 10px;
       font-size: 3vh;
       cursor: pointer;
   }


   @media(max-width: 800px){
       .contato{
           flex-direction: column;
           margin: auto;
       }

        .infos{
       margin-right: 20vw;
       margin-top: 7vh;
       }

       .infos span{
            font-size: 5.5vh;
            white-space: nowrap;
       }

       .infos i{
            margin-right: 2vw;
       }

       .redes{
           font-size: 5vh;    
        
       }
   }
</style>
