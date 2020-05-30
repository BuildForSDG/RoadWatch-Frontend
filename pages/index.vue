<template>
  <div>
    <section class="section section-lg pt-lg-0 mt--200">
      <div class="container">
        <div class="row justify-content-center">
          <div class="col-lg-12">
            <div class="row row-grid">
              <div class="col-lg-12" style="text-align:center">
                <h2 class="text-primary text-uppercase text-center mt-4 mb-4">
                  Road Watch
                </h2>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <section class="section section-lg" style="margin-top: 15%">
      <div class="container">
        <div class="row row-grid justify-content-center">
          <div class="col-lg-6 text-center">
            <p class="lead" style="font-size:1.0rem">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
              eiusmod tempor incididunt sss ut labore et dolore magna aliquas
            </p>
          </div>
          <div class="col-lg-6 text-center mb-2">
            <img src="/ambulance.png" style=" width:270px" />
          </div>
        </div>
        <div
          class="btn-wrapper"
          style=" text-align: center;
           font-size: 20px;
    color: red;"
        >
          <nuxt-link
            to="/report"
            style=" 
           font-size: 20px;
    color: red;"
          >
            Report a Case</nuxt-link
          >
        </div>
      </div>
    </section>
  </div>
</template>

<script>
export default {
  data() {
    return {}
  }
}
</script>
