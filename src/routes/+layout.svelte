<script lang="ts">
	import favicon from '$lib/assets/favicon.svg';

	let { children } = $props();
</script>

<svelte:head>
	<link rel='icon' href={favicon} />
</svelte:head>

<h1>S-Burks</h1>

<nav>
	<a href='/'>Home</a>
	<a href='/about'>About</a>
	<a href='/film'>Film</a>
	<a href='/programming'>Programming</a>
</nav>

{@render children?.()}
