<script setup>
  import DisplayReps from './components/DisplayReps.vue'
  import DisplayExercises from './components/DisplayExercises.vue'
</script>

<template>
  <main class="h-dvh bg-gray-50 p-3">
    <div class="border border-black rounded bg-white max-w-sm mx-auto w-full h-full">
      <DisplayReps />
      <DisplayExercises />
    </div>
  </main>
</template>