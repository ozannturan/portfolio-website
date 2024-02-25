<section id="Blog">
	<script>
		let blogPosts = [
			{
				id: 1,
				title: 'Post Title 1',
				content: 'This is the first post of the blog. We are creating a simple blog using Svelte and Tailwind CSS.',
				date: 'February 25, 2024',
				imageUrl: 'https://via.placeholder.com/150'
			},
			{
				id: 2,
				title: 'Post Title 2',
				content: 'Writing a blog with Svelte and Tailwind CSS is so much fun! Hope this example interests you.',
				date: 'February 26, 2024',
				imageUrl: 'https://via.placeholder.com/150'
			}
		];
	</script>

	<main class="container mx-auto px-4 py-8 grid grid-cols-1 sm:grid-cols-2 gap-4">
		{#each blogPosts as post}
			<div
				class="border p-4 rounded-lg cursor-pointer transition duration-500 ease-in-out transform hover:-translate-y-1 hover:scale-105"
			>
				<img src={post.imageUrl} alt={post.title} class="w-full h-auto mb-4 rounded-lg" />
				<h2 class="text-lg font-semibold mb-2">{post.title}</h2>
				<p class="text-gray-600 mb-2">{post.date}</p>
				<p>{post.content}</p>
			</div>
		{/each}
	</main>
</section>
