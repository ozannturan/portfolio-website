<!-- header.svelte -->

<script>
	let tabs = [
		{ name: 'Home', link: '#homePage' },
		{ name: 'Projects', link: '#projects' },
		{ name: 'Blog', link: '#blog' },
		{ name: 'Contact Me', link: '#Contactme' }
	];
</script>

<header class="text-white p-4">
	<div class="container mx-auto flex justify-between items-center">
		<div class="text-2xl font-bold">
			<h1
				class="font-bold text-transparent bg-gradient-to-r bg-clip-text from-green-500 to-red-500"
			>
				<b>Ozan</b> Turan
			</h1>
		</div>
		<nav>
			<ul class="flex space-x-4">
				{#each tabs as tab}
					<li>
						<a
							href={tab.link}
							class="relative overflow-hidden px-5 py-2 group rounded-full bg-white text-slate-950 hover:text-blue-500 transition-colors duration-200"
							>{tab.name}</a
						>
					</li>
				{/each}
			</ul>
		</nav>
	</div>
</header>
