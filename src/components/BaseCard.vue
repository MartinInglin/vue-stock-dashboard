<template>
    <div class="base-card">
      <slot></slot>
    </div>
  </template>
  
  <script>
  export default {
    name: 'BaseCard',
  };
  </script>
  
  <style scoped>
  .base-card {
    background-color: #011F35;
    border-radius: 16px;
    padding: 20px 32px 20px 32px;
  }
  </style>
  