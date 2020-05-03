<template>
	<div class="snack-menu">
	  	<div class="container">
			<h1 class="outline-2 text-center pt-5">Frozen Products List</h1>
			<FrozenProduct 
			v-for="fproduct in fproducts"
			:key="fproduct.name"
			:fproduct="fproduct"
			/>
	  	</div>
	</div>
</template>

<script>
	import FrozenProduct from "../components/FrozenProduct";  

	export default {
    components:{
      FrozenProduct
    },
    data() {
    	return {
    		fproducts: [
    			{
    				name: 'Mango Float',
    				description: 'Not Availble Currently',
    				price: '0',
    				min_order: '',
    				src: require('../assets/mangofloat-1.jpg')
    			},
    			{
    				name: 'Chicken Siomai',
    				description: 'Not Availble Currently',
    				price: '330',
    				min_order: '',
    				src: require('../assets/chicken-siomai-1.jpg')
    			},
    			{
    				name: 'Chocolate Cake',
    				description: 'Not Availble Currently',
    				price: '0',
    				min_order: '',
    				src: require('../assets/chococake-1.jpg')
    			},
    			{
    				name: 'Beef Siomai',
    				description: 'Not Availble Currently',
    				price: '0',
    				min_order: '',
    				src: require('../assets/beef-1.jpg')
    			},
    			{
    				name: 'Chicken Proven',
    				description: 'Not Availble Currently',
    				price: '0',
    				min_order: '',
    				src: require('../assets/proven-2.jpg')
    			},
    			{
    				name: 'Squid Rolls, Squid Balls & Tempura',
    				description: 'Not Availble Currently',
    				price: '0',
    				min_order: '',
    				src: require('../assets/squid-rolls-1.jpg')
    			},
    			{
    				name: 'Fries',
    				description: 'Not Availble Currently',
    				price: '0',
    				min_order: '',
    				src: require('../assets/fries-2.jpg')
    			},
                {
                    name: 'Mang Inasal Pecho',
                    description: 'Not Availble Currently',
                    price: '0',
                    min_order: '',
                    src: require('../assets/inasal-1.jpg')
                },
                {
                    name: 'Japanese Siomai',
                    description: 'Not Availble Currently',
                    price: '0',
                    min_order: '',
                    src: require('../assets/japan-1.jpg')
                },
    		]
    	}
    }
  }
</script>

<style>
</style>