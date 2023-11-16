<script></script>

<template>
  <div class="conteiner-about">
    <div class="about-main">
      <h2 class="about-title">Sobre Mim</h2>
      <p class="about">
        Bem Vindo(a) ao meu portifólio! Meu nome é Bruno Cantarelli, tenho 19
        anos e atualmente estou cursando Sistemas de Informação pela UFSM
        (Universidade Federal de Santa Maria) e Engenharia de Software pela
        Unicesumar.
      </p>
    </div>
    <div class="intro-img">
      <!-- <img src="@/assets/img/study2.svg" alt="Logo de HTML, JS e CSS" /> -->
    </div>
  </div>
</template>

<style>
@import url("https://fonts.googleapis.com/css2?family=Barlow+Condensed:wght@300&display=swap");
@import url("https://fonts.googleapis.com/css2?family=Caveat&display=swap");
@import url("https://fonts.googleapis.com/css2?family=Bebas+Neue&display=swap");
@import url("https://fonts.googleapis.com/css2?family=Ubuntu+Condensed&display=swap");

.conteiner-about {
  display: flex; /* Utilize flex para alinhar lado a lado */
  background-image: url(@/assets/img/direita-azul-cinza.svg);
  background-size: cover;
  height: 100vh;
  align-items: center;
}

.about-main {
  flex: 1; /* Ocupa uma parte flexível do espaço disponível */
  padding: 20px;
}

.about-title {
  display: flex;
  color: #ffffff;
  font-size: 24px;
  margin-bottom: 10px;
  align-items: center;
  font-family: "Bebas Neue", sans-serif;
  font-size: 90px;
  flex-direction: column;
}

.about {
  color: #ffffff;
  font-family: "Ubuntu Condensed", sans-serif;
  font-size: 35px;
  text-align: center;
}

.intro-img {
  flex: 1; /* Ocupa uma parte flexível do espaço disponível */
  display: flex;
  align-items: center;
  justify-content: center;
}

.intro-img img {
  max-width: 100%;
  height: 500px;
}
</style>
