<template>
  <div>
    <ul>
        <li class="first">Menu</li>
      <li v-for="link in Links" :key="link.id">{{ link }}</li>
    </ul>
  </div>
</template>

<script>
export default {
  data() {
    return {
      Links: [ 'About us', 'Theme', 'Features', 'Pricing', 'Blog']
    };
  },
};
</script>

<style>
</style>