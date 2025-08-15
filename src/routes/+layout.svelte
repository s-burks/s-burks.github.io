<script lang="ts">
	import favicon from "$lib/assets/favicon.svg";

	let { children } = $props();
</script>

<svelte:head>
	<link rel="icon" href={favicon} />
	<link rel="preconnect" href="https://fonts.googleapis.com" />
	<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin="" />
	<link
		href="https://fonts.googleapis.com/css2?family=Ubuntu+Mono:ital,wght@0,400;0,700;1,400;1,700&display=swap"
		rel="stylesheet"
	/>
</svelte:head>

<h1>S-Burks</h1>

<nav>
	<a href="/">Home</a>
	<a href="/about">About</a>
	<a href="/contact">Contact</a>
	<a href="/projects">Projects</a>
</nav>

{@render children?.()}

<style>
	ubuntu-mono-regular {
		font-family: "Ubuntu Mono", monospace;
		font-weight: 400;
		font-style: normal;
	}

	.ubuntu-mono-bold {
		font-family: "Ubuntu Mono", monospace;
		font-weight: 700;
		font-style: normal;
	}

	.ubuntu-mono-regular-italic {
		font-family: "Ubuntu Mono", monospace;
		font-weight: 400;
		font-style: italic;
	}

	.ubuntu-mono-bold-italic {
		font-family: "Ubuntu Mono", monospace;
		font-weight: 700;
		font-style: italic;
	}

	:global(h1) { font-family: ubuntu-mono-bold, monospace; }
	:global(h2) { font-family: ubuntu-mono-regular, monospace;}

</style>
