<script setup>
import LinkedinIcon from './Components/Icons/LinkedinIcon.vue'
import GithubIcon from './Components/Icons/GithubIcon.vue'
</script>
<template>
  <main>
    <section class="presentation">
      <div class="presentation-left">
        <h1 class="fw-bold display-4">Leonel Ibarra</h1>
        <h3 class="fw-bold highlight">Fullstack Developer</h3>
        <p>
          Inicié mi carrera profesional como desarrollador hace más de
          6 años. Participé en multiples proyectos del sector público
          y privado, colaborando con dististos equipos y profesionales.
        </p>
        <LinkedinIcon class="me-3"/>
        <GithubIcon />
      </div>
      <div>
        <img
          src="https://picsum.photos/200"
          class="rounded-circle image"
          alt="Imagen Leonel"
        >
      </div>
    </section>
  </main>
</template>

