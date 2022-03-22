<template>
  <div :class="['fixed-top scroll-transition', { 'bg-dark': scrolled }]">
    <nav class="navbar navbar-expand-lg navbar-dark">
      <div class="container position-relative">
        <div class="">
          <a class="navbar-brand" href="#"
            ><img src="../assets/img/logo.svg" alt=""
          /></a>
        </div>
        <button
          class="navbar-toggler border-0"
          type="button"
          data-bs-toggle="collapse"
          data-bs-target="#navbarSupportedContent"
          aria-controls="navbarSupportedContent"
          aria-expanded="false"
          aria-label="Toggle navigation"
        >
          <span class="navbar-toggler-icon"></span>
        </button>
        <div
          class="collapse navbar-collapse mobileNav"
          id="navbarSupportedContent"
        >


          <ul
            class="
              navbar-nav
              d-flex
              flex-column flex-lg-row
              align-items-center
              ms-auto
              mb-2 mb-lg-0
            "
          >

            <li class="nav-item py-2">
              <a class="nav-link grayish-blue" aria-current="page" href="#"
                >About</a
              >
            </li>
            <li class="nav-item py-2">
              <a class="nav-link grayish-blue px-sm-3" href="#">Services</a>
            </li>
            <li class="nav-item py-2">
              <a class="nav-link grayish-blue px-sm-3" href="#">Projects</a>
            </li>
            <li class="nav-item py-2 px-sm-3">
              <button class="contact-btn rounded-pill border-0 hover-light">
                <a
                  class="nav-link text-dark heading text-uppercase px-sm-3"
                  href="#"
                  >Contact</a
                >
              </button>
            </li>
          </ul>
        </div>
      </div>
    </nav>
  </div>
</template>

<script>
export default {
  name: "Navigation",

  data() {
    return {
      scrolled: false,
    };
  },

  mounted() {
    window.addEventListener("scroll", () => {
      this.scrolled = window.pageYOffset > 100;
    });
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>
@import "../assets/css/main.css";

.navbar-dark .navbar-nav a:nth-child(-n + 3) {
  color: #fff !important;
}

.navbar-dark .navbar-nav button .nav-link:last-child {
  color: #000 !important;
}

.scroll-transition {
  transition: background-color 0.5s ease-in-out;
}

@media screen and (max-width: 998px) {
  .navbar-dark .navbar-nav a:nth-child(-n + 3) {
    color: hsl(210, 4%, 67%) !important;
  }

  .contact-btn {
    padding-block: 0.4rem;
    padding-left: 2rem;
    padding-right: 2rem;
    background-color: hsl(51, 100%, 49%);
  }

  .navbar-collapse {
    position: absolute;
    top: 225%;
    width: 75%;
    margin-left: auto;
    margin-right: auto;
    left: 0;
    right: 0;
    background-color: #fff;
  }

  .mobileNav::after {
    content: "";
    position: absolute;
    bottom: 100%;
    right: 0;
    width: 0;
    height: 0;
    border-bottom: 25px solid white;
    border-left: 25px solid transparent;
  }
}

@media screen and (min-width: 998px) {
.navbar-dark .navbar-nav button a:nth-child(-n + 3):hover {
  color: #fff !important;
}
}
</style>
