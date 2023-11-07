<script>
  	const navItems = [
		{ name: 'Home', href: '/' },
		{ name: 'Contact', href: '/contact' },
	];
</script>

<footer class="bg-black text-white">
  <nav flex justify-between>
		<ul class="flex justify-center gap-6">
			{#each navItems as { name, href }}
				<li><a {href}>{name}</a></li>
			{/each}
		</ul>
	</nav>
  <p class="text-center">&copy; Jessica Nelson</p>
</footer>