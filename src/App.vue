<script setup>
import LinkedinIcon from './Components/Icons/LinkedinIcon.vue'
import GithubIcon from './Components/Icons/GithubIcon.vue'
import TwitterIcon from './Components/Icons/TwitterIcon.vue';
import Timeline from './Components/Timeline.vue';
import Skills from './Components/Skills.vue';
</script>
<template>
  <main>
    <section class="presentation">
      <div class="presentation-left">
        <h1 class="fw-bold display-4">Leonel Ibarra</h1>
        <h3 class="fw-bold highlight">Full Stack Developer</h3>
        <p class="description">
          Inicié mi carrera profesional como desarrollador hace más de
          6 años. Participé en multiples proyectos del sector público
          y privado, colaborando con dististos equipos y profesionales.
        </p>
        <div class="social-media">
          <LinkedinIcon />
          <GithubIcon />
          <TwitterIcon />
        </div>
      </div>
      <div class="presentation-right">
        <img
          src="https://picsum.photos/200"
          class="rounded-circle image"
          alt="Imagen Leonel"
        >
      </div>
    </section>
    <section class="experiencia">
      <h3 class="fw-bold">Experiencia</h3>
      <Timeline />
    </section>
    <section class="habilidades">
      <h3 class="fw-bold">Tecnologías</h3>
      <p>
        A continuación listo algunas de las tecnologías con las que trabajé
        en estos años como desarrollador y con las que me siento cómodo y seguro de mis conocimientos.
      </p>
      <Skills />
    </section>
    <section class="contacto">
      <h3 class="fw-bold">Contacto</h3>
    </section>
  </main>
</template>

