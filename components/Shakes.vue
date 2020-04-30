<template>
	<div class="s-menu">
		<div class="s-inner">
			<div class="s-image">
				<img :src="shake.src" class="image" width="70%" style="border-radius: 5%;" />
			</div>
			<div class="s-detail">
				<h2 class="outline-4">{{ shake.name }}</h2>
				<h5>For only ₱{{ shake.price }}</h5>
			</div>
		</div>	
	</div>
</template>

<script>
	export default {
		props: ['shake']
	}
</script>

<style>
	.s-menu{
		display: inline-block;
	    width: 50%;
	    padding: 25px;
	    text-align: center;
	    margin-top: 50px;
	}
	.s-inner{
		padding: 20px 0px 5px 0px;
		box-shadow: 0px 0px 16px rgba(0, 0, 0, 0.25);
		perspective: 1000px;
		border-radius: 15px;
		background-image: linear-gradient(#ffffff,#c6a530);
	}
	.s-image{
	    transform-origin: center;
	}
	.s-detail{
		margin: 10px 5px 20px 5px;
	}
	.s-detail h5 {
		font-size: 20px;
	    line-height: 1.5;
	    font-weight: 400;
	    color: #ffffff;
	}
	@media (max-width: 415px){
		.s-menu{
		    width: 100%;
		}
	}
</style>