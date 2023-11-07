<script>
	const navItems = [
		{ name: 'Home', href: '/' },
		{ name: 'Cocktail Menu', href: '/cards' },
		{ name: 'Contact', href: '/contact' },
	];
</script>

<header class="bg-red-400 text-white flex justify-between p-4">
	<nav>
		<ul class="flex justify-around gap-4">
			{#each navItems as { name, href }}
				<li><a {href}>{name}</a></li>
			{/each}
		</ul>
	</nav>
</header>