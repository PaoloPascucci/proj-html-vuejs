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
      <ul>
        <li class="first">Menu</li>
        <li>About us</li>
        <li>Theme</li>
        <li>Features</li>
        <li>Pricing</li>
        <li>Blog</li>
      </ul>
      <ul>
        <li class="first">About Us</li>
        <li>About Sofbox</li>
        <li>Roadmap</li>
        <li>How it Work</li>
        <li>Team</li>
        <li>News</li>
      </ul>
      <ul>
        <li class="first">Quick Links</li>
        <li>About us</li>
        <li>Theme</li>
        <li>Features</li>
        <li>Pricing</li>
        <li>Blog</li>
      </ul>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss">
.footer {
  display: flex;
  flex-direction: row;
  width: 85%;
  margin:auto;
}
.Sx_Footer {
    display:flex;
    flex-direction:column;
    justify-content: center;
    width: 350px;
    img{
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
      padding-top:1rem;
    a {
      text-decoration: none;
    }
  }
}
.Dx_Footer {
  display: flex;
  margin-left:8rem ;
  ul {
    margin :0 6rem 0 5rem;
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