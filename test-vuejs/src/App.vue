<script setup>
import { RouterView, RouterLink } from "vue-router";
</script>

<template>
  <div>
    <nav>
      <ul>
        <li><RouterLink :to="{ name: 'home' }">Home</RouterLink></li>
        <li><RouterLink :to="{ name: 'about' }">About</RouterLink></li>
      </ul>
    </nav>
    <RouterView />
  </div>
</template>