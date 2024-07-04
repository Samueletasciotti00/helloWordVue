<!-- src/components/Jumbotron.vue -->
<template>
    <div class="jumbotron">
      <h1 class="display-4">{{ title }}</h1>
      <p class="lead">{{ subtitle }}</p>
      <hr class="my-4">
      <p>{{ description }}</p>
      <a class="btn btn-primary btn-lg" :href="buttonLink" role="button">{{ buttonText }}</a>
    </div>
  </template>
  
  <script>
  export default {
    name: 'Jumbotron',
    props: {
      title: {
        type: String,
        required: true
      },
      subtitle: {
        type: String,
        required: true
      },
      description: {
        type: String,
        required: true
      },
      buttonText: {
        type: String,
        required: true
      },
      buttonLink: {
        type: String,
        required: true
      }
    }
  };
  </script>
  
  <style scoped>
  .jumbotron {
    padding: 2rem 1rem;
    background-color: #e9ecef;
    border-radius: .3rem;
  }
  </style>
  
  