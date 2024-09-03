
    <script setup lang="ts">
    </script>


<template>
  <v-app class="bg-white" >
    <v-container class="container1 bg-red" >
      <v-app-bar :elevation="1" class="bg-white pa-2">
        <template v-slot:prepend>
          <img class="sicredi-logo" src="./assets/image.png" alt="" srcset="" width="50px">
        </template>

        <v-btn class="text-none bg-green-darken-3 mr-12 px-3 py-5 d-flex"><p class="btn-text">Abrir conta</p></v-btn>

      </v-app-bar>
    </v-container>

    <div class="pagini mb-5 ml-13 d-flex" >
    <p class="pgini mr-3"> Página inicial</p>   <p class="mr-3"> > </p>   <p>Seja Associado</p>
    </div>

      <div class="main bg-red d-flex">
        <v-container class="contar">
          <div class="main-title">
            <h1 class="mb-4">Não é só dinheiro, é ter com quem contar</h1>
            <h5>Abra a sua conta com a gente e peça seu cartão, sujeiro à análise de crédito</h5>
          </div>

          <v-card class="card-name bg-white pa-4">
            <v-card-title class="card-title">Informe seu nome para iniciar</v-card-title>
            <v-card-actions>
              <v-sheet class="mx-auto" width="400">
                <v-form @submit.prevent class="bg-white" >
                  <v-text-field class="field-nome bg-white" bg-color="white" label="Nome Completo"></v-text-field>
                    <v-btn class="text-none mt-2 bg-green-darken-3" type="submit" block><p class="btn-text">Abrir conta</p></v-btn>
                </v-form>
              </v-sheet>
            </v-card-actions>
          </v-card>
        </v-container>
      </div>


      <h2 class="mt-16">Facilidades dos cartões de crédito do Sicredi</h2>

      <div class="teste-div d-flex">
            <div class="cards d-flex px-10">
              <v-row>
                <v-col class="col-card" sm="12" lg="4" md="6">
                    <v-card
                      class="card-background mx-auto"
                      width="95%"
                      height="100%"
                    >
                      <v-img
                        class="align-end text-white"
                        height="250"
                        width="100%"
                        src="./assets/card1_img.webp"
                        cover
                      >
                    </v-img>

                    <div class="pa-4">
                      <v-card-title class="text-h5">Programa de Recompensa</v-card-title>

                        <v-card-text>
                          <div class="text-h6">Quanto mais você usa, mais pontos você acumula. Troque seus pontos por cashback, milhas em companhias áreas ou compre produtos no Shopping do Sicredi.</div>
                        </v-card-text>

                        <v-card-actions>
                          <v-btn class="text-none text-h6" text="Conhecer programa de recompensa &#x2192;"></v-btn>
                        </v-card-actions>
                      </div>

                    </v-card>
                </v-col>

                <v-col class="col-card" sm="12" lg="4" md="6">
                    <v-card
                      class="card-background mx-auto"
                      width="95%"
                      height="100%"
                    >
                      <v-img
                        class="align-end text-white"
                        height="250"
                        width="100%"
                        src="./assets/card2_img.webp"
                        cover
                      >
                    </v-img>

                    <div class="pa-4">
                      <v-card-title class="text-h5">Carteira Digital</v-card-title>

                        <v-card-text>
                          <div class="text-h6">Segurança e praticidade para suas transações via Apple Pay, Samsung Pay e Pagamentos por WhatsApp.</div>
                        </v-card-text>

                        <v-card-actions>
                          <v-btn class="text-none text-h6" text="Conhecer carteiras digitais &#x2192;"></v-btn>
                        </v-card-actions>
                      </div>

                    </v-card>
                </v-col>
                <v-col class="col-card" sm="12" lg="4" md="6">
                    <v-card
                      class="card-background mx-auto"
                      width="95%"
                      height="100%"
                    >
                      <v-img
                        class="align-end text-white"
                        height="250"
                        width="100%"
                        src="./assets/card3_img.webp"
                        cover
                      >
                    </v-img>

                    <div class="pa-4">
                      <v-card-title class="text-h5">Cartão Virtual</v-card-title>

                        <v-card-text>
                          <div class="text-h6">Segurança para suas compras online, em aplicativos ou outros serviços, tanto em transações únicas, como nas recorrentes.</div>
                        </v-card-text>

                        <v-card-actions>
                          <v-btn  class="text-none text-h6" text="Conhecer cartão virtual &#x2192;"></v-btn>
                        </v-card-actions>
                      </div>

                    </v-card>
                </v-col>

              </v-row>
            </div>
      </div>

    <h2>Benefícios de cada cartão de crédito</h2>
      <p class="text-h6 ml-12 mb-5">Encontre o cartão ideal para realizar seus planos.</p>

        <div class="teste-div d-flex">
            <div class="cards d-flex px-10" width="100%" >
              <v-row>

                <v-col sm="12" lg="4" md="6">
                  <v-card class="sicredi-card bg-white d-flex pa-8" width="100%" height="500">
                    <v-card-title class="title-card2">Cartão Sicredi Gold</v-card-title>
                    <v-btn class="text-none bg-green-darken-1 mt-4 mb-6 px-6" size="large"><p class="btn-label">Solicitar Cartão</p></v-btn>
                    <v-card-text>  <p class="card-icon-text ml-n2"> <img src="./assets/icon_seguro-protecao.png" width="25px" class="mr-3"> Seguro proteção de preço </p> <p class="ml-7 text-h6 font-weight-medium">Quando voce paga integralmente um item da lista de bens elegíveis, você pode receber a diferença do valor quando encontrar o mesmo item (mesma marca, modelo e ano) por um preço menor.</p></v-card-text>
                    <v-btn class="expandir-caracteristicas text-none bg-white" size="large"><p class="font-weight-bold">Expandir características <img src="./assets/arrow-down.svg"> </p></v-btn>
                  </v-card>
                </v-col>

                <v-col sm="12" lg="4" md="6">
                  <v-card class="sicredi-card bg-white d-flex pa-8" width="100%" height="500">
                    <v-card-title class="title-card2">Cartão Sicredi Platinum</v-card-title>
                    <v-btn class="text-none bg-green-darken-1 mt-4 mb-6 px-6" size="large"><p class="btn-label">Solicitar Cartão</p></v-btn>
                    <v-card-text>  <p class="card-icon-text ml-n2"> <img src="./assets/icon_assistencia.png" width="25px" class="mr-3"> Assistência global de emergência </p> <p class="ml-7 text-h6 font-weight-medium">Atendimento 24 horas por dia, 365 dias por ano, em qualquer idioma, para casos de perda ou roubo de cartão</p></v-card-text>
                    <v-btn class="expandir-caracteristicas text-none bg-white" size="large"><p class="font-weight-bold">Expandir características <img src="./assets/arrow-down.svg"> </p></v-btn>
                  </v-card>
                </v-col>


                <v-col sm="12" lg="4" md="6">
                  <v-card class="sicredi-card bg-white d-flex pa-8" width="100%" height="500">
                    <v-card-title class="title-card2">Cartão Sicredi Mastercard Black<span class = "text-grey-darken-2" >&#x2122; </span></v-card-title>
                    <v-btn class="text-none bg-green-darken-1 mt-4 mb-6 px-6" size="large"><p class="btn-label">Solicitar Cartão</p></v-btn>
                    <v-card-text>  <p class="card-icon-text ml-n2"> <img src="./assets/icon_salas_VIP.png" width="25px" class="mr-3"> Salas VIP </p> <p class="ml-7 text-h6 font-weight-medium">Você aguarda o seu voo no conforto de uma sala VIP. São 1.100 salas em mais de 120 países</p></v-card-text>
                    <v-btn class="expandir-caracteristicas text-none bg-white" size="large"><p class="font-weight-bold">Expandir características <img src="./assets/arrow-down.svg"></p></v-btn>
                  </v-card>
                </v-col>
              </v-row>
            </div>
          </div>


          <v-container class="mb-15">
            <h2 class="abrir-conta-title text-green ml-1">Ao abrir uma conta, você se torna associado, mas <strong class="ser-associado">o que é ser associado?</strong> </h2>

            <p class="text-h6">É ser mais do que apenas “um cliente” ou “um correntista”, é ser dono da instituição financeira cooperativa. A cooperativa reúne pessoas com o mesmo propósito na região onde atua. Ela funciona de forma democrática, e isso significa que todos os associados podem participar das decisões que fazem a diferença para sua região e sua vida, definindo como os resultados financeiros serão distribuídos ou investidos.</p>
          </v-container>




  </v-app>
</template>

<style scoped>
  @import url('https://fonts.googleapis.com/css2?family=Exo+2:ital,wght@0,100..900;1,100..900&family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap');

* {
  font-family: 'Nunito';
}

.v-app-bar {
  background-color: aqua;
}

  .abrir-conta-title {
    line-height: 50px;
    margin-bottom: 3rem;
  }

  .ser-associado  {
    letter-spacing: 0.6px;
    font-size: 2.8rem;
  }

  .sicredi-card{
    align-items: center;
    flex-direction: column;
    box-shadow: rgba(100, 100, 111, 0.2) 0px 7px 29px 0px;
  }

  .expandir-caracteristicas{
    box-shadow:none;
  }

  .expandir-caracteristicas p{
    color: rgb(1, 162, 1);
  }

  .expandir-caracteristicas p img{
    width: 13px;
  }


  .card-icon-text {
    display: flex;
    font-size: 1.1rem;
    color: rgb(96, 96, 96);
    margin-bottom: 2px;
  }

  .btn-label {
    font-size: 1.2rem;
    letter-spacing: 0.7px;
    font-weight: 550;
  }

  .btn-text {
    font-size: 1rem;
    font-weight: 550 !important;
    letter-spacing: 0.2px;
  }

  .teste-div{
    justify-content: center;
  }

  .title-card2{
    font-size: 1.8rem;
  }

  .card-title{
    font-family: 'Exo 2' !important;
    font-weight: 400 !important;
    margin-left: 1rem;
    font-size: 1rem;
    color: rgb(93, 93, 93);
  }

  .cards{
    margin: 0;
    margin-top: 1rem;
    width:100%;
    margin-bottom: 3rem;
  }

  .card-background {
    background-color: rgb(0, 64, 0);
    border-radius: 10px;
  }

  .contar {
    width: 35rem;
    height: 30rem;
    align-self: center;
    margin-left: 4rem;

    @media (max-width: 950px) {
      width: 100%;
    }
  }

  .sicredi-logo{
    width: 14rem;
  }

  h1{
    font-size:3rem;
    font-weight: 400 !important;
  }

  h2{
    font-family: 'Exo 2' !important;
    font-size: 2.5rem;
    margin-top: 2rem;
    margin-left: 3rem;
    font-weight: 400 !important;
  }

  h5 {
    font-size: 1rem;
    font-weight: 400 !important;
  }

  .pagini{
    margin-top: 4rem;
    font-size: 14px;
    font-weight: 700;
    letter-spacing: 50%;
    font-weight: 400 !important;
  }

  .pgini {
    color: rgb(11, 74, 31);
  }

  .main{
    background-image: url('./assets/media_produtos_filer_public_thumbnails_filer_public_2024_06_28_banner-seja-associado-sicredi-ana-castela.png__1717x768_subsampling-2.webp');
    background-position: center;
    background-size: cover;
    background-color: rgb(11, 74, 31);
    height: 711px;
    width: 100%;

     @media (max-width: 950px) {
      background-color: rgb(11, 74, 31) !important;
      background-image: url('./assets/background_sicredi_celular.webp');
    }
  }

    .card-name{
      margin-top: 3rem;
      width: 85%;
      border-radius: 15px;
    }

    .main-title h1{
      font-family: 'Exo 2' !important;
      line-height: 110%;
      font-style: italic !important;

      @media (max-width: 950px) {
        font-size: 2.5rem;
      }
    }

    .main-title {
      @media (max-width: 950px) {
        margin-top: -90px;
        margin-bottom: 290px;
        width: 100% !important;
      }
    }


    .field-nome >>> input {
      background-color: white !important;
      border-block-end-width: 1px;
    }


    @media (max-width: 564px) {
        .sicredi-card {
          width: 380px !important;
          margin-left: -1rem;
        }

        .cards {
          padding: 10px !important;
          width: 400px;
        }

        .card-background {
          width: 90%;
        }

        h2 {
          font-size: 1.8rem;
          margin-left: 10px;
        }

        .title-card2 {
          font-size: 1.5rem;
        }

        .contar {
          margin-left: 0;
        }

    }


</style>
