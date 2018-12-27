<template>
  <div>
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
    <hr>
  </div>
</template>

<script>
export default {
  name: 'Header'
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
	font-size: 12pt;
}

#nav-container ul {
	list-style: none;
	margin: 0;
	padding: 0;
	text-align: center;
	font-weight: 100;
}

#nav-container ul li {
  display: inline-block;
	padding: 0 3em;
}

.nuxt-link-exact-active {
  text-decoration: underline;
  font-weight: 500;
}

hr {
  margin: 10px;
}
</style>

