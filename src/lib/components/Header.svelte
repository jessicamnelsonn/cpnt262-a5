 <script>
	const navItems = [
		{ name: 'Home', href: '/' },
		{ name: 'Contact', href: '/contact' },
	];
</script>

<header class="bg-slate-300 flex justify-between p-4 hover:text-blue-800">
	<nav>
		<ul class="flex justify-around gap-4">
			{#each navItems as { name, href }}
				<li class="font-bold text-xl"><a {href}>{name}</a></li>
			{/each}
		</ul>
	</nav>
</header> 