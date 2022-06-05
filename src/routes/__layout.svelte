<script>
	import '../app.css';
</script>

<nav class="fixed right-0 mt-4 mr-12 flex space-x-6 text-xl text-white">
	<a>Projects</a>
	<a href="https://blog.johnradojevich.dev">Blog</a>
	<a href="./static/Resume.pdf" download>Resume</a>
</nav>

<span
	class="fixed bottom-10 inline-flex h-10 w-10 animate-bounce items-center justify-center rounded-full bg-white p-2 shadow-lg ring-1 ring-slate-900/5 dark:bg-slate-800 dark:ring-slate-200/20"
>
	<svg
		fill="none"
		stroke-linecap="round"
		stroke-linejoin="round"
		stroke-width="2"
		viewBox="0 0 24 24"
		stroke="currentColor"
		width="32px"
		height="32px"
		class="mx-auto text-red-500"
	>
		<path d="M19 14l-7 7m0 0l-7-7m7 7V3" />
	</svg>
</span>
<slot />
