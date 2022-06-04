<script>
	import globe from '../dark2.svg';
</script>

<svelte:head>
	<title>John Radojevich: Full Stack Web Developer, GIS / Data Visualization Specialist</title>
</svelte:head>

<main class="h-screen snap-y snap-mandatory overflow-y-scroll">
	<section
		class="grid h-full snap-center bg-[#120930] from-zinc-800 to-zinc-900 dark:bg-gradient-to-b lg:grid-cols-2 md:grid-cols-1"
	>
		<div class="flex flex-col justify-center align-middle">
			<h1 class="text-right text-7xl text-white">Hello;<br />I'm <span class='font-bold'> John Radojevich</span></h1>
			<p class="mt-6 bg-zinc-900 p-4 text-right text-gray-300 shadow-sm shadow-red-500">
				To me, maps are so much more than diagrams that help us navigate from point A to point B.
				<br>
				They are windows into information that allow us to explore our world, understand it better, and
				engage with it more productively. They spark our curiosity, provide insight, and help us
				build solutions for a better world.
			</p>
		</div>
		<div class="flex">
			<img src={globe} class="m-auto h-100 w-100" />
		</div>
	</section>
	<section class="h-full snap-center dark:bg-zinc-900">
			<h1 class="text-white text-7xl pt-10">Experienced.</h1>
			<h2 class='text-white text-3xl mt-5'>To me, development is more than a career.</h2>
	</section>
</main>

