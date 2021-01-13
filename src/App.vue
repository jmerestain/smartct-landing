<template>
  <div id="app" class="flex flex-col justify-between min-h-screen">
    <Navbar />
    <router-view />
    <footer class="bg-tertiary py-5">
      <div class="flex flex-col items-center container mx-auto lg:px-20 px-5">
        <img class="mx-auto" :src="require('@/assets/img/Smart-CT-White 1.png')" />
        <div class="flex justify-center">
          <p class="text-white text-sm py-2 font-light tracking-wide">
            This work and its contents by SmartCitiesPH, Inc. is licensed under a Creative Commons
            Attribution-NonCommercial-ShareAlike 4.0 International License. Other works (software,
            source code, etc.) referenced in this website are under their own respective licenses.
          </p>
        </div>
      </div>
    </footer>
  </div>
</template>

<script>
import Navbar from '@/components/Navbar.vue';

export default {
  name: 'App',
  components: {
    Navbar,
  },
};
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Poppins&display=swap');

#app, html, body {
  min-height: 100vh;
  font-family: 'Poppins', sans-serif;
}
.bg-primary {
  background: #ff5039;
}
.text-primary {
  color: #ff5039;
}
.bg-secondary {
  background: #87c540;
}
.text-secondary {
  color: #87c540;
}
.bg-tertiary {
  background: #410f35;
}
.text-tertiary {
  color: #410f35;
}
</style>
