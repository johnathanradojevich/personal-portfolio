<script>
	import globe from '../dark2.svg';
</script>

<svelte:head>
	<title>John Radojevich: Full Stack Web Developer, GIS / Data Visualization Specialist</title>
</svelte:head>

<main class="static h-screen snap-y snap-mandatory overflow-y-scroll">
	<section
		class="static grid h-full snap-center bg-[#120930] from-zinc-800 to-zinc-900 dark:bg-gradient-to-b md:grid-cols-1 lg:grid-cols-2"
	>
		<div class="flex flex-col justify-center align-middle">
			<h1 class="text-right text-7xl text-white">
				Hello,<br />I'm <span class="font-bold"> John Radojevich</span>
			</h1>
			<h2 class="mt-5 text-right text-xl text-gray-300">
				A Full-Stack Developer, <i>Specializing in GIS & Data Visualization</i>
			</h2>
			<p class="mt-6 bg-zinc-900 p-4 text-right text-gray-300 shadow-sm shadow-red-500">
				To me, maps are so much more than diagrams that help us navigate from point A to point B.
				<br />
				They are windows into information that allow us to explore our world, understand it better, and
				engage with it more productively. They spark our curiosity, provide insight, and help us build
				solutions for a better world.
			</p>
		</div>
		<div class="flex">
			<img src={globe} class="h-100 w-100 m-auto" />
		</div>
	</section>
	<section class="relative h-full snap-center dark:bg-zinc-900">
		<h1 class="pt-10 text-7xl text-white">Experienced.</h1>
		<h2 class="mt-5 text-3xl text-white">
			To me, development is more than a career. It's a passion.
		</h2>
		<span class="absolute top-0 mx-auto mt-60 h-[500px] rounded border-2 border-white" />
	</section>
	<section
		class="grid h-full snap-center grid-cols-[2fr_1fr] bg-gradient-to-b from-zinc-900 to-zinc-800 pt-32 pr-20 dark:bg-gradient-to-b"
	>
		<div></div>
		<div>
			<h1 class="text-right text-7xl text-white">Inquisitive.</h1>
			<h2 class="text-right text-3xl text-gray-200">Through the outdoors, I find inspiration.</h2>
			<p class="mt-5 text-right text-lg text-white">
				I often receive the question, why? In a world that is so heavily focused on media
				consumption, why would I choose to focus on GIS? After all, <i>isn't geography boring?</i>
			</p>
			<p class="mt-5 text-right text-lg text-white">
				Those statements couldn't be further from the truth. There is nothing more dynamic than the
				world in which we live. Be it wars, natural disasters, famine, sickness, the world is
				constantly changing. Every time it does, we have an opportunity and a responsibility to
				analyze trends in this data, make sense of it all, and use it to improve our lives.
			</p>
		</div>
	</section>
	<section class="grid h-full snap-center grid-cols-[1fr_2fr] from-zinc-800 to-zinc-900 pt-32 pl-20 dark:bg-gradient-to-b">
		<div>
			<h1 class='text-7xl text-white text-left'>Determined.</h1>
			<h2 class='text-left text-3xl text-gray-200'>I've never given up, and I won't.</h2>
		</div>
	</section>
</main>
