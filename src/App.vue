<template>
  <div class="wrapper overflow-hidden">
    <Navigation />
    <div class="row g-0 position-relative heading text-uppercase text-white">
      <div class="col p-0">
        <img
          class="img-fluid d-md-none"
          src="./assets/img/mobile/image-header.jpg"
          alt=""
        />
          <img
          class="img-fluid d-none d-md-block"
          src="./assets/img/desktop/image-header.jpg"
          alt=""
        />
      <h1 class="position-absolute hero-title"> We are creatives</h1>
      </div>
    </div>
    <div class="row g-0">
      <div class="col-md-6 p-0 order-md-1">
        <img
          class="d-md-none"
          src="./assets/img/mobile/image-transform.jpg"
          alt=""
        />
          <img
          class="w-100 d-none d-md-block"
          src="./assets/img/desktop/image-transform.jpg"
          alt=""
        />
      </div>
      <div class="col-md-6 d-md-flex align-items-md-center">
        <div class="d-flex flex-column align-items-center align-items-sm-start p-5">
          <h2 class="heading text-md-start fw-900">Transform your brand</h2>
          <p class="text-center text-md-start py-4 grayish-blue">
            We are a full-service creative agency specializing in helping brands
            grow fast. Engage your clients through compelling visuals that do
            most of the marketing for you.
          </p>
          <a href="#" class="heading text-decoration-none text-uppercase text-dark">Learn More</a>
        </div>
      </div>
    </div>
    <div class="row g-0">
      <div class="image-header col-md-6 p-md-0">
        <img
          class="img-fluid d-md-none"
          src="./assets/img/mobile/image-stand-out.jpg"
          alt=""
        />
        <img
          class="img-fluid w-100 d-none d-md-block"
          src="./assets/img/desktop/image-stand-out.jpg"
          alt=""
        />
      </div>
      <div class="col-md-6 d-md-flex align-items-md-center">
        <div class="d-flex flex-column align-items-center align-items-sm-start p-5">
          <h2 class="heading  text-md-start fw-900">Stand out to the right audience</h2>
          <p class="text-center text-md-start py-4 grayish-blue">
            Using a collaborative formula of designers, researchers,
            photographers, videographers, and copywriters, we’ll build and
            extend your brand in digital places.
          </p>
          <a href="#" class="text-decoration-none">Learn More</a>
        </div>
      </div>
    </div>
    <div class="row g-0">
      <div class="card text-white border-0 col-md-6 p-md-0">
        <img
          src="./assets/img/mobile/image-graphic-design.jpg"
          class="card-img d-md-none"
          alt="..."
        />
        <img
          src="./assets/img/desktop/image-graphic-design.jpg"
          class="card-img d-none d-md-block"
          alt="..."
        />
        <div
          class="
            card-img-overlay
            d-flex
            flex-column
            align-items-center
            justify-content-end
            p-4
            dark-desaturated-cyan
          "
        >
          <h1 class="card-title heading fw-900">Graphic design</h1>
          <p class="card-text text-center p-3">
            Great design makes you memorable. We deliver artwork that
            underscores your brand message and captures potential clients’
            attention.
          </p>
        </div>
      </div>
      <div class="card text-white border-0 col-md-6 p-md-0">
        <img
          src="./assets/img/mobile/image-photography.jpg"
          class="card-img d-md-none"
          alt="..."
        />
        <img
          src="./assets/img/desktop/image-photography.jpg"
          class="card-img d-none d-md-block"
          alt="..."
        />
        <div
          class="
            card-img-overlay
            d-flex
            flex-column
            align-items-center
            justify-content-end
            p-4
            dark-blue
          "
        >
          <h1 class="card-title heading fw-900">Photography</h1>
          <p class="card-text text-center p-3">
            Increase your credibility by getting the most stunning, high-quality
            photos that improve your business image.
          </p>
        </div>
      </div>
    </div>
    <div class="container py-7 g-0">
        <h3 class="text-uppercase text-center heading grayish-blue">client testimonials</h3>
      <div class="row py-5">
        <div class="col-md-4 d-flex flex-column justify-content-center">
          <div class="profile-circle">
            <img class="img-fluid" src="./assets/img/image-emily.jpg" alt="" />
          </div>
          <div class="d-flex flex-column align-items-center pt-4">
            <p class="text-center p-3">
              We put our trust in Sunnyside and they delivered, making sure our
              needs were met and deadlines were always hit.
            </p>
            <h3 class="heading fw-900">Emily R.</h3>
            <span class="grayish-blue">Marketing Director</span>
          </div>
        </div>
        <div class="col-md-4 d-flex flex-column justify-content-center pt-4">
          <div class="profile-circle">
            <img class="img-fluid" src="./assets/img/image-thomas.jpg" alt="" />
          </div>
          <div class="d-flex flex-column align-items-center">
            <p class="text-center p-3">
              Sunnyside’s enthusiasm coupled with their keen interest in our
              brand’s success made it a satisfying and enjoyable experience.
            </p>
            <h3 class="heading fw-900">Thomas S.</h3>
            <span class="grayish-blue heading-barlow">Chief Operating Officer</span>
          </div>
        </div>
        <div class="col-md-4 d-flex flex-column justify-content-center pt-4">
          <div class="profile-circle">
            <img class="img-fluid" src="./assets/img/image-jennie.jpg" alt="" />
          </div>
          <div class="d-flex flex-column align-items-center">
            <p class="text-center p-3">
              Incredible end result! Our sales increased over 400% when we worked
              with Sunnyside. Highly recommended!
            </p>
            <h3 class="heading fw-900">Jennie F.</h3>
            <span class="grayish-blue">Business Owner</span>
          </div>
        </div>
      </div>
    </div>
    <div class="row h-100 g-0">
      <div class="col-6 col-md-3 p-0">
        <img class="img-fluid" src="./assets/img/mobile/image-gallery-milkbottles.jpg" alt="" />
      </div>
      <div class="col-6 col-md-3 p-0">
        <img class="img-fluid" src="./assets/img/mobile/image-gallery-orange.jpg" alt="" />
      </div>
      <div class="col-6 col-md-3 p-0">
        <img class="img-fluid" src="./assets/img/mobile/image-gallery-cone.jpg" alt="" />
      </div>
      <div class="col-6 col-md-3 p-0">
        <img class="img-fluid" src="./assets/img/mobile/image-gallery-sugar-cubes.jpg" alt="" />
      </div>
    </div>
    <footer class="py-4 bg-dark-moderate-cyan d-flex align-items-center flex-column">
      <h1 class="text-center text-decoration-none pt-4 pb-2 fw-900 dark-desaturated-cyan">sunnyside</h1>
      <ul class="d-flex list-unstyled dark-desaturated-cyan">
        <li class="px-2">About</li>
        <li class="px-2">Services</li>
        <li class="px-2">Projects</li>
      </ul>
      <div class="d-flex justify-content-center">
        <div class="col-4 mx-1 p-0">
        <img class="img-fluid mx-auto" src="./assets/img/icon-facebook.svg" alt="" />
      </div>
        <div class="col-4 mx-1 p-0">
        <img class="img-fluid" src="./assets/img/icon-instagram.svg" alt="" />
      </div>
        <div class="col-4 mx-1  p-0">
        <img class="img-fluid " src="./assets/img/icon-twitter.svg" alt="" />
      </div>
        <div class="col-4 mx-1 p-0">
        <img class="mx-auto" src="./assets/img/icon-pinterest.svg" alt="" />
      </div>
      </div>
    </footer>
  </div>
</template>

<script>
import Navigation from "./components/Navigation.vue";

export default {
  name: "App",
  components: {
    Navigation,
  },
};
</script>

<style>
</style>
