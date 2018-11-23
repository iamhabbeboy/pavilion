<template>
	<div class="slider-holder">
		<div class="container">
			<div class="row">
				<div class="slider col-md-7">
					<h1>Learn, Practise &amp; Get Menthored</h1>
					<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
					tempor incididunt ut labore et dolore magna aliqua.Lorem ipsum dolor sit amet, consectetur adipisicing elit.</p>
				</div>
				<div class="col-md-4">
					<img src="../assets/slider-logo.webp" border="0" class="image-custom">
				</div>
			</div>
		</div>
	</div>
</template>

<script>
</script>

<style lang="scss">
	$white: #FFF;
	.slider-holder {
		background: linear-gradient( rgba(blue, 0.5),  rgba(blue, 0.7));
		background-repeat: no-repeat; 
		background-size: cover;
		padding-top: 100px;
		padding-bottom: 100px;
	}
	.slider {
		h1 {
			font-family: 'Oswald', sans-serif;
			color: rgba($white, 0.8);
			font-size: 4.2em;
		}
		p {
			color: #CCC;
			font-size: 14px;
			font-weight: normal;
			margin-top: 40px;
		}
	}
	.image-custom {
		opacity: 0.7;
		width: 100%;
		max-width: 900px;
	}
</style>