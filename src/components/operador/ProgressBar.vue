<template>
    <div class="progress-bar-wrapper">
      <div class="progress-bar" :style="{ width: progress + '%', backgroundColor: progressColor }"></div>
    </div>
  </template>
  
  <script>
  export default {
    props: {
      progress: Number,
      progressColor: String
    }
  };
  </script>
  
  <style scoped>
  .progress-bar-wrapper {
    /* estilos aquí */
  }
  .progress-bar {
    /* estilos aquí */
  }
  </style>
  