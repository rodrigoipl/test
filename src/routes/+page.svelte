<script>
	export let data;

	console.log(data.serverTime);
</script>

<svelte:head>
	<title>Home</title>
	<meta name="description" content="Svelte demo app" />
</svelte:head>

Server tine: {data.serverTime}
