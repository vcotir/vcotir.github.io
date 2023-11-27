<script>
	import Counter from './Counter.svelte';
	import welcome from '$lib/images/svelte-welcome.webp';
	import welcome_fallback from '$lib/images/svelte-welcome.png';
</script>

<svelte:head>
	<title>I'm Victor Ngo</title>
	<meta name="description" content="Victor Ngo's Personal Website" />
</svelte:head>

<section id="welcome">
	<h1 class="mb-3">
		Hello
	</h1>
	<p>
		My name is Victor Ngo. I build for builders
		<br /> 
		I'm a DevOps Engineer based in San Francisco
	</p>
	<section>
		<nav>
			<li>
				<a href="#">About me</a>
			</li>
			<li>
				<a href="#">Read my articles</a>
			</li>
		</nav>
	</section>
</section>

<section id="projects">
	<section>
		DevOps
	</section>
	<section>
		Web Development
	</section>
	<section>
		
	</section>
</section>

<section id="contact">
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
