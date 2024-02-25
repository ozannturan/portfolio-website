<script>
	let tabs = [
		{ name: 'About Me', link: '#aboutme' },
		{ name: 'Projects', link: '#projects' },
		{ name: 'Blog', link: '#blog' },
		{ name: 'Contact Me', link: '#Contactme' }
	];

    let projects = [
        { 
            title: "Project Title 1",
            image: "project1.jpg",
            description: "Project description goes here. Lorem ipsum dolor sit amet, consectetur adipiscing elit."
        },
        { 
            title: "Project Title 2",
            image: "project2.jpg",
            description: "Project description goes here. Lorem ipsum dolor sit amet, consectetur adipiscing elit."
        },
        { 
            title: "Project Title 3",
            image: "project3.jpg",
            description: "Project description goes here. Lorem ipsum dolor sit amet, consectetur adipiscing elit."
        },
        { 
            title: "Project Title 4",
            image: "project4.jpg",
            description: "Project description goes here. Lorem ipsum dolor sit amet, consectetur adipiscing elit."
        }
    ];

</script>

<div class="relative flex flex-col max-w-[1400px] mx-auto w-full text-sm">
	<div class="fixed bottom-0 w-full duration-200 flex p-10 z-[10]">
		<button>
			<i class="fa-solid fa-arrow-up" />
		</button>
	</div>
</div>
<header class="bg-gray-800 text-white p-4">
	<div class="container mx-auto flex justify-between items-center">
		<div class="text-2xl font-bold">
			<h1
				class=" font-bold text-transparent bg-gradient-to-r bg-clip-text from-green-500 to-red-500"
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
							target="_blank"
							rel="noopener noreferrer"
							class="relative overflow-hidden px-5 py-2 group rounded-full bg-white text-slate-950 hover:text-blue-500 transition-colors duration-200"
							>{tab.name}</a
						>
					</li>
				{/each}
			</ul>
		</nav>
	</div>
</header>

<main class="flex flex-col flex-1 p-4">
	<section id="aboutme" class="grid grid-cols-1 lg:grid-cols-2 gap-10 py-8 sm:py-14">
		<div class="flex flex-col lg:justify-center text-center lg:text-left gap-6 md:gap-8 lg:gap-10">
			<h2 class="font-semibold text-2xl sm:text-3xl md:text-4xl">
				Hi! I'm <span class="text-green-500">Ozan</span> Turan <br />Front
				<span class="text-green-500">Developer</span>
			</h2>
			<p class="text-base sm:text-lg md:text-xl">
				<span class="text-green-500"
					>and I'm on my way to becoming a <span class="text-white"> Full Stack web3</span> developer</span
				>
			</p>
		</div>
		<div class="relative shadow-2xl grid place-items-center justify-center">
			<img src={'src/routes/images/ozan.jpeg'} alt="ozan" class="object-cover z-[2] max-h-[40vh]" />
		</div>
	</section>
</main>

<section id="projects" class="py-20 lg:py-32 flex flex-col gap-24">
	<div class="flex flex-col gap-2 text-center">
		<h6 class="text-xl sm:text-xl md:text-2xl">A few of my creative product.</h6>
		<h3 class="text-3xl sm:text-4xl md:text-2xl text-blue-500">
			You can review my projects and contact me.
		</h3>
	</div>

	<!-- İlgili sınıflara hover efektlerini ekleyelim -->
	<div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-8 mt-12">
		<div class="bg-white shadow-md rounded-lg p-6 transition-transform duration-300 transform hover:scale-105">
			<img src="project1.jpg" alt="Project 1" class="w-full h-auto rounded-lg mb-4" />
			<h4 class="text-xl font-semibold mb-2">Project Title</h4>
			<p class="text-gray-600">
				Project description goes here. Lorem ipsum dolor sit amet, consectetur adipiscing elit.
			</p>
			<a href="#" class="text-blue-500 mt-4 inline-block">View Project</a>
		</div>
	</div>

	<div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-8 mt-12">
		<div class="bg-white shadow-md rounded-lg p-6 transition-transform duration-300 transform hover:scale-105">
			<img src="project2.jpg" alt="Project 2" class="w-full h-auto rounded-lg mb-4" />
			<h4 class="text-xl font-semibold mb-2">Project Title</h4>
			<p class="text-gray-600">
				Project description goes here. Lorem ipsum dolor sit amet, consectetur adipiscing elit.
			</p>
			<a href="#" class="text-blue-500 mt-4 inline-block">View Project</a>
		</div>
	</div>

	<div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-8 mt-12">
		<div class="bg-white shadow-md rounded-lg p-6 transition-transform duration-300 transform hover:scale-105">
			<img src="project3.jpg" alt="Project 3" class="w-full h-auto rounded-lg mb-4" />
			<h4 class="text-xl font-semibold mb-2">Project Title</h4>
			<p class="text-gray-600">
				Project description goes here. Lorem ipsum dolor sit amet, consectetur adipiscing elit.
			</p>
			<a href="#" class="text-blue-500 mt-4 inline-block">View Project</a>
		</div>
	</div>

	<div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-8 mt-12">
		<div class="bg-white shadow-md rounded-lg p-6 transition-transform duration-300 transform hover:scale-105">
			<img src="project4.jpg" alt="Project 4" class="w-full h-auto rounded-lg mb-4" />
			<h4 class="text-xl font-semibold mb-2">Project Title</h4>
			<p class="text-gray-600">
				Project description goes here. Lorem ipsum dolor sit amet, consectetur adipiscing elit.
			</p>
			<a href="#" class="text-blue-500 mt-4 inline-block">View Project</a>
		</div>
	</div>
</section>

