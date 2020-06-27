<script>
	export let imgURL;
	export let imgALT;
	export let linkURL;
</script>

<div><a href={linkURL} target="_blank" rel="noopener"><img src={imgURL} alt={imgALT}></a></div>

<style>
	div {
		display: flex;
		justify-content: center;
		align-items: center;
		width: 100%;
		height: auto;
	}

	img {
		box-sizing: border-box;;
		min-width: 64px;
		max-width: calc(100% - 3em);
		min-height: 200px;
		max-height: 75vh;
		margin: 1.5em;
	}
</style>
