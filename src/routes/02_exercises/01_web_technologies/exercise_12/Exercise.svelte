<script>
	let clicked = false;
</script>

{#if clicked}
<div>
	<button title="You have clicked the button!" class="btn btn-primary" on:click={() => (clicked = true) } >
		click here
	</button>
</div>
{:else}
<div>
	<button title="You have to click the button!" class="btn btn-primary" on:click={() => (clicked = true) } >
		click here
	</button>
</div>
{/if}

