<template>
  <div class="">
    <NavBar />

    <!-- Hero section  -->
    <div class="grid gap-y-[32px] py-13 text-center font-normal">
      <button type="button">Introducing Rafts Card</button>

      <h1 class="text-white text-8xl">Building the future of banking</h1>

      <p class="custom-text-gray text-2xl">
        Experience the future of banking with RAFT. We're here <br />
        to empower your financial journey.
      </p>

      <div>
        <button
          type="button"
          class="custom-btn-bg-green text-white py-4 px-8 font-semibold border-radius-100"
        >
          Get Started
        </button>
      </div>
    </div>
  </div>
</template>

<script setup>
import NavBar from '@/components/NavBar.vue'
</script>
