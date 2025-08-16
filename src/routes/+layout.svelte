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

<style>
	nav {
		display: flex;
		justify-content: space-around;
		border:  solid 2px white;
		border-radius: 10px;
	}

	a {
		display: flexbox;
		background-color: darkslategrey;
		padding: 10px;
		border: 2px solid white;
		border-radius: 5px;
		flex: 1;
		text-align: center;
		font-size: 30px;
	}

	h1 {
		text-align: center;
		font-size: 100px;
		font-weight: bold;
	}

</style>
