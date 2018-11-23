<template>
	<div class="extended-header">
		<div class="row links">
			<div class="col-md-4 text-center">
				<a href="#">Become Menthor</a>
			</div>
			<div class="col-md-4 text-center">
				<a href="#">Become Instructor</a>
			</div>
			<div class="col-md-4 text-center">
				<a href="#">Become Instructor</a>
			</div>
		</div>
	</div>
</template>

<script>
	export default {
		name: 'minheader'
	}
</script>

<style lang="scss">
	$blue: blue;
	.extended-header {
		padding: 50px;
		border-bottom: 1px solid #ccc;
	}

	.links {
		a {
			color: rgba(#333, 0.8);
			font-size: 14px;
		}
	}
</style>