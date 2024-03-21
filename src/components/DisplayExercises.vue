<script setup>
 const exercises = [
  'Goblet Squats',
  'Turkish Getups',
  'Russian Twists',
  'KB Suitcase Deadlifts',
  'KB Swings',
  'KB 1-Arm Swings',
  'KB Overhead Squats',
  'KB 1-Arm Overhead Squats',
  'KB Press',
  'KB 1-Arm Press',
  'KB Clean & Press',
  'KB 1-Arm Clean & Press',
  'KB Halos',
 ]

  const randomizeExercies = exercises.sort(function() { return 0.5 - Math.random() });
</script>

<template>
  <div class="container">
    <div v-for="exercise in randomizeExercies.slice(0, 4)" :key="exercise">{{ exercise }}</div>
  </div>
</template>