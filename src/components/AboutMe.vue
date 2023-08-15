<template>
  <div class="conteiner-about">
    <div class="about-main">
      <h2 class="about-title">Sobre Mim</h2>
      <p class="about">
        Bem Vindo(a) ao meu portifólio! Meu nome é Bruno Cantarelli, tenho 19
        anos e atualmente estou cursando Sistemas de Informação pela UFSM
        (Universidade Federal de Santa Maria) e Engenharia de Software pela
        Unicesumar. Entrei nesse mundo da tecnologia no começo de 2022, desde
        então não penso mais em trabalhar em outra área que não seja essa! Meu
        principal objetivo é ser Full-Stack, porém, atualmente estou focando no
        Front-end e procurando um estágio!
      </p>
    </div>
    <div class="intro-img">
      <img src="@/assets/img/study2.svg" alt="Logo de HTML, JS e CSS" />
    </div>
  </div>
</template>

<script></script>
<style>
@import url("https://fonts.googleapis.com/css2?family=Barlow+Condensed:wght@300&display=swap");
@import url("https://fonts.googleapis.com/css2?family=Caveat&display=swap");

.conteiner-about {
  display: flex; /* Utilize flex para alinhar lado a lado */
  background-image: url(@/assets/img/sobre-mim.svg);
  background-size: cover;
  height: 100vh;
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
  font-family: "Caveat", cursive;
  font-size: 90px;
  flex-direction: column;
}

.about {
  color: #ffffff;
  font-family: "Barlow Condensed", sans-serif;
  font-size: 50px;
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
