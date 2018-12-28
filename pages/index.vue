<template>
  <section class="pt-3">
    <div class="row justify-content-center">
      <div id="carousel-container">
        <b-carousel
          controls
          indicators
          img-width="640"
          img-height="480"
        >
          <b-carousel-slide img-src="~/assets/images/partyroom.jpg"></b-carousel-slide>
          <b-carousel-slide img-src="~/assets/images/lobster.jpg"></b-carousel-slide>
          <b-carousel-slide img-src="~/assets/images/sign.jpg"></b-carousel-slide>
          <b-carousel-slide img-src="~/assets/images/lion.jpg"></b-carousel-slide>
        </b-carousel>
      </div>
    </div>
    <div class="row justify-content-center align-items-center mt-5">
      <em>"Jasper presents a unique style combining top-notch cuisine, service and surroundings</em> <small class="pl-3">&#9733;&#9733;&#9733;&frac12;</small><em>"</em>
    </div>
    <div class="row justify-content-center mt-3">
      <span>The Star-Ledger - October 3, 2004</span>
    </div>
  </section>
</template>

<script>
export default {
  name: 'index'
}
</script>

<style scoped>
#carousel-container {
  width: 640px;
  height: 480px;
}
</style>

