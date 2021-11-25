<template>
  <div class="header">
    <div class="Sx_head">
      <img class="logo_head" src="../assets/logo-2.png" alt="" />
    </div>
    <div class="Dx_head">
      <div class="link">
        <ul>
          <li><a href="#">Home</a></li>
          <li><a href="#">About Us</a></li>
          <li><a href="#">Feature</a></li>
          <li><a href="#">Testimonials</a></li>
          <li><a href="#">Contact Us</a></li>
        </ul>
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
export default {};
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
    ul {
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
  }
  .search {
    padding: 1rem;
    margin-top: 3px;

    i {
      padding: 0 1rem;
      .fa-shopping-cart {
          position: relative;
          z-index: 1;
      }
    }
    .number {
      background-color: rgb(55, 125, 255);
      color: white;
      width: fit-content;
      border-radius: 50%;
      padding: 0.1rem;
      position: absolute;
      right: 18.8%;
      top: 3.5%;
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
      background-color: rgb(55, 125, 255);
      color: white;
      border: none;
      padding: 1rem;
      border-radius: 5px;
    }
  }
}
</style>