<template>
	<div class="snack-menu">
	  	<div class="container">
			<h1 class="outline-2 text-center pt-5">Shakes & Drinks Menu</h1>
			<Shakes 
			v-for="shake in shakes"
			:key="shakes"
			:shake="shake"
			/>
	  	</div>
	</div>
</template>

<script>
	import Shakes from "../components/Shakes";  

	export default {
    components:{
      Shakes
    },
    data() {
    	return {
    		shakes: [
    			{
    				name: 'Mango',
    				price: '30',
    				src: require('../assets/mango-1.jpg')
    			},
    			{
    				name: 'Choco Kisses',
    				price: '30',
    				src: require('../assets/choco-kisses-1.jpg')
    			},
    			{
    				name: 'Buko Pandan',
    				price: '30',
    				src: require('../assets/bukopandan-1.jpg')
    			},
    		]
    	}
    }
  }
</script>

<style>
	.shakes{
	}
</style>