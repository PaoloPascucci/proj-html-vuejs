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
        <img src="../assets/27-1.png" alt="" />
      </div>
    </section>
    <section class="content">
      <div class="container">
        <div class="Cont">
          <div class="Cont_Up">
            <div class="pc">
              <img src="../assets/24.png" alt="" />
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
              <img src="../assets/24.png" alt="" />
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
              <img src="../assets/24.png" alt="" />
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
    <section class="tips_tricks">
      <div class="tricks">
        <div class="sx">
          <h3>Get tips tricks on how to skyrocket your sales.</h3>
          <p class="weird">
            Faff about only a quid blower i don't want no agro bleeding chimney
            pot burke tosser cras nice boot fanny.!
          </p>

          <div class="card Report">
            <div class="img">
              <img src="../assets/510.png" alt="" />
            </div>
            <div class="text">
              <h4 class="title1">Reporting Analysis</h4>
              <p>
                It is a long established fact that a reader will be distracted
                by the readable content of a page when looking at its layout.
              </p>
            </div>
          </div>
          <div class="card">
            <div class="img">
              <img src="../assets/511.png" alt="" />
            </div>
            <div class="text">
              <h4 class="title2">Technicval SEO Audit</h4>
              <p>
                It is a long established fact that a reader will be distracted
                by the readable content of a page when looking at its layout.
              </p>
            </div>
          </div>
        </div>
        <div class="dx">
          <img src="../assets/509.jpeg" alt="" />
        </div>
      </div>
    </section>
    <section class="features">
      <div class="container2">
        <div class="f_text">
          <div class="_text">
            <h3>Populare features that oyur business needs</h3>
            <p>
              Faff about only a quid blower i don't want no agro bleeding
              chimney pot burke tosser cras nice boot fanny.!
            </p>
          </div>
          <button class="Explore">Explore more Feature</button>
        </div>
        <div class="f_info">
          <div class="card">Customized Invoices <i class="flaticon flaticon-growth"></i> </div>
          <div class="card">Stock Management</div>
          <div class="card">Receivable e Payables</div>
          <div class="card">Manage Buying</div>
          <div class="card">Powerful e Secure</div>
          <div class="card">Fastest Return Filing</div>
          <div class="card">Monthly Detailed</div>
          <div class="card">Product Management</div>
        </div>
      </div>
    </section>
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
  margin-top: 10rem;
  .container {
    display: flex;
    flex-direction: row;
    margin: 5rem;
    .Cont_Up {
      display: flex;
      flex-direction: row;
      .pc {
        img {
          height: 80px;
        }
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
      .pc_text {
        p {
          padding-top: 1rem;
          width: 80%;
          line-height: 30px;
          color: #8e989f;
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
.tips_tricks {
  .tricks {
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: center;

    .sx {
      display: flex;
      flex-direction: column;
      width: 41%;
      margin-right: 1rem;
      h3 {
        width: 70%;
        font-size: 30px;
        line-height: 60px;
      }
      .weird {
        line-height: 30px;
      }
      .card {
        display: flex;
        flex-direction: row;
        padding: 1rem;
        p {
          line-height: 35px;
        }
        .img {
          margin-right: 1rem;
          display: flex;
          justify-content: center;
          align-items: center;

          img {
            width: 70px;
            height: 79px;
          }
        }
      }
      .Report {
        margin-top: 1rem;
        box-shadow: 18px 18px 50px #00000014;
      }
    }
    .dx {
      margin-top: 1px;
    }
  }
}
.features {
  width: 80%;
  margin: auto;
  .f_text {
    display: flex;
    ._text {
      p {
        width: 65%;
        line-height: 30px;
      }
    }
    .Explore {
      color: white;
      background-color: #377dff;
      border: none;
      border-radius: 5px;
      padding: 0 1rem;
      height: 50px;
    }
  }
  .f_info {
    display: flex;
    flex-wrap: wrap;
    width: 70%;
    flex-direction: row;
    .card {
      margin: 1rem;
    }
  }
}
</style>