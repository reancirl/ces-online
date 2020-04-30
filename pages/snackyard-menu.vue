<template>
	<div class="snack-menu">
	  	<div class="container">
			<h1 class="outline-2 text-center pt-5">Snack Yard Menu</h1>
			<ProductMenu 
			v-for="product in products"
			:key="product.name"
			:product="product"
			/>
	  	</div>
	</div>
</template>

<script>
	import ProductMenu from "../components/ProductMenu";  

	export default {
    components:{
      ProductMenu
    },
    data() {
    	return {
    		products: [
    			{
    				name: 'Fries',
    				description: 'Cheese, Barbecue & Sour cream Flavored',
    				price: '30',
    				availability: 'Avalable for delivery in Bulk Orders',
    				src: require('../assets/fries-sour.jpg')
    			},
    			{
    				name: 'Tempura & Squid Roll',
    				description: 'Cheese, Barbecue & Sour cream Flavored',
    				price: '35',
    				availability: 'Avalable for delivery in Bulk Orders',
    				src: require('../assets/squid-1.jpg')
    			},
    			{
    				name: 'Good Morning Burger',
    				description: 'Buy 1 Take 1 | Burger w/ cheese & egg',
    				price: '60',
    				availability: 'Sold only in Store',
    				src: require('../assets/gmb-1.jpg')
    			},
    			{
    				name: 'Siomai',
    				description: '5 pieces | Beef, Chicken, Pork & Japanese Siomai',
    				price: '35',
    				availability: 'Avalable for delivery in Bulk Orders',
    				src: require('../assets/siomai-1.jpg')
    			},
    			{
    				name: 'Siopao',
    				description: 'Pork & Chicken Siopao',
    				price: '18',
    				availability: 'Avalable for delivery in Bulk Orders',
    				src: require('../assets/siopao-1.jpg')
    			},
    			{
    				name: 'Burger',
    				description: 'Buy 1 Take 1',
    				price: '35',
    				availability: 'Sold only in Store',
    				src: require('../assets/burger-1.jpg')
    			},
    			{
    				name: 'Chicken Proven',
    				description: 'Per stick',
    				price: '5',
    				availability: 'Avalable for delivery in Bulk Orders',
    				src: require('../assets/proven-1.jpg')
    			},
    		]
    	}
    }
  }
</script>

<style>
	.products{
	}
</style>