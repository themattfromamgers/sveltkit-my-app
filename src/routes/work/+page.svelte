<svelte:head>
	<title>Work</title>
	<meta name="description" content="WORK this app" />
</svelte:head>

<script>

	let firstName = '';
</script>

<div>
    <h1>WORK</h1>
	{firstName}
	<br>
	<input type="text" bind:value={firstName}>
</div>