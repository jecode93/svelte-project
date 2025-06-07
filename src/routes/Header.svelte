<script lang="ts">
	let great: String = 'World';
  let { name } = $props();
</script>

<h1>Hello {great}</h1>
<p>This is my first svelte component called {name}</p>
