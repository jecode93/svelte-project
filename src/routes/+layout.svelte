<script lang="ts">
	import Header from '../components/Header.svelte';
	let { children } = $props();
</script>

<Header />

{@render children()}