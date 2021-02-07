<script>
	import NavBar from './NavBar.svelte';
	import Banner from './Banner.svelte';
	import About from './About.svelte';
	import Projects from './Projects.svelte';
	import Contact from './Contact.svelte';
</script>

<header>
	<NavBar />
</header>
<main>
	<Banner />
	<About />
	<Projects />
	<Contact />
</main>
<footer>
	<p>Made by Espen Berget</p>
	<a href="https://github.com/EspenBerget/portfolio" target="_blank"><i class="fab fa-github"></i> source for this page</a>
</footer>

<style>
	:global(body) {
		padding: 0;
	}

	main {
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		height: auto;
		min-height: 100vh;
		width: 100vw;
	}

	footer {
		background-color: black;
		color: rgb(197, 197, 197);
		padding: 1rem;

		display: flex;
		justify-content: space-between;
	}

	footer p {
		margin: 0;
	}

	footer a {
		color:rgb(197, 197, 197); 
		text-decoration: none;
	}
</style>