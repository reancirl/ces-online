<template>
	<div class="footer">
		<div class="container">
			<b-row>
				<b-col sm="6">
					<h6 class="font--9" id="yong-name">
						© 2020 Yong Snack Yard & Frozen Products
					</h6>
				</b-col>
				<b-col sm="6">
					<h6 class="font--9" id="rb-name">
						Made with ❤ by <a href="https://reancirl.life" target="_blank" style="color:white; text-decoration: underline;">Reancirl Balaba</a> | All Rights Reserved
					</h6>
				</b-col>
			</b-row>
			
		</div>
	</div>
</template>

<script>
	
</script>

<style>
	h6{
		font-size: .9rem;			
	}
	.footer{
		background-color: #c6a530;
		color: #f7f7f7;
		padding: 20px 15px 10px 15px;
	}
	.icon-1{
		font-size: 20px;
	}
	#yong-name{
		text-align: left;
	}
	#rb-name{
		text-align: right;
	}
	@media (max-width: 415px){
		#rb-name{
			text-align: center;
		}
	}
</style>