<template>
  <div class="index">
  	<div class="main">
		<div class="container-main">
			<h1 class="outline-1">What you crave?</h1>
		</div>
  	</div>
		<div id="hours">
			<h1 class="outline-2 text-center mt-3">Business Hours</h1>
			<div class="container pt-3">
				<b-row>
					<b-col sm="6"><img src="../assets/hamburger-1.svg" style="width:90%;"></b-col>
					<b-col sm="6">
						<h4></h4>
					</b-col>
				</b-row>
			</div>
		</div>
  </div>
</template>

<script>

  export default {
    components:{

    }
  }
</script>

<style>
	.main{
		margin: 1rem 0px 0px 0px;
		padding:0px 0px;
		height: 100%;
		background-image: url('../assets/kikkiam.jpg');		
		background-size: cover;
		background-position: center;
		height: 50vh;
		padding:2rem 10px;
		margin-bottom: 1.5rem;
	}
	.container-main{
	 	background-color:rgba(0,0,0,0.25);
	 	text-align: center;
	  	border-radius: 10px;
	 	box-shadow: 3px 6px rgba(255,255,255,0.25);
		padding: 10px 10px;
		margin-right: 4rem;
		margin-left: 4rem;
	}
	.outline-1 {
		font-size: 3rem;
		font-weight: 900;
		color: #c6a530 !important;
		-webkit-text-stroke:1.5px #fff;
	}
	.outline-2 {
		font-size: 3rem;		
		font-weight: 900;
		color: #c6a530 !important;
		-webkit-text-stroke:1.5px #fff;
	}
	@media (max-width: 415px){
		.outline-1 {
			font-size: 2rem;
		}
		.container-main{
			margin-right: 0rem;
			margin-left: 0rem;
		}
	}
</style>
