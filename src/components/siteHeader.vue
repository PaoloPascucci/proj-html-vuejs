<template>
  <div class="header">
    <div class="Sx_head">
      <img class="logo_head" src="../assets/logo-2.png" alt="" />
    </div>
    <div class="Dx_head">
      <div class="link">
        <Headerlist/>
        </div>
      <div class="search">
        <i class="fas fa-search"></i>
        <i class="fas fa-shopping-cart"></i>
        <div class="number"><span>0</span></div>
      </div>
      <div class="button">
        <button class="get_started">Get Started</button>
      </div>
  </div>
  </div>
</template>

<script>
import Headerlist from "@/components/Headerlist.vue"
export default {
components:{
Headerlist,
}
  
};
</script>

<style lang="scss">
.header {
  margin: 1rem 0;
  display: flex;
  justify-content: space-around;
  .logo_head {
    height: 50px;
  }
  .Dx_head {
    display: flex;
    flex-direction: row;
  }
  .link {
    margin-top: 1.2rem;
  }
  .search {
    padding: 1rem;
    margin-top: 3px;

    i {
      padding: 0 1rem;
    }
    i.fas.fa-shopping-cart {
      position: relative;
      z-index: 1;
    }
    .number {
      background-color: #377dff;
      color: white;
      width: fit-content;
      border-radius: 50%;
      position: absolute;
      right: 23.8%;
      top: 2.2%;
      transform: translate(50%, 25%);
      font-size: 12px;
      span {
        margin: 1px;
        vertical-align: sub;
      }
    }
  }
  .button {
    margin: 4px 0;
    .get_started {
      background-color: #377dff;
      color: white;
      border: none;
      padding: 1rem;
      border-radius: 5px;
    }
  }
}
</style>