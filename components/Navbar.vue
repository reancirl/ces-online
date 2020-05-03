<template>
	<div class="nav">	
		<b-container class="bv-example-row">
			<b-row>
				<b-col class="text-center" sm="12">
					<nuxt-link to="/"><img src="../assets/yong-logo.png" alt="Yong" id="logo"></nuxt-link>
					<b-button v-b-toggle.sidebar-1 id="nav-link">Snack Yard</b-button>
					<b-button v-b-toggle.sidebar-2 id="nav-link">Frozen Products</b-button>
				</b-col>
			</b-row>
		</b-container>
		<b-sidebar id="sidebar-1" title="Snack Yard" backdrop shadow>
	      <div class="px-3 py-2">
	        <nuxt-link to="/snackyard-menu" id="side-link">Snacks</nuxt-link>
	        <nuxt-link to="/shakes" id="side-link">Shakes&Drinks</nuxt-link>
	        <b-img src="../assets/food-1.jpg" fluid thumbnail class="mt-4"></b-img>
	        <h5 class="text-center pt-3"> You can visit us at Masilakon 2, Brgy. Poblacion, Lugait 9025 Misamis Oriental </h5>
	      </div>
	      <template v-slot:footer="{ hide }">
	       <div class="d-flex bg-dark text-light align-items-center px-3 py-2">
	        <strong class="mr-3"><font-awesome-icon :icon="['fab', 'facebook']"/></strong>
	        <strong class="mr-3"><font-awesome-icon :icon="['fab', 'instagram']"/></strong>
	        <strong class="ml-auto"><font-awesome-icon :icon="['fas', 'phone-alt']"/> +63 9488607427</strong>
	       </div>
	      </template>
	    </b-sidebar>
	    <b-sidebar id="sidebar-2" title="Frozen Products" backdrop shadow>
	      <div class="px-3 py-2">
	        <nuxt-link to="/frozen-products" id="side-link">Products</nuxt-link>
	        <nuxt-link to="#" id="side-link">UnAvailable</nuxt-link>
	        <b-img src="../assets/japan-1.jpg" fluid thumbnail class="mt-4"></b-img>
	        <h5 class="text-center pt-3">We do not offer any delivery service right now due to COVID19 Pandemic, Keep Safe and Godbless!</h5>
	      </div>
	      <template v-slot:footer="{ hide }">
	       <div class="d-flex bg-dark text-light align-items-center px-3 py-2">
	        <strong class="mr-3"><font-awesome-icon :icon="['fab', 'facebook']"/></strong>
	        <strong class="mr-3"><font-awesome-icon :icon="['fab', 'instagram']"/></strong>
	        <strong class="ml-auto"><font-awesome-icon :icon="['fas', 'phone-alt']"/> +63 9488607427</strong>
	       </div>
	      </template>
	    </b-sidebar>
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
	#side-link{
		text-decoration: none !important;
		font-weight: 700;
		text-transform: uppercase;
		font-size: 1rem;
		color: #f7f7f7;
		border-radius: 6px;
		padding: 10px 15px 10px 15px;
		background-size: 300% 300%;
		color: white;
		margin-left: 10px;

		background-image: linear-gradient(to bottom right, #c6a530,#d6ae7b);
		background-position: top left;
		transition: 2s linear;
	}
	#side-link:hover{
		color:black;
		background-position: right bottom;
	}
	#nav-link{
		text-decoration: none !important;
		font-weight: 700;
		text-transform: uppercase;
		font-size: 1rem;
		color: #f7f7f7;
		border-radius: 6px;
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