<template>
	<div class="nav">	
		<b-container class="bv-example-row">
			<b-row>
				<b-col class="text-center" sm="12">
					<nuxt-link to="#"><img src="../assets/yong-logo.png" alt="Yong" id="logo"></nuxt-link>
					<nuxt-link to="#" id="nav-link">Snack Yard</nuxt-link>
					<nuxt-link to="#" id="nav-link">Frozen Products</nuxt-link>
				</b-col>
			</b-row>
		</b-container>
	</div>
</template>

<script>
	
</script>

<style>
	.nav{
		background-color: transparent;
	}
	#logo{
	    width:130px; 
	    padding-top: .5rem;
	}
	#nav-link{
		text-decoration: none !important;
		font-weight: 800;
		text-transform: uppercase;
		font-size: 1rem;
		color: #f7f7f7;
		border-radius: 6px;
		padding: 12px 15px 12px 15px;
		background-size: 300% 300%;
		color: white;
		margin-left: 10px;

		background-image: linear-gradient(to bottom right, #c6a530,#d6ae7b);
		background-position: top left;
		transition: .5s linear;
	}
	#nav-link:hover{
		color:black;
		background-position: right bottom;
	}
	@media (max-width: 415px){
		#logo{
		    width:100px; 
		    padding-top: .5rem;
		}
		#nav-link{
			text-decoration: none !important;
			font-weight: 500;
			text-transform: uppercase;
			font-size: .7rem;
			color: #f7f7f7;
			border-radius: 6px;
			padding: 5px 8px 5px 8px;
			background-size: 300% 300%;
			color: white;
			margin-left: 0px;

			background-image: linear-gradient(to bottom right, #c6a530,#d6ae7b);
			background-position: top left;
			transition: .5s linear;
		}
		#nav-link:hover{
			color:black;
			background-position: right bottom;
		}
	}
</style>