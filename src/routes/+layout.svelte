<head>
	<link rel="stylesheet" href="/shared.css">
</head>

<script lang="ts">
    import Header from './Header.svelte';

	let { children } = $props();
</script>

<Header/>

{@render children?.()}

