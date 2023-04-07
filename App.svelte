<script>
    import BurgerMenu from "svelte-burger-menu";
</script>

<BurgerMenu 
						backgroundColor="#e5e7eb"
						padding={'0px'}
						menuColor="Gray-100"
						width= 200px
						font-weight: 400;
						text-align: center;
						>
	
    <h2>About</h2>
    <h2>Products</h2>
	<h2>Resturant</h2>
	<h2>Contact</h2>
	<h2>Sign In</h2>
</BurgerMenu>


<style>
	h2 {
	  font-size: 18px;
	  font-weight: 300;
	  padding-top: 15px;
	  padding-left: 3em;
	  padding-right: 3.2em;
	  cursor: pointer;
	  position: relative;
	  width: 80px;
	  height: 40px;
	  text-align: center;
	  float: center;
	  display: block;
	}

	h2:hover {
	  background-color: #94a3b8;
		border-radius: 0.5rem; /* 16px */
		
	}
	
</style>