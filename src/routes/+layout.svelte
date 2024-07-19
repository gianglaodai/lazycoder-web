<script>
	import '../app.css';
</script>

<header class="bg-gray-800 p-4 text-white shadow-md">
	<div class="container mx-auto flex items-center justify-between">
		<h1 class="text-2xl font-bold">
			<a href="/"> Lazycoder </a>
		</h1>
		<nav class="space-x-4">
			<a href="/demo" class="hover:text-gray-400">Live Demo</a>
			<a href="/blog" class="hover:text-gray-400">Blog</a>
		</nav>
	</div>
</header>

<slot />
