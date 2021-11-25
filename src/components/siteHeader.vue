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
.header{
display: flex;
justify-content: space-around;    
    .logo_head {
      height: 50px;
    }
    .Dx_head{
        display: flex;
        flex-direction: row;
    }
    ul{
        display: flex;
        flex-direction: row;
        li{
            padding: 0 1rem 0 0;
            list-style: none;
            a{
                color: black;
                text-decoration: none;
                font-weight: bold;
            }
        }
    }
    .search{
    padding:1rem;
    i{
        padding:0 1rem;
    }
    }

    .get_started{
        background-color: rgb(55, 125, 255);
        color: white;
        border: none;
        padding: 1rem;
        border-radius: 5px;
    }
    }
</style>