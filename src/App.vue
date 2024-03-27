<script setup lang="ts">
import { RouterLink, RouterView } from "vue-router";
import Perfil from "./components/Perfil.vue";
</script>

<template>
  <header>
    <div class="wrapper">
      <Perfil msg="You did it!" />
    </div>
  </header>

  <RouterView />
</template>
