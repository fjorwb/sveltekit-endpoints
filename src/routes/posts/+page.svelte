<script>
	export let data;
	import { goto } from '$app/navigation';

	function handleReadMore(id) {
		goto(`/posts/${id}`);
	}
</script>

<div>
	{#each data.posts as post}
		<h1>{post.title}</h1>
		<p>{post.body.slice(0, 150)}...</p>
		<button on:click={handleReadMore(post.id)}>read more...</button>
	{/each}
</div>
