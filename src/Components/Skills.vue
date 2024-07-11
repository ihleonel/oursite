<script setup>
import HtmlIcon from './Icons/Technologies/HtmlIcon.vue'
import CssIcon from './Icons/Technologies/CssIcon.vue'
import JavascriptIcon from './Icons/Technologies/JavascriptIcon.vue'
import ReactIcon from './Icons/Technologies/ReactIcon.vue'
import VueIcon from './Icons/Technologies/VueIcon.vue'
import SassIcon from './Icons/Technologies/SassIcon.vue'
import ViteIcon from './Icons/Technologies/ViteIcon.vue'
import PhpIcon from './Icons/Technologies/PhpIcon.vue'
import LaravelIcon from './Icons/Technologies/LaravelIcon.vue'
import ApacheIcon from './Icons/Technologies/ApacheIcon.vue'
import PythonIcon from './Icons/Technologies/PythonIcon.vue'
import DjangoIcon from './Icons/Technologies/DjangoIcon.vue'
import NginxIcon from './Icons/Technologies/NginxIcon.vue'
import DockerIcon from './Icons/Technologies/DockerIcon.vue'
import MysqlIcon from './Icons/Technologies/MysqlIcon.vue'
import PostgresqlIcon from './Icons/Technologies/PostgresqlIcon.vue'
import GitIcon from './Icons/Technologies/GitIcon.vue'
import GitHIcon from './Icons/Technologies/GitHIcon.vue'
import GitLabIcon from './Icons/Technologies/GitLabIcon.vue'
import FigmaIcon from './Icons/Technologies/FigmaIcon.vue'
import SlackIcon from './Icons/Technologies/SlackIcon.vue'

</script>
<template>
  <div class="row">
    <div class="col-6">
      <div class="wrapper">
        <h4 class="text-center my-3">Frontend</h4>
        <div class="row mb-1">
          <div class="col-4 text-center">
            <HtmlIcon class="icon"/>
            <small class="fw-bold">HTML</small>
          </div>
          <div class="col-4 text-center">
            <CssIcon class="icon"/>
            <small class="fw-bold">CSS</small>
          </div>
          <div class="col-4 text-center">
            <JavascriptIcon class="icon"/>
            <small class="fw-bold">JavaScript</small>
          </div>
        </div>
        <div class="row">
          <div class="col-4 text-center">
            <ReactIcon class="icon"/>
            <small class="fw-bold">ReactJS</small>
          </div>
          <div class="col-4 text-center">
            <VueIcon class="icon"/>
            <small class="fw-bold">VueJS</small>
          </div>
          <div class="col-4 text-center">
            <SassIcon class="icon"/>
            <small class="fw-bold">Sass</small>
          </div>
        </div>
        <div class="row">
          <div class="col-4 text-center">
            <ViteIcon class="icon"/>
            <small class="fw-bold">Vite</small>
          </div>
        </div>
      </div>
    </div>
    <div class="col-6">
      <div class="wrapper">
        <h4 class="text-center my-3">Backend</h4>
        <div class="row">
          <div class="col-4 text-center">
            <PhpIcon class="icon"/>
            <small class="fw-bold">PHP</small>
          </div>
          <div class="col-4 text-center">
            <LaravelIcon class="icon"/>
            <small class="fw-bold">Laravel</small>
          </div>
          <div class="col-4 text-center">
            <ApacheIcon class="icon"/>
            <small class="fw-bold">Apache</small>
          </div>
        </div>
        <div class="row">
          <div class="col-4 text-center">
            <PythonIcon class="icon"/>
            <small class="fw-bold">Python</small>
          </div>
          <div class="col-4 text-center">
            <DjangoIcon class="icon"/>
            <small class="fw-bold">Django</small>
          </div>
          <div class="col-4 text-center">
            <NginxIcon class="icon"/>
            <small class="fw-bold">Nginx</small>
          </div>
        </div>
        <div class="row">
          <div class="col-4 text-center">
            <DockerIcon class="icon"/>
            <small class="fw-bold">Docker</small>
          </div>
          <div class="col-4 text-center">
            <MysqlIcon class="icon"/>
            <small class="fw-bold">MySQL</small>
          </div>
          <div class="col-4 text-center">
            <PostgresqlIcon class="icon"/>
            <small class="fw-bold">PostgreSQL</small>
          </div>
        </div>
     </div>
    </div>
  </div>
  <div class="row">
    <div class="col-12">
      <div class="wrapper mt-4">
        <h3 class="text-center my-2">Tools</h3>
        <div class="row">
          <div class="col-2 text-center">
            <GitIcon class="icon"/>
            <small class="fw-bold">Git</small>
          </div>
          <div class="col-2 text-center">
            <GitHIcon class="icon"/>
            <small class="fw-bold">GitHub</small>
          </div>
          <div class="col-2 text-center">
            <GitLabIcon class="icon"/>
            <small class="fw-bold">GitLab</small>
          </div>
          <div class="col-2 text-center">
            <SlackIcon class="icon"/>
            <small class="fw-bold">Slack</small>
          </div>
          <div class="col-2 text-center">
            <FigmaIcon class="icon"/>
            <small class="fw-bold">Figma</small>
          </div>

        </div>
      </div>
    </div>
  </div>
</template>
<style scoped>
.wrapper {
  border: 1px solid var(--secondary-color);
  border-radius: 10px;
  padding-bottom: 1em;

  &:hover {
    box-shadow: 0 0 20px 2px var(--secondary-color);
  }
}
.icon {
  width: 70px;
  margin: .5em;
}
</style>
