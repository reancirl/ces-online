<template>
	<div class="snack-menu">
	  	<div class="container">
			<h1 class="outline-2 text-center pt-5">Snack Yard Menu</h1>
			<ProductMenu />
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
    				name: 'Siopao',
    				description: 'Pork & Chicken Siopao',
    				price: '18 pesos',
    				availability: 'Avalable for delivery in Bulk Orders',

    			},
    			{
    				name: 'Burger',
    				description: 'Buy 1 Take 1',
    				price: '35 pesos',
    				availability: 'Sold only in Store',

    			},
    			{
    				name: 'Cheese Burger',
    				description: 'Buy 1 Take 1',
    				price: '40 pesos',
    				availability: 'Sold only in Store',

    			},
    			{
    				name: 'Good Morning Burger',
    				description: 'Buy 1 Take 1 | Burger w/ egg',
    				price: '50 pesos',
    				availability: 'Sold only in Store',

    			},
    			{
    				name: 'Siomai',
    				description: '5 pieces | Beef, Chicken & Japanese Siomai',
    				price: '35 pesos',
    				availability: 'Avalable for delivery in Bulk Orders',

    			},
    			{
    				name: 'Fries',
    				description: 'Cheese, Barbecue & Sour cream Flavored',
    				price: '25 pesos',
    				availability: 'Avalable for delivery in Bulk Orders',

    			},
    			{
    				name: 'Tempura & Squid Roll',
    				description: 'Cheese, Barbecue & Sour cream Flavored',
    				price: '35 pesos',
    				availability: 'Avalable for delivery in Bulk Orders',

    			},

    			{
    				name: 'Chicken Proven',
    				description: 'Per stick',
    				price: '5 pesos',
    				availability: 'Avalable for delivery in Bulk Orders',

    			}
    		]
    	}
    }
  }
</script>

<style>
	
</style>