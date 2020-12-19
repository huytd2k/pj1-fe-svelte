<script lang="typescript">
	let name: string = "World";
	import Tailwind from "./tailwind.svelte";
</script>

<style>
</style>

<div class="App">
	<header class="App-header">
		<Tailwind />
		<div class="shadow-md">Hello {name}</div>
	</header>
</div>
