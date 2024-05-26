<script setup>
</script>
<template>
  <!-- Section: Timeline -->
<div class="mt-3">
  <ul class="timeline">
    <li class="timeline-item">
      <h5 class="fw-bold title">Outsource Argentina</h5>
      <p class="mb-2 dates">Abril 2023 - Actualidad</p>
      <p class="mb-5">
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Sit
        necessitatibus adipisci, ad alias, voluptate pariatur officia
        repellendus repellat inventore fugit perferendis totam dolor
        voluptas et corrupti distinctio maxime corporis optio?
      </p>
    </li>
    <li class="timeline-item">
      <h5 class="fw-bold title">ECI Solution Software</h5>
      <p class="mb-2 dates">Abril 2022 - Abril 2023</p>
      <p class="mb-5 description">
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Sit
        necessitatibus adipisci, ad alias, voluptate pariatur officia
        repellendus repellat inventore fugit perferendis totam dolor
        voluptas et corrupti distinctio maxime corporis optio?
      </p>
    </li>
    <li class="timeline-item">
      <h5 class="fw-bold title">Gobierno de la provincia de Salta</h5>
      <p class="mb-2 dates">Abril 2018 - Abril 2022</p>
      <p class="mb-5">
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Sit
        necessitatibus adipisci, ad alias, voluptate pariatur officia
        repellendus repellat inventore fugit perferendis totam dolor
        voluptas et corrupti distinctio maxime corporis optio?
      </p>
    </li>
  </ul>
</div>
<!-- Section: Timeline -->
</template>
<style scoped>
.timeline {
  margin: 0;
  border-left: 1px solid var(--main-color);
  position: relative;
  list-style: none;
}

.timeline .timeline-item {
  position: relative;
}

.timeline .timeline-item:after {
  position: absolute;
  display: block;
  top: 0;
}

.timeline .timeline-item:after {
  background-color: var(--main-color);
  top: 4px;
  left: -40px;
  border-radius: 50%;
  height: 15px;
  width: 15px;
  content: "";
}

/* .title {
  color: var(--secondary-color);
} */
.dates {
  color: var(--secondary-color);
}
</style>
