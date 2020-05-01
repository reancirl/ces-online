<template>
  <div class="index">
  	<div class="main">
		<div class="container-main">
			<h1 class="outline-1">Take a bite and Enjoy the moment!</h1>
		</div>
  	</div>
	<div id="hours">
		<h1 class="outline-2 text-center mt-3">Business Hours and Scope</h1>
		<div class="container pt-5">
			<b-row>
				<b-col sm="6"><img src="../assets/hamburger-1.svg" style="width:90%;"></b-col>
				<b-col sm="6" class="text-center">
					<h4><span class="day-1">Monday - Saturday :</span> </h4>
					<h4>(8:00 am - 8:00pm)</h4>
					<h4><span class="day-1">Sunday :</span></h4>
					<h4>(2:00 pm - 6:00 pm)</h4>
					<h4><span class="day-1">Delivery range :</span></h4>
					<h4> Within Poblacion, Iligan City - Manticao, Misamis Oriental</h4>
				</b-col>
			</b-row>
		</div>
	</div>
	<div id="about">
		<h1 class="outline-2 text-center mt-5">What we offer</h1>
		<div class="container pt-3">
			<b-row>
				<b-col sm="6" class="pt-4 pb-4">
					<h5 class="pt-2"> <span class="highlight-1">We offer</span> a variety of snack products from classic streetfoods like tempura and Chicken Proven to Siopao, Siomai and Burgers to name a few.</h5>
					<h5 class="pt-2"> We also offer <span class="highlight-1">Delivery Service</span> for bulk purchase of our frozen products.</h5>
				</b-col>
				<b-col sm="6"><img src="../assets/shopping-1.svg" style="width:90%;"></b-col>
			</b-row>
		</div>
	</div>
  </div>
</template>

<script>
export default {
  data () {
    return {
      title: 'Yong Snack Yard & Frozen Products'
    }
  },
  head () {
    return {
      title: this.title,
      meta: [
        { hid: 'description', name: 'description', content: 'Giving Lugait a place to sit, talk, and have a great food!' }
      ]
    }
  }
}
</script>

<style>
	.main{
		margin: 1rem 0px 0px 0px;
		padding:0px 0px;
		height: 100%;
		background-image: url('../assets/kikkiam-1.jpg');		
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
		-webkit-text-stroke:1.7px black;
	}
	.outline-3 {
		font-size: 2rem;		
		font-weight: 900;
		color: #c6a530 !important;
		-webkit-text-stroke:1.7px black;
	}
	.outline-4 {
		font-size: 2rem;		
		font-weight: 900;
		color: #c6a530 !important;
		-webkit-text-stroke:.7px #ffffff;
	}
	.day-1{
		font-size: 1.5rem;
		color:#c6a530;
		font-weight: 700;
		-webkit-text-stroke:.5px black;
	}
	.highlight-1{
		font-size: 1.3rem;
		color:#c6a530;
		font-weight: 700;
		-webkit-text-stroke:.5px black;
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
