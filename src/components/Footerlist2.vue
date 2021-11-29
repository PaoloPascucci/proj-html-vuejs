<template>
  <div>
    <ul>
        <li class="first">About us</li>
      <li v-for="contact in Contacts" :key="contact.id">{{ contact }}</li>
    </ul>
  </div>
</template>

<script>
export default {
  data() {
    return {
          Contacts:[
      "About Sofbox", "Roadmap", "How it Work", "Team", "News"
    ]
    };
  },
};
</script>

<style>
</style>