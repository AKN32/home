<template>
  <div class="home">
    <main class="container text-center">
      <img class="p-4 rounded" src="/andreas.jpg" />
      <h1>Andreas Knops</h1>
      <p>Web-Developer based in Linz / Austria</p>

      <div class="p-4">
        <a
          class="btn btn-secondary"
          href="mailto:andreas@knops.at"
          target="_blank"
          >Email</a
        >

        <a
          class="btn btn-secondary"
          href="https://www.facebook.com/Andreas_Knops2"
          target="_blank"
          >Facebook</a
        >

        <a
          class="btn btn-secondary"
          href="https://www.xing.com/profile/Andreas_Knops2"
          target="_blank"
          >Xing</a
        >
        <a class="btn btn-secondary" href="#" target="_blank">Twitter</a>

        <a
          class="btn btn-secondary"
          href="https://www.instagram.com/andi.32/"
          target="_blank"
          >Instagram</a
        >

        <a class="btn btn-secondary" href="#" target="_blank">GitHub</a>

        <p class="p-5 text-muted">Made with ❤️ in Linz</p>
      </div>
    </main>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({})
</script>

<style>
@import '~/node_modules/bootstrap/dist/css/bootstrap.css';

html,
body {
  height: 100%;
}

body {
  display: -ms-flexbox;
  display: -webkit-box;
  display: flex;
  -ms-flex-align: center;
  -ms-flex-pack: center;
  -webkit-box-align: center;
  align-items: center;
  -webkit-box-pack: center;
  justify-content: center;
  padding-top: 40px;
  padding-bottom: 40px;
}

footer {
  position: fixed;
  bottom: 0;
  width: 100%;
}
</style>
