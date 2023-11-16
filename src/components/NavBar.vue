<script>
export default {
  mounted() {
    const aboutTextElement = document.getElementById("about-text");
    const aboutText = `Bruno Cantarelli`;

    let index = 0;

    function typeAboutText() {
      aboutTextElement.textContent = aboutText.slice(0, index);
      index++;

      if (index <= aboutText.length) {
        setTimeout(typeAboutText, 100); 
      }
    }

    typeAboutText();
  },
};
</script>

<template>
  <div class="container-nav">
    <div class="div-name">
      <h1 class="name">
        <a href="#" class="name" id="about-text"></a>
      </h1>
    </div>
    <div class="div-options">
      <nav>
        <ul class="menu-options">
          <li>
            <a
              class="menu-option"
              href="https://www.instagram.com/brunoo_cantarelli/"
              target="_blank"
            >
              <img
                class="img-menu"
                src="@/assets/img/logo-instagram.svg"
                alt="Logo do Instagram"
              />
              Instagram
            </a>
          </li>
          <li>
            <a
              class="menu-option"
              href="https://www.linkedin.com/in/bruno-cantarelli-67a35022b"
              target="_blank"
            >
              <img
                class="img-menu"
                src="@/assets/img/logo-linkedin.svg"
                alt="Logo do Linked-in"
              />
              Linked-in
            </a>
          </li>
          <li>
            <a
              class="menu-option"
              href="https://api.whatsapp.com/send?phone=5555981294385&text=Olá! Vi seu portifólio, gostaria de conversar com você."
              target="_blank"
            >
              <img
                class="img-menu"
                src="@/assets/img/logo-whatsapp.svg"
                alt="Logo do Whatsapp"
              />
              Whatsapp
            </a>
          </li>
          <li>
            <a
              class="menu-option"
              href="https://github.com/BrunoCantarelli"
              target="_blank"
            >
              <img
                class="img-menu"
                src="@/assets/img/logo-github.svg"
                alt="Logo do GitHub"
              />
              Git-Hub
            </a>
          </li>
        </ul>
      </nav>
    </div>
  </div>
</template>

<style>
@import url("https://fonts.googleapis.com/css2?family=Montserrat:wght@900&family=Open+Sans:ital,wght@0,400;0,700;1,400&display=swap");
@import url("https://fonts.googleapis.com/css2?family=Caveat&display=swap");
@import url("https://fonts.googleapis.com/css2?family=Lobster&display=swap");
@import url("https://fonts.googleapis.com/css2?family=Comfortaa:wght@300;400&display=swap");

.container-nav {
  background-color: rgba(255, 255, 255, 0.623);
  justify-content: space-between;
  position: fixed;
  display: flex;
  width: 100%;
  padding: 20px;
}
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }
.name {
  text-decoration: none;
  color: inherit;
  font-family: "Caveat", cursive;
  font-size: 40px;
}

.div-options {
  display: flex;
}

.menu-options {
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  align-items: center;
  list-style: none;
  font-family: "Comfortaa", cursive;
  font-size: 20px;
}

.menu-option {
  display: flex;
  flex-direction: row;
  justify-content: space-around;
  align-items: center;
  width: 170px;
  text-decoration: none;
  margin: 0 40px 0 0;
  position: relative;
  color: #01012c;
}

.menu-option::after {
  content: "";
  position: absolute;
  bottom: -0.4rem;
  left: 0;
  width: 0;
  height: 0.2rem;
  background-color: #0011aa;
  transition: all 300ms ease-in-out;
}

.menu-option:hover::after {
  width: 100%;
}

.img-menu {
  width: 50px;
  height: auto;
}
</style>
