<template>
<div>
  <ul v-for="link in links" :key="link.id">
          <li><a href="#">{{link.name}}</a></li>
        </ul>
      </div>
</template>

<script>


export default {
    data(){
        links:[
            {name:"Home"},
        {name:"About Us"},
        {name:"Feature"},
        {name:"Testimonials"},
        {name:"Contact Us"}
        ]
    }
}
</script>

<style>

</style>