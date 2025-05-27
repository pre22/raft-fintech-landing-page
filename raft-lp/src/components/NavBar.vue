<template>
  <nav class="flex justify-between content-center text-white nav-bd py-4 px-[2rem]">
    <!-- logo  -->
    <div>
      <img src="/src/assets/img/raft.png" alt="Raft" srcset="" />
    </div>

    <div class="flex justify-between custom-text-gray">
      <RouterLink to="/" class="px-4">Solutions</RouterLink>
      <RouterLink to="/" class="px-4">Learn</RouterLink>
      <RouterLink to="/" class="px-4">About</RouterLink>
    </div>

    <!-- buttons  -->
    <div>
      <button type="button" class="py-2 px-3 font-semibold">Login</button>
      <button type="button" class="custom-btn-bg-green py-2 px-3 font-semibold border-radius-100">
        Get Started
      </button>
    </div>
  </nav>
</template>

<style scoped>
.nav-bd {
  border-bottom: 1px solid #3d3d3d;
}
</style>

<script setup>
import { RouterLink } from 'vue-router'
</script>
