<script lang="ts">
	import './layout.css';
	import favicon from '$lib/assets/favicon.svg';

	let { children } = $props();
</script>

<svelte:head><link rel="icon" href={favicon} /></svelte:head>



<nav>
	<p>PROYECT ARC</p>

	<div>
		<a href="/">menu</a>
		<a href="/xbox">xbox</a>
		<a href="/playstation">playstation</a>
		<a href="/nintendo">nintendo</a>
		<a href="/pc">pc</a>
		
	</div>

	<a href="/login">
		<span></span>
		<p>login</p>
	</a>

	<a href="/search">
		<span></span>
		<p>search</p>
	</a>

</nav>

{@render children()}

<footer>
	Este es mi pie de pagina
</footer>
