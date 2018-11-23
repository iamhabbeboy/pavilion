<template>

	<div class="header">
	<!-- 	<video autoplay muted loop id="myVideo">
		  <source src="https://www.w3schools.com/howto/rain.mp4" type="video/mp4">
		</video> -->
		
		<div class="container">
			<nav class="navbar navbar-expand-lg navbar-light bg-light">
			  <a class="navbar-brand" href="#">LOGO</a>
			  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
			    <span class="navbar-toggler-icon"></span>
			  </button>
			  <div class="collapse navbar-collapse " id="navbarNav">
			    <ul class="navbar-nav ml-auto">
			      <li class="nav-item active">
			        <a class="nav-link" href="#">Home <span class="sr-only">(current)</span></a>
			      </li>
			      <li class="nav-item">
			        <a class="nav-link" href="#">Features</a>
			      </li>
			      <li class="nav-item">
			        <a class="nav-link" href="#">Pricing</a>
			      </li>
			      <li class="nav-item">
			        <a class="nav-link" href="#">Courses</a>
			      </li>
			      <li class="nav-item">
			        <a class="nav-link" href="#">Sign Up</a>
			      </li>
			    </ul>
			  </div>
			</nav>
		</div>
		<Slider />
	</div>
</template>

<script>
	import Slider from './Slider.vue'

	export default {
	  name: 'Header',
	  components: {
	    Slider,
	  }
}
</script>

<style lang="scss">
$white: #FFF;
$orange: rgba(blue, 0.6);
.header {
	background-color: transparent; 
}

// #myVideo {
//     position: fixed;
//     right: 0;
//     bottom: 0;
//     min-width: 100%; 
//     min-height: 100%;
// }


.bg-light {
	background-color: transparent !important;
}

.navbar-light .navbar-nav .active>.nav-link, .navbar-light .navbar-nav .nav-link.active, .navbar-light .navbar-nav .nav-link.show, .navbar-light .navbar-nav .show>.nav-link {
	color: $white;
}


.navbar-light .navbar-brand {
	color: $orange;
}

.navbar-light .navbar-nav .nav-link {
	color: $orange;
	padding: 20px;
	transition: .2s all;
	&:hover {
		color: #999;
	}
}

.navbar-light .navbar-toggler {
	border-color: $white;
	color: $white;
}

.navbar-light .navbar-toggler-icon {
	// background-image: url("data:image/svg+xml;charset=utf8,%3Csvg viewBox='0 0 30 30' xmlns='http://www.w3.org/2000/svg'%3E%3Cpath stroke='red");
}


</style>