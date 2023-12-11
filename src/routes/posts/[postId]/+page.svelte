<script>
	import { goto } from '$app/navigation';

	export let data;
</script>

<div>
	<h1>{data.post.title}</h1>
	<p>{data.post.body}</p>
	<button on:click={() => goto(`/posts`)}>go back...</button>
</div>

<style>
</style>
