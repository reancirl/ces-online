<template>
	<div class="p-menu">
		<div class="p-inner">
			<div class="p-image">
				<img :src="product.src" class="image" width="70%" style="border-radius: 5%;" />
			</div>
			<div class="p-detail">
				<h2 class="outline-3">{{ product.name }}</h2>
				<h5>For only ₱{{ product.price }}</h5>
				<p>{{ product.description }} | {{ product.availability }}</p>
			</div>
		</div>	
	</div>
</template>

<script>
	export default {
		props: ['product']
	}
</script>

<style>
	.p-menu{
		display: inline-block;
	    width: 50%;
	    padding: 25px;
	    text-align: center;
	    margin-top: 50px;
	}
	.p-inner{
		padding: 20px 0px 5px 0px;
		box-shadow: 0px 0px 16px rgba(0, 0, 0, 0.25);
		perspective: 1000px;
		border-radius: 15px;
		background-image: linear-gradient(#c6a530,#ffffff);
	}
	.p-image{
	    transform-origin: center;
	}
	.p-detail{
		margin: 10px 5px 20px 5px;
	}
	.p-detail p {
		font-size: 15px;
	    line-height: 1.5;
	    font-weight: 500;
	    color: #676767;
	}
	@media (max-width: 415px){
		.p-menu{
		    width: 100%;
		}
	}
</style>