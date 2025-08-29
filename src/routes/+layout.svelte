<script lang="ts">
	import Header from './Header.svelte';
	import ferbIcon from "$lib/assets/ferbicon.png";

	let { children } = $props();
</script>

<svelte:head>
	<title>S-Burks</title>
	<link rel="stylesheet" href="/shared.css">
	<link rel="icon" href={ferbIcon}>
</svelte:head>


<Header/>

{@render children?.()}

