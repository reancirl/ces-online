<template>
	<div class="contact">
		<h6 class="font--9 float-right">
			<font-awesome-icon class="mr-2 icon-1" :icon="['fab', 'facebook']"/> <font-awesome-icon class="mr-2 icon-1" :icon="['fab', 'twitter']"/> <font-awesome-icon class="mr-2 icon-1" :icon="['fab', 'instagram']"/> 
		</h6>
		<h6 class="font--9">
			© 2020 Yong Snack Yard & Frozen Products
		</h6>
		<h6 class="font--9" id="yong-name">
			Made with ❤ by <a href="https://reancirl.life" target="_blank">Reancirl Balaba</a> | All Rights Reserved
		</h6>
	</div>
</template>

<script>
	
</script>

<style>
	h6{
		font-size: .9rem;			
	}
	.contact{
		background-color: #c6a530;
		color: #f7f7f7;
		padding: 10px 15px 1px 15px;
	}
	.icon-1{
		font-size: 20px;
	}
	#yong-name{

	}
	@media (max-width: 415px){
		#yong-name {
			margin-top: 20px;
			text-align: center;
		}
	}
</style>