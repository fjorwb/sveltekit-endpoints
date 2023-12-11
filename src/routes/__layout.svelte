<script></script>

<slot />

<style>
	:root {
		--color-primary: #ff0000;
		--color-secondary: #00ff00;
		--color-tertiary: #0000ff;
	}
	:global(body) {
		font-family: 'Open Sans';
		padding: 3rem;
		background: rgb(12, 12, 27);
		color: white;
	}

	:global(h1) {
		font-weight: 300;
		/* font-size: 1rem; */
	}

	:global(a) {
		color: yellowgreen;
	}

	:global(a:hover) {
		color: yellow;
	}

	:global(button) {
		background: var(--color-secondary);
		color: var(--color-tertiary);
		padding: 0.25rem 0.5rem;
		border-radius: 5px;
		border: none;
		font-weight: 700;
	}
</style>
