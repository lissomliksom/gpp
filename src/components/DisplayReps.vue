<script setup>
  const repetitionVariations = [
    '21-15-9',
    '5 x 5',
    '5-4-3-2-1'
  ]
  const randomRepetitionVariation = repetitionVariations[Math.floor(Math.random() * repetitionVariations.length)]
</script>

<template>
  <div class="container">
    <p>{{ randomRepetitionVariation }}</p>
  </div>
</template>