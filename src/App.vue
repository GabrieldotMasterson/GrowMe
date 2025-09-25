<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
import logo from '@/assets/logo.svg'
</script>

<template>
  <link href="https://fonts.googleapis.com/css?family=Inter" rel="stylesheet" />
  <header>
    <div class="effect-nav">
      <span></span>
    </div>
    <nav class="nav">
      <div class="nav-right">
        <img :src="logo" class="nav-logo" alt="" />
      </div>

      <div class="nav-left">
        <a href="">Olimpiads</a>
        <a href="">My network</a>
        <a href="">Projects</a>
        <a href="">Perfil</a>
      </div>
    </nav>
  </header>
  <RouterView />
</template>

<style scoped></style>
