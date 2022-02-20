<svelte:options tag="svg-pan" />

<script>
	let count = 0;

	function handleClick() {
		count += 2;
	}
</script>

<button on:click={handleClick}>
	Clicked {count}
	{count === 1 ? "time" : "times"}
</button>
