<script setup>
</script>
<template>
  <div class="row">
    <div class="col-6">
      <fieldset>
        <legend>Frontend</legend>
        <div class="row mb-1">
          <div class="col-4 text-center">
            <img src="https://img.icons8.com/?size=100&id=20909&format=png&color=000000" alt="HTML 5" class="icon">
            <small>html 5</small>
          </div>
          <div class="col-4 text-center">
            <img src="https://img.icons8.com/?size=100&id=21278&format=png&color=000000" alt="" class="icon">
            <small>css 3</small>
          </div>
          <div class="col-4 text-center">
            <img src="https://img.icons8.com/?size=100&id=108784&format=png&color=000000" alt="" class="icon">
            <small>Javascript</small>
          </div>
        </div>
        <div class="row">
          <div class="col-4 text-center">
            <img src="https://img.icons8.com/?size=100&id=bzf0DqjXFHIW&format=png&color=000000" alt="" class="icon" style="width: 60px;">
            <small>reactjs</small>
          </div>
          <div class="col-4 text-center">
            <img src="https://img.icons8.com/?size=100&id=rY6agKizO9eb&format=png&color=000000" alt="" class="icon">
            <small>vuejs</small>
          </div>
        </div>

      </fieldset>
    </div>
    <div class="col-6">
      <fieldset>
        <legend>Backend</legend>
        <ul>
          <li>PHP</li>
          <li>Python</li>
          <li>Docker</li>
        </ul>
     </fieldset>
    </div>
  </div>
</template>
<style scoped>
fieldset, legend {
  all: revert;
}
fieldset {
  border: 1px solid var(--main-color);
  border-radius: 10px;
}
.icon {
  width: 70px;
}
</style>
