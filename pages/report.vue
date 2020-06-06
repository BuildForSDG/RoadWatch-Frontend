<template>
  <div>
    <section class="section section-lg pt-lg-0 mt--200">
      <div class="container">
        <div class="row justify-content-center">
          <div class="col-lg-12">
            <div class="row row-grid">
              <div class="col-lg-3 mt-2" style="">
                <router-link to="/"
                  ><img src="/back.png" style="width:25px"
                /></router-link>
              </div>
              <div class="col-lg-8" style=""></div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <section>
      <p class=" m-3 text-center">
        Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod
        tempor incididunt ut labore et dolore magna aliqua.
      </p>
    </section>
    <section class="section section-lg" style="margin-top: 15%">
      <div class="container">
        <div class="row row-grid justify-content-center">
          <div class="col-lg-6 text-center mb-2">
           <image-upload></image-upload>
          </div>
        </div>
        <div
          class="btn-wrapper"
          style=" text-align: center;   font-size: 20px;     color: red;"  >
        </div>
      </div>
    </section>

    <section>
      <div class="row m-4">
        <div class="col-3 p-2">
          <img src="/imagesq.gif" style=" width:60px" />
        </div>
        <div class="col-3 p-2">
          <img src="/imagesq.gif" style=" width:60px" />
        </div>
        <div class="col-3 p-2">
          <img src="/imagesq.gif" style=" width:60px" />
        </div>
        <div class="col-3 p-2">
          <img src="/imagesq.gif" style=" width:60px" />
        </div>
      </div>
    </section>
    <section>
      <div class="form-group m-4">
        <label for="exampleFormControlSelect1">Accident Type </label>
        <select class="form-control" id="exampleFormControlSelect1">
          <option>.........</option>
          <option>.........</option>
        </select>
      </div>
    </section>

    <section>
      <div class="m-4">
        <button
          type="button"
          class="btn btn-outline-danger btn-lg btn-block"
          style="margin-right:20px" >
          <nuxt-link
            to="/submit"
            style=" 
           font-size: 20px;
          color: red;"
            >Submit
          </nuxt-link>
        </button>
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
