<script setup lang="ts">
import { RouterLink, RouterView } from "vue-router";
import Perfil from "./components/Perfil.vue";
import SobreMi from "./components/SobreMi.vue";
</script>

<template>
  <header>
    <div class="wrapper">
      <Perfil msg="You did it!" />
    </div>
  </header>
  <SobreMi />
  <RouterView />
</template>
