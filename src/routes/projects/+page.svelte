<svelte:head>
	<title>Projects</title>
	<meta name="description" content="My Project" />
</svelte:head>

<div class="text-column">
	<h1 style="background-color: black;margin:0 20px;border:solid red 0.3rem">Opensource Projects</h1>

	<div class="loader">
		<h2 style="font-size:larger;background-color: yellow;"><strong>Smrt_Mrkt</strong></h2>
	</div>

	<p>
		This is a <a href="https://kit.svelte.dev">SvelteKit</a> app. You can make your own by typing the
		following into your command line and following the prompts:
	</p>

	<pre>npm create svelte@latest</pre>

	<p>
		The page you're looking at is purely static HTML, with no client-side interactivity needed.
		Because of that, we don't need to load any JavaScript. Try viewing the page's source, or opening
		the devtools network panel and reloading.
	</p>

	<p>
		The <a href="/sverdle">Sverdle</a> page illustrates SvelteKit's data loading and form handling. Try
		using it with JavaScript disabled!
	</p>
</div>

<style>
	
	.text-column{
		color: white;
		background-image: url('../../lib/images/bkg.jpg');
		background-repeat: no-repeat;
    	background-size: cover;
	}

	.loader{
		text-align:center;
		background-color: green;
		margin:10px auto;
	}

</style>