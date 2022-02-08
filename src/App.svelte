<script>
	import Popup from './Rules_Modal.svelte';
const showPopup = () => {
		open(Popup, { message: "It's a popup!" });
	};
</script>

<main>
	<h1>BaseBall Game <span><button on:click={showPopup}>?</button></span> </h1> 
	<form>
	<input type='number' id='num' value='0'/>
	<input type='number' id='num' value='0'/>
	<input type='number' id='num' value='0'/>
	<input type='button' id='btn' value='Throw!'/>
	</form>
</main>

<style>

</style>