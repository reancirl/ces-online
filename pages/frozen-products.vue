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
    				description: 'Lorem Ipsum Durom',
    				price: '0',
    				min_order: 'Minumum order Required',
    				src: require('../assets/mangofloat-1.jpg')
    			},
    			{
    				name: 'Chicken Siomai',
    				description: 'Lorem Ipsum Durom',
    				price: '0',
    				min_order: 'Minumum order Required',
    				src: require('../assets/chicken-siomai-1.jpg')
    			},
    			{
    				name: 'Chocolate Cake',
    				description: 'Lorem Ipsum',
    				price: '0',
    				min_order: 'Lorem Ipsum Durom',
    				src: require('../assets/chococake-1.jpg')
    			},
    			{
    				name: 'Beef Siomai',
    				description: 'Lorem Ipsum Durom',
    				price: '0',
    				min_order: 'Minumum order Required',
    				src: require('../assets/beef-1.jpg')
    			},
    			{
    				name: 'Chicken Proven',
    				description: 'Lorem Ipsum',
    				price: '0',
    				min_order: 'Lorem Ipsum Durom',
    				src: require('../assets/proven-2.jpg')
    			},
    			{
    				name: 'Squid Rolls, Squid Balls & Tempura',
    				description: 'Lorem Ipsum Durom',
    				price: '0',
    				min_order: 'Minimum order required',
    				src: require('../assets/squid-rolls-1.jpg')
    			},
    			{
    				name: 'Fries',
    				description: 'PLorem Ipsum Durom',
    				price: '0',
    				min_order: 'Minumum order Required',
    				src: require('../assets/fries-2.jpg')
    			},
                {
                    name: 'Mang Inasal Pecho',
                    description: 'PLorem Ipsum Durom',
                    price: '0',
                    min_order: 'Minumum order Required',
                    src: require('../assets/inasal-1.jpg')
                },
                {
                    name: 'Japanese Siomai',
                    description: 'Lorem Ipsum',
                    price: '0',
                    min_order: 'Lorem Ipsum Durom',
                    src: require('../assets/japan-1.jpg')
                },
    		]
    	}
    }
  }
</script>

<style>
</style>