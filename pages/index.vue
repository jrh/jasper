<template>
  <section class="container">
    <div class="row justify-content-center mt-5">
      <img src="~/assets/images/jasper_title_sm.png">
    </div>
    <div class="row justify-content-center">
      <span id="header-title">CHINESE RESTAURANT & BAR</span>
    </div>
    <hr> 
    <div id="nav-container">
      <ul>
        <li><nuxt-link to="/">Home</nuxt-link></li>
        <li><nuxt-link to="/lunch">Luncheon Special</nuxt-link></li>
        <li><nuxt-link to="/menu">Menu</nuxt-link></li>
        <li><nuxt-link to="/map">Map / Directions</nuxt-link></li>
        <li><nuxt-link to="/contact">Contact Info</nuxt-link></li>
      </ul>
    </div>
    <hr style="margin-top: 35px;">
    <div>
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
    <div class="row justify-content-center">
      <em>"Jasper presents a unique style combining top-notch cuisine, service and surroundings</em> <small>&#9733;&#9733;&#9733;&frac12;</small><em>"</em><br>
      The Star-Ledger - October 3, 2004

    </div>
  </section>
</template>

<script>
export default {
}
</script>

<style scoped>

#header-title {
  font-weight: 100;
	color: #666;
	text-align: center;
	padding: 20px 0 10px 0;
	font-size: 16pt; /* 24pt; */
	font-family: "Garamond", "Georgia", "Times New Roman", "Times", serif;
	letter-spacing: 8px;
	position: relative;
}

#nav-container {
	margin: 0 auto;
	float: left;
	width: 900px;
	padding-top: 0px;
	font-size: 12pt;
	position: relative;
}

#nav-container ul {
	clear: left;
	float: left;
	list-style: none;
	margin: 0;
	padding: 0;
	left: 50%;
	position: relative;
	text-align: center;
	font-weight: 100;
}

#nav-container ul li {
	float: left;
	display: block;
	position: relative;
	padding: 0 3em;
	right: 50%
}
</style>
