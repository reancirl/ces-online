<template>
	<div class="nav">	
		<b-container class="bv-example-row">
			<b-row>
				<b-col class="text-center" sm="12">
					<nuxt-link to="#"><img src="../assets/yong-logo.png" alt="Yong" id="logo"></nuxt-link>
					<b-button v-b-toggle.sidebar-1 id="nav-link">Snack Yard</b-button>
					<b-button v-b-toggle.sidebar-2 id="nav-link">Frozen Products</b-button>
				</b-col>
			</b-row>
		</b-container>
		<b-sidebar id="sidebar-1" title="Snack Yard" backdrop shadow>
	      <div class="px-3 py-2">
	        <p>
	          Cras mattis consectetur purus sit amet fermentum. Cras justo odio, dapibus ac facilisis
	          in, egestas eget quam. Morbi leo risus, porta ac consectetur ac, vestibulum at eros.
	        </p>
	        <b-img src="https://picsum.photos/500/500/?image=54" fluid thumbnail></b-img>
	      </div>
	      <template v-slot:footer="{ hide }">
	       <div class="d-flex bg-dark text-light align-items-center px-3 py-2">
	        <strong class="mr-auto">Footer</strong>
	       </div>
	      </template>
	    </b-sidebar>
	    <b-sidebar id="sidebar-2" title="Frozen Products" backdrop shadow>
	      <div class="px-3 py-2">
	        <p>
	          Cras mattis consectetur purus sit amet fermentum. Cras justo odio, dapibus ac facilisis
	          in, egestas eget quam. Morbi leo risus, porta ac consectetur ac, vestibulum at eros.
	        </p>
	        <b-img src="https://picsum.photos/500/500/?image=54" fluid thumbnail></b-img>
	      </div>
	      <template v-slot:footer="{ hide }">
	       <div class="d-flex bg-dark text-light align-items-center px-3 py-2">
	        <strong class="mr-auto">Footer</strong>
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
			font-size: .8rem;
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