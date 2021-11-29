<template>
  <div class="footer">
    <div class="Sx_Footer">
      <img src="../assets/35.png" alt="" />
      <p class="text">
        It is a long established fact that a reader will be distracted by the
        readable content.
      </p>
      <p class="copy">Copyright @ 2018 <a href="#">Sofbox</a></p>
    </div>
    <div class="Dx_Footer">
      <Footerlist/>
      <Footerlist2/>
      <Footerlist3/>
    </div>
  </div>
</template>

<script>
import Footerlist from "@/components/Footerlist.vue"
import Footerlist2 from "@/components/Footerlist2.vue"
import Footerlist3 from "@/components/Footerlist3.vue"
export default {
  components:{
Footerlist,
Footerlist2,
Footerlist3
  },
}
</script>

<style lang="scss">
.footer {
  display: flex;
  flex-direction: row;
  width: 85%;
  margin: auto;
}
.Sx_Footer {
  display: flex;
  flex-direction: column;
  justify-content: center;
  width: 350px;
  img {
    height: 41px;
    width: 117px;
  }
  .text,
  .copy {
    color: rgb(147, 157, 163);
    width: 80%;
    line-height: 30px;
  }
  .copy {
    padding-top: 1rem;
    a {
      text-decoration: none;
    }
  }
}
.Dx_Footer {
  display: flex;
  margin-left: 8rem;
  ul {
    margin: 0 6rem 0 5rem;
    list-style: none;
    line-height: 30px;
    li {
      list-style: none;
    }
  }
  .first {
    font-weight: bold;
    margin: 10px 0;
  }
}
</style>