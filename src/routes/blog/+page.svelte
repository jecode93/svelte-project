<script lang="ts">
	let { data } = $props();
</script>

<h1>Blog</h1>
<ul>
	{#each data.summaries as { slug, title }}
		<li><a href="/blog/{slug}">{title}</a></li>
	{/each}
</ul>
