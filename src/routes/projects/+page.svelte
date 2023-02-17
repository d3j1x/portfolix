<svelte:head>
	<title>Projects</title>
	<meta name="description" content="My Project" />
</svelte:head>

<div class="text-column">
	<h1 style="background-color: black;margin:0 20px;border:solid red 0.2rem;opacity:0.9">Opensource Projects</h1>

	<div class="secret">
		<h2>CYBER-SECRET</h2>
		<p>
		This is a <a href="https://github.com/d3j1x/cyber-secret">Cyber-secret</a> repo. You can Explore it by following the <a href="https://d3j1x.github.io/cyber-secret/">link</a>.
		</p>
	</div>

	
	<!-- 

	<pre>npm create svelte@latest</pre>

	<p>
		The page you're looking at is purely static HTML, with no client-side interactivity needed.
		Because of that, we don't need to load any JavaScript. Try viewing the page's source, or opening
		the devtools network panel and reloading.
	</p>

	<p>
		The <a href="/sverdle">Sverdle</a> page illustrates SvelteKit's data loading and form handling. Try
		using it with JavaScript disabled!
	</p> -->
</div>

<style>
	
	.text-column{
		margin: 25px auto;
		color: white;
		width: 100%;
		background-image: url('../../lib/images/bkg.jpg');
		background-repeat: no-repeat;
    	background-size: cover;
		border-radius: 20%;
	}

	.secret{
		background-color: black;
		margin: 10px auto;
		text-align: center;
		border: dotted yellow;
	}

	h2{
		font-size:larger;
		font-weight: bolder;
		color: #3DFF33;
		
	}

	

</style>