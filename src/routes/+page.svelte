<script>
	import Counter from './Counter.svelte';
	import welcome from '$lib/images/svelte-welcome.webp';
	import welcome_fallback from '$lib/images/svelte-welcome.png';
</script>

<svelte:head>
	<title>Home</title>
	<meta name="description" content="Svelte demo app" />
</svelte:head>

<section>
	<h1>
		Victor Ngo, DevOps Engineer
			<!-- TODO remove -->
		<!-- <span class="welcome">
			<picture>
				<source srcset={welcome} type="image/webp" />
				<img src={welcome_fallback} alt="Welcome" />
			</picture>
		</span> -->
	</h1>
	<p>Welcome to my personal site!</p>
	<p>
		The intentions of this site are to </p>
		<ol>
			<li>
					1 - add value to you, 
			</li>
			<li>
				2 - serve as a personal site
			</li>
		</ol>
		
	<section>
		<h2>Resources</h2>

			Here are some things that have added value to my life and I hope they help yours:
			- Link
			<ul>
				<li></li>
			</ul>
			* Linktree
			* Personal blog 
			* Link to CI/CD
		
			Health
			- Avoid microplastics - https://twitter.com/davidasinclair/status/1680619459399090176		
	</section>


</section>

<style>
	section {
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		flex: 0.6;
	}

	h1 {
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
	}
</style>
