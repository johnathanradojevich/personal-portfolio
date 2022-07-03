<div class='grid grid-cols-1 h-screen bg-black text-white'>
	<div class='place-self-center'>
		<h1 id='name' class='text-6xl font-bold font-Gemunu tracking-widest'></h1>
		<h2 class='font-Gemunu text-2xl'>Hey! 😎 I'm a Full-Stack Software Developer @ Terracon 🌎</h2>
		<div class='mt-10'>
			<a href='./static/resume.pdf' class='border-2 p-2 pt-1.5'>Resume</a>
			<a href='https://github.com/johnathanradojevich' class='border-2 p-2 pt-1.5'>GitHub</a>
			<a href='https://www.linkedin.com/in/john-radojevich' class='border-2 p-2 pt-1.5'>LinkedIn</a>
			<a href='mailto:johnathanradojevich@gmail.com' class='border-2 p-2 pt-1.5'>Email</a>
			<a href='https://blog.johnradojevich.dev' class='border-2 p-2 pt-1.5'>Blog</a>
		</div>
	</div>
</div>

<script>

	import { onMount } from 'svelte';

	onMount(() => {

		const text = 'John Radojević';
		const header = document.getElementById('name');

		header.textContent = text[0];
		let typingIdx = 0;

		const interval = setInterval(() => {
			++typingIdx;
			header.textContent = text.slice(0, typingIdx);
			if (typingIdx >= text.length) {
				clearInterval(interval);
			}
		}, 60);
	});

</script>