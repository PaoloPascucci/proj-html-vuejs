<template>
  <div class="main">
    <section class="hero">
      <div class="hero_text">
        <h1>The biggest platform for your growth.</h1>
        <p>
          There are many variation of passages of Lorem Ipsum available, but the
          majority have alteration in some form
        </p>
        <button class="get_started">Read More</button>
      </div>
      <div class="hero_image">
        <img src="../assets/508.jpeg" alt="" />
      </div>
    </section>
    <section></section>
    <section></section>
    <section></section>
    <section></section>
    <section></section>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss">
.hero {
  display: flex;
  flex-direction: row;
  background-color: #F2F7FF;
  height: 450px;
  .hero_text {
    display: flex;
    justify-content: center;
    margin-left: 4rem;
    flex-direction: column;
    h1 {
      font-size: 40px;
      width: 50%;
      line-height: 60px;
    }
    p {
      width: 55%;
      line-height: 30px;
    }
    button {
      margin-top: 2rem;
      padding: 1rem;
      background-color: #377dff;
      color: white;
      border: none;
      width: 100px;
      border-radius: 5px;
    }
  }
  .hero_image {
    position: relative;
    img {
      position: absolute;
      bottom: 165px;
      right: 0;
      transform: translate(50%, 50%);
    }
  }
}
</style>