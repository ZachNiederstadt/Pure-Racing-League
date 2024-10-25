<script>
	import '../app.css';
	let { children } = $props();
</script>

<div class="body">
	<main
		class=" bg flex h-lvh min-h-screen flex-col content-center justify-center bg-opacity-50 bg-center"
		style="background-image: url('/background.avif');"
	>
		<header class="border-gray-200 bg-white dark:bg-gray-900">
			<div class="mx-auto flex max-w-screen-xl flex-wrap items-center justify-between p-4">
				<a href="https://flowbite.com/" class="flex items-center space-x-3 rtl:space-x-reverse">
					<img alt="" class="flex w-[200px] pt-2" src="/logos/prl.jpg" />
					<!-- <img src="https://flowbite.com/docs/images/logo.svg" class="h-8" alt="Flowbite Logo" />
			<span class="self-center whitespace-nowrap text-2xl font-semibold dark:text-white"
				>Flowbite</span -->
				</a>
				<button
					data-collapse-toggle="navbar-default"
					type="button"
					class="inline-flex h-10 w-10 items-center justify-center rounded-lg p-2 text-sm text-gray-500 hover:bg-gray-100 focus:outline-none focus:ring-2 focus:ring-gray-200 md:hidden dark:text-gray-400 dark:hover:bg-gray-700 dark:focus:ring-gray-600"
					aria-controls="navbar-default"
					aria-expanded="false"
				>
				</button>
				<div class="hidden w-full md:block md:w-auto" id="navbar-default">
					<ul
						class="mt-4 flex flex-col rounded-lg border border-gray-100 bg-black p-4 font-medium md:mt-0 md:flex-row md:space-x-8 md:border-0 md:bg-white md:p-0 rtl:space-x-reverse dark:border-gray-700 dark:bg-black md:dark:bg-black"
					>
						<li>
							<a
								href="#"
								class="block rounded bg-blue-700 px-3 py-2 text-white md:bg-transparent md:p-0 md:text-blue-700 dark:text-white md:dark:text-blue-500"
								aria-current="page">Home</a
							>
						</li>
						<li>
							<a
								href="#"
								class="block rounded px-3 py-2 text-gray-900 hover:bg-gray-100 md:border-0 md:p-0 md:hover:bg-transparent md:hover:text-blue-700 dark:text-white dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent md:dark:hover:text-blue-500"
								>About</a
							>
						</li>
						<li>
							<a
								href="#"
								class="block rounded px-3 py-2 text-gray-900 hover:bg-gray-100 md:border-0 md:p-0 md:hover:bg-transparent md:hover:text-blue-700 dark:text-white dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent md:dark:hover:text-blue-500"
								>Schedule</a
							>
						</li>
						<li>
							<a
								href="#"
								class="block rounded px-3 py-2 text-gray-900 hover:bg-gray-100 md:border-0 md:p-0 md:hover:bg-transparent md:hover:text-blue-700 dark:text-white dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent md:dark:hover:text-blue-500"
								>Standings</a
							>
						</li>
						<li>
							<a
								href="#"
								class="block rounded px-3 py-2 text-gray-900 hover:bg-gray-100 md:border-0 md:p-0 md:hover:bg-transparent md:hover:text-blue-700 dark:text-white dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent md:dark:hover:text-blue-500"
								>Sign-Up</a
							>
						</li>
					</ul>
				</div>
			</div>
		</header>

		{@render children()}
		<footer class="sticky bottom-0 flex justify-center gap-2 pb-10">
			<a class="social" href="https://x.com/PureRacingGT">
				<img src="/sociallogos/x.png" />
			</a>
			<a class="social" href="https://discord.com/invite/asvZn6w3Tx">
				<img src="/sociallogos/discord.png" />
			</a>
			<a class="social" href="https://www.instagram.com/pure.racingleague/">
				<img src="/sociallogos/instagram.png" />
			</a>
		</footer>
	</main>
</div>

<style>
	.body {
		display: flex;
		flex-direction: column;
		height: 100dvh;
	}
	header {
		background-color: rgb(0, 0, 0);
		height: 77px;
	}

	main {
		background-color: #000000;
		flex: 1;
	}

	footer {
		padding-top: 15px;
		margin-top: auto;
		background-color: #000000;
		height: 0px;
	}
	.social {
		width: 30px;
	}
</style>
