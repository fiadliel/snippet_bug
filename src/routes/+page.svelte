<script lang="ts">
</script>

{#snippet test(param: string = "default")}
    <p>Inside a snippet, param: {param}</p>
{/snippet}

<h1>Welcome to SvelteKit</h1>
<p>
    Visit <a href="https://svelte.dev/docs/kit">svelte.dev/docs/kit</a> to read the
    documentation
</p>
{@render test()}
