<template>
  <div id="app">
<siteHeader/>
<siteMain/>
<siteFooter/>
  </div>
</template>

<script>
import siteHeader from "./components/siteHeader.vue"
import siteMain from "./components/siteMain.vue"
import siteFooter from "./components/siteFooter.vue"
export default {
  name: 'App',
  components: {
    siteHeader,
    siteMain,
    siteFooter
  }
}
</script>

<style lang="scss">
// #app {
//   font-family: Avenir, Helvetica, Arial, sans-serif;
//   -webkit-font-smoothing: antialiased;
//   -moz-osx-font-smoothing: grayscale;
//   text-align: center;
//   color: #2c3e50;
//   margin-top: 60px;
// }
@import url('https://fonts.googleapis.com/css2?family=Spartan:wght@400&display=swap');
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
body{
  font-family: 'Spartan', sans-serif;
  width:80%;
  margin: auto  ;

}
</style>
