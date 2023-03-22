<svelte:head>
	<title>Projects</title>
	<meta name="description" content="My Project" />
</svelte:head>

<div class="text-column">
	<h1 style="background-color: black;margin:0 20px;border:solid red 0.2rem;opacity:0.9">Opensource Projects</h1>

	<!-- <div class="secret">
		<h2>CYBER-SECRET</h2>
		<p>
		This is a <a href="https://github.com/d3j1x/cyber-secret">Cyber-Secret</a> repo. You can Explore it by following the <a href="https://d3j1x.github.io/cyber-secret/">link</a>.
		</p>
	</div> -->

	<div id="loading">
		<div class="waviy">
			<br>
 <span style="--i:1">₿</span>
 <span style="--i:2">I</span>
 <span style="--i:3">T</span>
 <span style="--i:4">C</span>
 <span style="--i:5">O</span>
 <span style="--i:6">I</span>
 <span style="--i:7">N</span>
 <span style="--i:8">-</span>
 <span style="--i:9">S</span>
 <span style="--i:10">T</span>
 <span style="--i:11">R</span>
 <span style="--i:12">E</span>
 <span style="--i:13">E</span>
 <span style="--i:14">T</span>
	</div>
		<p>
			This is a <a href="https://github.com/d3j1x/BitcoinStreet">₿itcoin-Street</a> repo. You can Explore it by following the <a href="https://bitcoin-street.vercel.app/">link</a>.
		</p>
	</div>

	<div id="loading">
		<div class="waviy">
			<br>
 <span style="--i:1">C</span>
 <span style="--i:2">Y</span>
 <span style="--i:3">B</span>
 <span style="--i:4">E</span>
 <span style="--i:5">R</span>
 <span style="--i:6">-</span>
 <span style="--i:7">S</span>
 <span style="--i:8">E</span>
 <span style="--i:9">C</span>
 <span style="--i:10">R</span>
 <span style="--i:11">E</span>
 <span style="--i:12">T</span>
	</div>
		<p>
			This is a <a href="https://github.com/d3j1x/cyber-secret">Cyber-Secret</a> repo. You can Explore it by following the <a href="https://d3j1x.github.io/cyber-secret/">link</a>.
		</p>
	</div>



	<div id="loading">
		<div class="waviy">
			<br>
 <span style="--i:1">S</span>
 <span style="--i:2">M</span>
 <span style="--i:3">R</span>
 <span style="--i:4">T</span>
 <span style="--i:5">-</span>
 <span style="--i:6">M</span>
 <span style="--i:7">R</span>
 <span style="--i:8">K</span>
 <span style="--i:9">T</span>
	</div>
		<p>
			This is a <a href="https://github.com/smrket/Smrt-Mrkt">Smrt-Mrkt</a> repo. You can Explore it by following the <a href="https://smrket.github.io/Smrt-Mrkt/">link</a>.
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

	/* .secret{
		background-color: black;
		margin: 10px auto;
		text-align: center;
		border: dotted yellow;
	}

	h2{
		font-size:larger;
		font-weight: bolder;
		color: #3DFF33;
		
	} */

	#loading {
	width: 80%;
  	background-color: black;
  	margin: 10px auto;
	text-align: center;
	border: dotted yellow;
	}

.waviy {
  position: relative;
 
}
.waviy span {
  	position: relative;
  	display: inline-block;
  	font-size:larger;
	font-weight: bolder;
	color: #3DFF33;
 	text-transform: uppercase;
  	animation: flip 3s infinite;
  	animation-delay: calc(.2s * var(--i))
}
@keyframes flip {
  0%,80% {
    transform: rotateY(360deg) 
  }
}

	

</style>