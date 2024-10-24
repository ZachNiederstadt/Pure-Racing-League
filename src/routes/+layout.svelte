<script>
	import '../app.css';
	let { children } = $props();
</script>

<img class="w-[100px]" src="/logos/prl.jpg" />
<nav>my cool menu</nav>
{@render children()}
