<template>
	<div class="container">
	<div class="row">
		<div class="col-md-6 offset-md-3 content">
			<h2> Path to your development career </h2>
			<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
			tempor incididunt ut labore et dolore magna aliqua..</p>
		</div>
	</div>

	<h2>Course Catalog </h2> 
	<hr>
	<div class="row">
		<div class="col-md-3 courses">
			<img src="../assets/laptop.jpg" class="image-custom-x">
			<h5>Mobile Development</h5>
			<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
			tempor incididunt ut labore et dolore magna aliqua.</p>
		</div>
		<div class="col-md-4 courses">
			<img src="../assets/android-phone.jpg" class="image-custom-x">
			<h5>Web Development</h5>
			<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
			tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
			quis nostrud exercitation ullamco .</p>
		</div>
		<div class="col-md-3 courses">
			<img src="../assets/woman-learning.jpg" class="image-custom-x">
			<h5>Hybrid Development</h5>
			<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
			tempor incididunt ut labore et dolore magna aliqua.</p>
		</div>
	</div>
	
		<div class="courses-row">
			<div class="row">
			<!-- <h2>Getting Involved </h2> -->
			<div class="col-md-3 courses">
				<img src="../assets/laptop.jpg" class="image-custom-x">
				<h5>Programming</h5>
				<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
				tempor incididunt ut labore et dolore magna aliqua.</p>
			</div>
			<div class="col-md-4 courses">
				<img src="../assets/android-phone.jpg" class="image-custom-x">
				<h5>Graphics Design</h5>
				<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
				tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
				quis nostrud exercitation ullamco .</p>
			</div>
			<div class="col-md-3 courses">
				<img src="../assets/woman-learning.jpg" class="image-custom-x">
				<h5>UI/UX</h5>
				<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
				tempor incididunt ut labore et dolore magna aliqua.</p>
			</div>
		</div>
	</div>
	</div>
</template>

<script>
	
</script>

<style lang="scss">
	.content {
		padding-top: 100px;
		padding-bottom: 100px;
		p {
			text-align: center;
		}
	}

	.courses-row {
		margin-top: 30px;
	}

	h2 {
		font-family: 'Oswald', sans-serif;
		font-size: 2.2em;
		color: rgba(blue, 0.5);
		text-align: center;
		margin-bottom: 25px;
	}

	.image {
		width: 200px;
		max-width: 100%;
	}

	.image-custom-x {
		width: 100%;
		max-width: 100%;
		margin-bottom: 10px;
		border-radius: 10px;
	}

	.courses {
		// border: 1px solid #ccc;
		padding: 0px;
		margin-left: 45px;
		transition: .2s all;
		border-bottom: 4px solid transparent;
		p {
			padding: 5px;
			color: #666;
			font-weight: normal;
		}
		&:hover {
			opacity: .5;
			cursor: pointer;
			border-bottom: 4px solid rgba(blue, 0.6);
		}
	}
</style>