<script>
	import '../app.css';
</script>

<nav class="fixed right-0 mt-4 mr-12 flex space-x-6 text-xl text-white">
	<a>Projects</a>
	<a>Blog</a>
	<a href="./static/Resume.pdf" download>Resume</a>
</nav>

<span class='fixed bottom-10 animate-bounce bg-white dark:bg-slate-800 p-2 w-10 h-10 ring-1 ring-slate-900/5 dark:ring-slate-200/20 shadow-lg rounded-full inline-flex items-center justify-center'>
	<svg fill='none' stroke-linecap='round' stroke-linejoin='round' stroke-width='2' viewBox='0 0 24 24' stroke='currentColor' width='32px' height='32px' class='mx-auto text-red-500'>
		<path d="M19 14l-7 7m0 0l-7-7m7 7V3"></path>
	</svg>
</span>
<slot />
