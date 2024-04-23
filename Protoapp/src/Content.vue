<template>
  <div class="text-center">
    <h1>{{ title }}</h1>
    <h2>{{ body }}</h2>
  </div>
</template>

<script>
export default {
    props: ['title', 'body']
};
</script>