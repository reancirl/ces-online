<template>
	<div class="f-menu">
		<div class="f-inner">
			<div class="f-image">
				<img :src="fproduct.src" class="image" width="70%" style="border-radius: 5%;" />
			</div>
			<div class="f-detail">
				<h2 class="outline-4">{{ fproduct.name }}</h2>
				<h5>For only ₱{{ fproduct.price }}</h5>
				<p>{{ fproduct.description }} | {{ fproduct.min_order }}</p>
			</div>
		</div>	
	</div>
</template>

<script>
	export default {
		props: ['fproduct']
	}
</script>

<style>
	.f-menu{
		display: inline-block;
	    width: 50%;
	    padding: 25px;
	    text-align: center;
	    margin-top: 10px;
	}
	.f-inner{
		padding: 20px 0px 5px 0px;
		box-shadow: 0px 0px 16px rgba(0, 0, 0, 0.25);
		perspective: 1000px;
		border-radius: 15px;
		background-image: linear-gradient(#ffffff,#c6a530);
	}
	.f-image{
	    transform-origin: center;
	}
	.f-detail{
		margin: 10px 5px 20px 5px;
	}
	.f-detail h5 {
	    font-size: 20px;
	    line-height: 1.5;
	    font-weight: 400;
	    color: #ffffff;
	}
	.f-detail p {
		font-size: 15px;
	    line-height: 1.5;
	    font-weight: 500;
	    color: #ffffff;
	}
	@media (max-width: 415px){
		.f-menu{
		    width: 100%;
		}
	}
</style>