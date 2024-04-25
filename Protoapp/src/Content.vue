<template>
  <div class="d-flex text-center justify-content-center">
    <div class="container">
      <h1>{{ title }}</h1>
      <h4>{{ body }}</h4>
    </div>
  </div>
</template>

<script>
export default {
  props: ["title", "body"],
};
</script>