<script lang="ts">
	let { children } = $props();
</script>

<h1>S-Burks</h1>

<nav>
	<a href="/">Home</a>
	<a href="/about">About</a>
	<a href="/contact">Contact</a>
	<a href="/projects">Projects</a>
</nav>

{@render children?.()}
