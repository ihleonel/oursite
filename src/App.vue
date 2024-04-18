<script setup>
import LinkedinIcon from './Components/Icons/LinkedinIcon.vue'
import GithubIcon from './Components/Icons/GithubIcon.vue'
</script>
<template>
  <main>
    <section class="presentation">
      <div class="presentation-left">
        <h1 class="fw-bold display-4">Leonel Ibarra</h1>
        <h3 class="fw-bold">Fullstack Developer</h3>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.
          Officiis vel placeat quam, nemo explicabo odit eius.</p>
        <a
          href="https://www.linkedin.com/in/leonel-ibarra-91967723a/"
          target="_blank"
        >
          <LinkedinIcon />
        </a>
        <a
          href="https://github.com/ihleonel"
          target="_blank"
          >
          <GithubIcon />
        </a>
      </div>
      <div>
        <img
          src="https://picsum.photos/200"
          class="rounded-circle"
          alt="Imagen Leonel"
        >
      </div>
    </section>
  </main>
</template>

