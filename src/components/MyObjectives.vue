<script></script>

<template>
  <div class="conteiner-objectives">
    <div class="img-objectives">
      <!-- <img src="@/assets/img/portImg.svg" alt="teste" /> -->
    </div>

    <div class="objectives-main">
      <h1 class="objectives-title">Quais são meus objetivos</h1>
      <div class="objectives-block">
        <li class="objective">
          Ganhar muita
          <spam class="words-importants">expêriencia</spam>
          na área
          <spam class="words-importants">front-end</spam>.
        </li>

        <li class="objective">
          Dominar o
          <spam class="words-importants">desenvolvimento web </spam>
          para fazer cada vez mais projetos e trabalhos.
        </li>

        <li class="objective">
          <spam class="words-importants">Aprender</spam>
          mais profundamente
          <spam class="words-importants">Inglês</spam>.
        </li>

        <li class="objective">
          Começar a estudar
          <spam class="words-importants">linguagens</spam>
          voltadas para
          <spam
            tyle="font-family: 'Caveat', cursive; font-size: 35px; color: #dc143c;"
            >back-end.</spam
          >
        </li>
        <li class="objective">
          Trabalhar
          <spam class="words-importants">fora</spam>
          do país.
        </li>
      </div>
    </div>
  </div>
</template>

<style>
.conteiner-objectives {
  background-image: url(@/assets/img/esquerda-azul-cinza.svg);
  background-size: cover;
  display: flex;
  height: 100vh;
  align-items: center;
}

.objectives-main {
  flex: 1;
}

.img-objectives {
  flex: 1;
}

.img-objectives img {
  max-width: 100%;
  height: 500px;
}

.objectives-title {
  display: flex;
  color: #ffffff;
  font-size: 24px;
  margin-bottom: 10px;
  align-items: center;
  font-family: "Bebas Neue", sans-serif;
  font-size: 90px;
  flex-direction: column;
}

.objective {
  list-style: none;
  font-size: 35px;
  margin-top: 40px;
  color: #ffffff;
  font-family: "Barlow Condensed", sans-serif;
}

.words-importants {
  font-family: "Caveat", cursive;
  font-size: 50px;
  color: #00ccff;
}
</style>
