<script>
	import Counter from './Counter.svelte';
	import welcome from '$lib/images/svelte-welcome.webp';
	import welcome_fallback from '$lib/images/svelte-welcome.png';

	import Myname from './Myname.svelte';
	import AnimatedText from "./AnimatedText.svelte";
	import bkg from '$lib/images/bkg.jpg';
	import pro from '$lib/images/pro.jpg';
</script>

<svelte:head>
	<title>PortfoliX</title>
	<meta name="description" content="Portfolix d3j1x app" />
</svelte:head>


<h3>WELCOME</h3>

	
	<div id="samg" style="width:250px;height:250px">
		
	</div>
<Myname text="I'm Shiheb Din" delay={300} />
<AnimatedText text="Cybersecurity Specialist & Full Stack Developer." delay={100} />
<!-- <section>
	<h1>
		<span class="welcome">
			<picture>
				<source srcset={welcome} type="image/webp" />
				<img src={welcome_fallback} alt="Welcome" />
			</picture>
		</span>

		

		to your new<br />SvelteKit app
	</h1>

	<h2>
		try editing <strong>src/routes/+page.svelte</strong>
	</h2>

	

	<Counter />
</section> -->

<style>

	#samg{
		align-items: center;
		justify-content: center;
		margin: 0 auto;
		border-radius: 50%;
		background-image:  url('/src/lib/images/pro.jpg');
		background-repeat: no-repeat;
    	background-size: cover;
	}

	h3{
		font-family: 'Ubuntu', sans-serif;
  		font-size: 3rem;
  		font-weight: bold;
  		color: red;
  		text-align: center;
  		letter-spacing: 5px;
  		text-shadow: 0 2px 3px #747474, 
      		1px 3px 4px #222, 
      		0 8px 3px #474747, 
      		0 11px 4px #747474,
      		0 14px 4px #565656,
      		0 17px 4px #343434,
      		0 20px 4px #171717;
	}
	
	/* section {
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		flex: 0.6;
	}

	h1,h2 {
		width: 100%;
		
	}

	.welcome {
		display: block;
		position: relative;
		width: 100%;
		height: 0;
		padding: 0 0 calc(100% * 495 / 2048) 0;
	}

	.welcome img {
		position: absolute;
		width: 100%;
		height: 100%;
		top: 0;
		display: block;
	} */
</style>
