<script setup lang="ts">
function efectoHabilidades() {
  var skills = document.getElementById("skills");
  var distancia_skills =
    window.innerHeight - skills.getBoundingClientRect().top;
  if (distancia_skills >= 300) {
    let habilidades = document.getElementsByClassName("progreso");
    habilidades[0].classList.add("javascript");
    habilidades[1].classList.add("htmlcss");
    habilidades[2].classList.add("photoshop");
    habilidades[3].classList.add("comunicacion");
    habilidades[4].classList.add("trabajo");
    habilidades[5].classList.add("creatividad");
  }
}

//detecto el scrolling para aplicar la animacion de la barra de habilidades
window.onscroll = function () {
  efectoHabilidades();
};
</script>
<template>
  <section class="skills" id="skills">
    <div class="contenido-seccion">
      <h2>Skills</h2>
      <div class="fila">
        <div class="col">
          <h3>Technical Skills</h3>
          <div class="skill">
            <span>Javascript</span>
            <div class="barra-skill">
              <div class="progreso">
                <span>75%</span>
              </div>
            </div>
          </div>
          <div class="skill">
            <span>HTML & CSS</span>
            <div class="barra-skill">
              <div class="progreso">
                <span>89%</span>
              </div>
            </div>
          </div>
          <div class="skill">
            <span>Photoshop</span>
            <div class="barra-skill">
              <div class="progreso">
                <span>95%</span>
              </div>
            </div>
          </div>
        </div>
        <div class="col">
          <h3>Professional Skills</h3>
          <div class="skill">
            <span>Comunicación</span>
            <div class="barra-skill">
              <div class="progreso">
                <span>80%</span>
              </div>
            </div>
          </div>
          <div class="skill">
            <span>Trabajo en Equipo</span>
            <div class="barra-skill">
              <div class="progreso">
                <span>70%</span>
              </div>
            </div>
          </div>
          <div class="skill">
            <span>Creatividad</span>
            <div class="barra-skill">
              <div class="progreso">
                <span>99%</span>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>
