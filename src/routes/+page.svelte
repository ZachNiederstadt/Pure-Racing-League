<script lang="ts">
	import { Button } from '$lib/components/ui/button';
</script>

<title> Pure Racing League </title>

<div class="ml-10 mr-10 pt-10">
	<h1 class="font-orbitron text-2xl tracking-widest md:text-4xl">Fastest GT League</h1>
	<h1 class="font-md font-orbitron text-2xl tracking-widest md:text-4xl">in North America</h1>
	<p class="mb-10 pt-5 font-ubuntu text-xs tracking-widest md:text-lg">
		World Series class driving, with close battles and fun rivalries
	</p>
</div>

<div
	class="mx-auto mt-10 flex justify-center pl-10 pr-10 pt-10 text-center font-orbitron tracking-wider md:text-xl"
>
	<h2>Current and former World Series drivers involved</h2>
</div>
<div
	class="drive m-5 mx-auto flex grid auto-cols-auto auto-rows-auto grid-cols-2 p-10 sm:grid-cols-3 sm:justify-center md:grid-cols-6 lg:grid-cols-6"
>
	<div class="align-center container flex grid items-center justify-center p-3">
		<img class="drivers" src="/drivers/calen.jpg" />
		<p class="name flex justify-center pt-2 font-ubuntu tracking-widest">Calen Roach</p>
	</div>
	<div class="align-center container flex grid items-center justify-center p-3">
		<img class="drivers" src="/drivers/robby.jpg" />
		<p class="name flex justify-center pt-2 font-ubuntu tracking-widest">Robby Heck</p>
	</div>
	<div class="align-center container flex grid items-center justify-center p-3">
		<img class="drivers" src="/drivers/mehdi.jpg" />
		<p class="name flex justify-center pt-2 font-ubuntu tracking-widest">Mehdi Hafidi</p>
	</div>
	<div class="align-center container flex grid items-center justify-center p-3">
		<img class="drivers" src="/drivers/cyrus.jpg" />
		<p class="name flex justify-center pt-2 font-ubuntu tracking-wide">Cyrus Cross</p>
	</div>
	<div class="align-center container flex grid items-center justify-center p-3">
		<img class="drivers" src="/drivers/dean.jpg" />
		<p class="name flex justify-center pt-2 font-ubuntu tracking-widest">Dean Hedlt</p>
	</div>
	<div class="align-center container flex grid items-center justify-center p-3">
		<img class="drivers" src="/drivers/andrew.jpg" />
		<p class="name flex justify-center pt-2 font-ubuntu tracking-widest">Andrew Lee</p>
	</div>
</div>
<div class="flex justify-center pb-12">
	<Button href="/about" class="flex justify-center font-ubuntu">About Us</Button>
</div>

<style>
	h1,
	h2 {
		font-weight: 800;
	}
	h1 {
	}
	p {
		font-weight: 400;
	}
	.drivers {
		object-fit: cover;
		width: 75px;
		height: 75px;
	}
	.name {
		font-size: x-small;
		font-weight: 500;
	}
	.drive {
		max-width: 80vh;
	}
</style>
