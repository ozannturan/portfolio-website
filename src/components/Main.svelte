<main class="flex flex-col flex-1 p-4">
	<section id="homePage" class="grid grid-cols-1 lg:grid-cols-2 gap-10 py-8 sm:py-14">
		<div
			class="flex flex-col justify-center items-center lg:items-start text-center lg:text-left gap-6 md:gap-8 lg:gap-10"
		>
			<h2 class="font-semibold text-4xl sm:text-5xl md:text-6xl">
				Hi! I'm <span class="text-green-500">Ozan</span> Turan <br />Front
				<span class="text-green-500">Developer</span>
			</h2>
			<p class="text-base sm:text-lg md:text-xl">
				<span class="text-green-500">
					and I'm on my way to becoming a <span class="text-white">Full Stack web3</span> developer
				</span>
			</p>
		</div>
		<div class="relative flex justify-center items-center">
			<img src="src/routes/images/ozan.jpeg" alt="ozan" class="object-cover z-[2] max-h-[40vh]" />
		</div>
	</section>

	<section id="projects" class="py-20 lg:py-32 flex flex-col gap-24">
		<div class="flex flex-col gap-2 text-center">
			<h6 class="text-xl sm:text-xl md:text-2xl">A few of my creative product.</h6>
			<h3 class="text-3xl sm:text-4xl md:text-2xl text-blue-500">
				You can review my projects and contact me.
			</h3>
		</div>

		<div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-8 mt-12">
			<div
				class="bg-white shadow-md rounded-lg p-6 transition-transform duration-300 transform hover:scale-105"
			>
				<img
					src="src/routes/images/Portfolio-website.png"
					alt="POrtfolio Website"
					class="w-full h-auto rounded-lg mb-4"
				/>
				<h4 class="text-xl font-semibold mb-2">Portfolio-website</h4>
				<p class="text-gray-600">Portfolio Website</p>
				<a
					href="https://github.com/ozannturan/portfolio-website"
					class="text-blue-500 mt-4 inline-block">View Project</a
				>
			</div>
		</div>

		<!-- blog.svelte 
		
		<main class="flex flex-col flex-1 p-4">
			<section id="blog" class="py-20 lg:py-32 flex flex-col gap-24">
				<div class="flex flex-col gap-2 text-center">
					<h6 class="text-xl sm:text-xl md:text-2xl">Check out my latest blog posts.</h6>
					<h3 class="text-3xl sm:text-4xl md:text-2xl text-blue-500">
						You can read my blog posts.
					</h3>
				</div>

				<div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-8 mt-12">
					<div
						class="bg-white shadow-md rounded-lg p-6 transition-transform duration-300 transform hover:scale-105"
					>
						<h4 class="text-xl font-semibold mb-2">Blog Post 1 Title</h4>
						<p class="text-gray-600">
							Brief description of Blog Post 1. Lorem ipsum dolor sit amet, consectetur adipiscing
							elit.
						</p>
						<a href="/blog-post-1" class="text-blue-500 mt-4 inline-block">Read More</a>
					</div>
				</div>
			</section>
		</main>
		-->
	</section>
</main>
