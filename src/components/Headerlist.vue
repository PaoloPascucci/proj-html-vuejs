<template>
  <div>
    <ul class="header_list">
      <li v-for="link in Links" :key="link.id">
        <a href="#">{{ link }}</a>
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  data() {
    return {
      Links: ["Home", "About Us", "Feature", "Testimonials", "Contact Us"],
    };
  },
};
</script>

<style lang="scss">
.header_list {
  display: flex;
  flex-direction: row;
  li {
    padding: 0 2.1rem;
    list-style: none;
    a {
      color: black;
      text-decoration: none;
      font-weight: bold;
    }
  }
}
</style>