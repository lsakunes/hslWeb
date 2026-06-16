<script lang="ts">
	import { resolve } from '$app/paths';
</script>

<svelte:head>
	<title>About</title>
	<meta name="description" content="About this app" />
</svelte:head>

<div class="text-column">
	<h1>About this app</h1>

	<p>
		wE are the greatest club in this nation. I haven't visited other countries so I don't know about them.
		We also have the greatest website.
	</p>

	<pre>SUCK IT EVAN YOU STACHYBOTRYS CHARTARUM SNORTING DUNCE</pre>

	<p>
		The page you're looking at is purely static HTML, with no client-side interactivity needed.
		Because of that, we don't need to load any JavaScript. Try viewing the page's source, or opening
		the devtools network panel and reloading.
	</p>

	<p>
		The <a href={resolve('/sverdle')}>Sverdle</a> page illustrates SvelteKit's data loading and form handling.
		Try using it with JavaScript disabled!
	</p>
</div>
