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
    <section class="content">
      <div class="container">
        <div class="Cont">
          <div class="Cont_Up">
            <div class="pc">
              <i class="fas fa-desktop"></i>
            </div>
            <div class="pc_text">
              <h3>Online Marketing</h3>
              <p>
                It is a long established fact that a reader will be distracted.
              </p>
            </div>
          </div>
          <div class="Cont_Down">
            <ul>
              <li><i class="fas fa-check"></i> SEO</li>
              <li><i class="fas fa-check"></i> SEM</li>
              <li><i class="fas fa-check"></i> Website Strategy</li>
              <li><i class="fas fa-check"></i> Social management</li>
            </ul>
          </div>
        </div>
        <div class="Cont">
          <div class="Cont_Up">
            <div class="pc">
              <i class="fas fa-desktop"></i>
            </div>
            <div class="pc_text">
              <h3>Online Marketing</h3>
              <p>
                It is a long established fact that a reader will be distracted.
              </p>
            </div>
          </div>
          <div class="Cont_Down">
            <ul>
              <li><i class="fas fa-check"></i> SEO</li>
              <li><i class="fas fa-check"></i> SEM</li>
              <li><i class="fas fa-check"></i> Website Strategy</li>
              <li><i class="fas fa-check"></i> Social management</li>
            </ul>
          </div>
        </div>
        <div class="Cont">
          <div class="Cont_Up">
            <div class="pc">
              <i class="fas fa-desktop"></i>
            </div>
            <div class="pc_text">
              <h3>Online Marketing</h3>
              <p>
                It is a long established fact that a reader will be distracted.
              </p>
            </div>
          </div>
          <div class="Cont_Down">
            <ul>
              <li><i class="fas fa-check"></i> SEO</li>
              <li><i class="fas fa-check"></i> SEM</li>
              <li><i class="fas fa-check"></i> Website Strategy</li>
              <li><i class="fas fa-check"></i> Social management</li>
            </ul>
          </div>
        </div>
      </div>
    </section>
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
  background-color: #f2f7ff;
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
.content {
  .container {
    display: flex;
    flex-direction: row;
    margin: 5rem;
    .Cont_Up {
      display: flex;
      flex-direction: row;
      .pc {
        .fa-desktop {
          padding: 0.7rem;
          background-color: #377dff;
          border: solid 7px white;
          border-radius: 50%;
          color: white;
          box-shadow: 0px 3px 8px #377dff;
          margin-right: 2.5rem;
        }
      }
      .pc_text{
        p{
          padding-top: 1rem;
          width: 80%;
          line-height: 30px;
        }
      }
    }
    .Cont_Down {
      ul {
        margin-left: 5rem;
        li {
          list-style: none;
          font-weight: bold;
          .fa-check {
            color: #377dff;
            margin: 1rem;
          }
        }
      }
    }
  }
}
</style>