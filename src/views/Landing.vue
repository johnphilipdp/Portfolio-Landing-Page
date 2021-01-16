<template>
  <div class="wrapper">
    <parallax class="section page-header header-filter" :style="headerStyle">
      <div class="container">
        <div class="md-layout">
          <div
            class="md-layout-item md-size-50 md-small-size-70 md-xsmall-size-100"
          >
            <h1 class="title">Hi, I am John</h1>
            <h4>A Freelance Web Developer</h4>
            <br />
            <a href="#about-me">
              <md-button class="md-primary md-accent">learn more</md-button>
            </a>
            <div class="social-tiles">
              <div>
                <a href="https://facebook.com/minecrafterme" target="_blank">
                  <img src="../assets/img/fb-logo.png" alt="facebook" />
                  <md-tooltip md-direction="bottom"
                    >add me on facebook 😁</md-tooltip
                  >
                </a>
              </div>
              <div>
                <a
                  href="https://www.youtube.com/channel/UCY3EuIvqfFYKWsCLS4Qfb3Q"
                  target="_blank"
                >
                  <img src="../assets/img/yt-logo.png" alt="youtube" />
                  <md-tooltip md-direction="bottom"
                    >i also do tutorials 👨‍🏫</md-tooltip
                  >
                </a>
              </div>
              <div>
                <a
                  href="https://www.linkedin.com/in/john-philip-parungao-a04374137/"
                  target="_blank"
                >
                  <img src="../assets/img/linked-logo.png" alt="linkedin" />
                  <md-tooltip md-direction="bottom"
                    >let's connect 💼</md-tooltip
                  >
                </a>
              </div>
            </div>
          </div>
          <div
            class="md-layout-item md-size-50 md-small-size-70 md-xsmall-size-100"
          >
            <img src="../assets/img/header_right.svg" alt />
          </div>
        </div>
      </div>
    </parallax>
    <div class="main main-raised">
      <div class="section" id="about-me">
        <div class="container">
          <div class="md-layout">
            <div
              class="md-layout-item md-size-50 md-small-size-70 md-xsmall-size-100"
            >
              <img src="../assets/img/table_desk.svg" alt />
            </div>
            <div
              class="md-layout-item md-size-50 md-small-size-70 md-xsmall-size-100"
            >
              <h2 class="title text-left">About Me</h2>
              <h5 class="description">
                My name is John Parungao, others call me JP.
                <br />I have been in the tech industry for more than 4 years as
                a web developer and stuffs with graphics design. <br />In
                constant search for the meaning of our fragile existence. jk.
                <br />I doubt we'll ever find the reason behind that, same goes
                with the incomprehensible, extreme increase development of
                javascript frameworks.haha. Dad joke unlocked right there.
                <br />By the way I am also a father of a little boy with a
                beautiful wife. 🤩
              </h5>

              <a href="#my-works">
                <md-button class="md-primary md-accent"
                  >check out my works!</md-button
                >
              </a>
            </div>
          </div>
        </div>
      </div>

      <div class="section text-center" id="work-history">
        <div class="container">
          <h2 class="title">Companies I have worked with</h2>
          <infinite-slide duration="25s">
            <div class="display: flex;align-items: center">
              <img src="../assets/img/slide_1.png" alt />
              <img src="../assets/img/slide_2.png" alt />
              <img src="../assets/img/slide_3.png" alt />
              <img src="../assets/img/slide_4.png" alt />
              <img src="../assets/img/slide_5.png" alt />
            </div>
          </infinite-slide>
        </div>
      </div>
      <div
        id="my-works"
        class="section text-center"
        style="background-color: #262534"
      >
        <div class="container md-primary">
          <div class="features text-center">
            <h2 class="title">Checkout Some of My Works!</h2>
            <div class="md-layout">
              <div class="md-layout-item md-medium-size-33 md-small-size-100">
                <div class="info">
                  <img src="../assets/img/project_2.png" alt />
                  <h4 class="info-title">Angular Landing Page</h4>
                  <p>Travel agency landing page</p>
                  <a
                    href="https://johnphilipdp.github.io/Angular-routing-landing-page/#/"
                    target="_blank"
                  >
                    <md-button class="md-accent md-primary">View</md-button>
                  </a>
                </div>
              </div>
              <div class="md-layout-item md-medium-size-33 md-small-size-100">
                <div class="info">
                  <img src="../assets/img/project_1.png" alt />
                  <h4 class="info-title">Client Panel with admin dashboard</h4>
                  <p>
                    Allows the user to login or create an account using
                    FireBase. With admin dashboard to process existing datas,
                    such as create/update/delete.
                  </p>
                  <a
                    href="https://clientpanelprod-da72a.firebaseapp.com/login"
                    target="_blank"
                  >
                    <md-button class="md-accent md-primary">View</md-button>
                  </a>
                </div>
              </div>
              <div class="md-layout-item md-medium-size-33 md-small-size-100">
                <div class="info">
                  <img src="../assets/img/project_3.png" alt />
                  <h4 class="info-title">Budget Calculator</h4>
                  <p>Vanilla Javascript budget calculator</p>
                  <a
                    href="https://johnphilipdp.github.io/budget-calc/"
                    target="_blank"
                  >
                    <md-button class="md-accent md-primary">View</md-button>
                  </a>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="section section-contacts" id="contact-me">
        <div class="container">
          <div class="md-layout">
            <div
              class="md-layout-item md-size-50 md-small-size-70 md-xsmall-size-100"
            >
              <h2 class="text-center title">Let's Talk!</h2>
              <h4 class="text-center description"></h4>
              <ul class="info_list">
                <li>
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    class="icon icon-tabler icon-tabler-mail"
                    width="44"
                    height="44"
                    viewBox="0 0 24 24"
                    stroke-width="1.5"
                    stroke="#262534"
                    fill="none"
                    stroke-linecap="round"
                    stroke-linejoin="round"
                  >
                    <path stroke="none" d="M0 0h24v24H0z" fill="none" />
                    <rect x="3" y="5" width="18" height="14" rx="2" />
                    <polyline points="3 7 12 13 21 7" />
                  </svg>
                  nhojparungao@gmail.com
                </li>
                <li>
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    class="icon icon-tabler icon-tabler-phone"
                    width="44"
                    height="44"
                    viewBox="0 0 24 24"
                    stroke-width="1.5"
                    stroke="#262534"
                    fill="none"
                    stroke-linecap="round"
                    stroke-linejoin="round"
                  >
                    <path stroke="none" d="M0 0h24v24H0z" fill="none" />
                    <path
                      d="M5 4h4l2 5l-2.5 1.5a11 11 0 0 0 5 5l1.5 -2.5l5 2v4a2 2 0 0 1 -2 2a16 16 0 0 1 -15 -15a2 2 0 0 1 2 -2"
                    />
                  </svg>
                  +639958955431
                </li>
              </ul>
            </div>
            <div
              class="md-layout-item md-size-50 md-small-size-70 md-xsmall-size-100"
            >
              <img src="../assets/img/hire_me.svg" alt />
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import InfiniteSlideBar from "vue-infinite-slide-bar";
export default {
  components: {
    "infinite-slide": InfiniteSlideBar,
  },
  bodyClass: "landing-page",
  props: {
    header: {
      type: String,
      default: require("@/assets/img/bg7.jpg"),
    },
    teamImg1: {
      type: String,
      default: require("@/assets/img/faces/avatar.jpg"),
    },
    teamImg2: {
      type: String,
      default: require("@/assets/img/faces/christian.jpg"),
    },
    teamImg3: {
      type: String,
      default: require("@/assets/img/faces/kendall.jpg"),
    },
  },
  data() {
    return {
      name: null,
      email: null,
      message: null,
    };
  },
  computed: {
    headerStyle() {
      return {
        backgroundColor: "#2f2e41",
      };
    },
  },
};
</script>

<style lang="scss" scoped>
.info_list {
  li {
    display: flex;
    align-items: center;
  }
  svg {
    margin-right: 10px;
  }
}
.social-tiles {
  display: flex;
  margin-top: 2rem;
  div {
    background: #fff;
    padding: 6px 12px;
    border-radius: 3px;
    box-shadow: 0px 1px 14px black;
    margin-right: 25px;
    img {
      width: 15px;
    }
  }
}
.features {
  h2,
  h4,
  p {
    color: #e2e2e2 !important;
  }
  img {
    filter: grayscale(100%);
  }
}

.md-card-actions.text-center {
  display: flex;
  justify-content: center !important;
}
.contact-form {
  margin-top: 30px;
}

.md-has-textarea + .md-layout {
  margin-top: 15px;
}
</style>
