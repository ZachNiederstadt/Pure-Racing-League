<script>
	import '../app.css';
	import { Select } from 'bits-ui';
	import * as DropdownMenu from '$lib/components/ui/dropdown-menu';
	import { Button } from '$lib/components/ui/button/index.js';

	let { children } = $props();

	// const pages = [{ label: 'Schedule' }, { label: 'Standings' }, { label: 'About' }];
</script>

<main
	class="bg flex h-dvh min-h-screen flex-col content-center justify-center bg-opacity-50 bg-center"
	style="background-image: url('/background.avif');"
>
	<header class="sticky mb-5 mt-0 h-[77px] border-gray-200 bg-black pl-3 pr-2">
		<div class="max-w-screen-xxl mx-auto flex flex-wrap items-center justify-between p-4 pb-5">
			<a href="/" class="flex items-center space-x-3 rtl:space-x-reverse">
				<img alt="" class="flex w-[200px] pt-2" src="/logos/prl.jpg" />
				<!-- <img src="https://flowbite.com/docs/images/logo.svg" class="h-8" alt="Flowbite Logo" />
			<span class="self-center whitespace-nowrap text-2xl font-semibold dark:text-white"
				>Flowbite</span -->
			</a>
			<DropdownMenu.Root class="bg-black">
				<DropdownMenu.Trigger asChild let:builder>
					<Button variant="variant" builders={[builder]}>
						<svg
							class="h-5 w-5"
							aria-hidden="true"
							xmlns="http://www.w3.org/2000/svg"
							fill="none"
							viewBox="0 0 17 14"
						>
							<path
								stroke="currentColor"
								stroke-linecap="round"
								stroke-linejoin="round"
								stroke-width="2"
								d="M1 1h15M1 7h15M1 13h15"
							/>
						</svg></Button
					>
				</DropdownMenu.Trigger>
				<DropdownMenu.Content class="w-56">
					<DropdownMenu.Label>Menu</DropdownMenu.Label>
					<DropdownMenu.Separator />

					<DropdownMenu.Item href="/schedule">Schedule</DropdownMenu.Item>
					<DropdownMenu.Item href="/standings">Standings</DropdownMenu.Item>
					<DropdownMenu.Item href="/about">About</DropdownMenu.Item>
				</DropdownMenu.Content>
			</DropdownMenu.Root>
		</div>
	</header>

	<div class="mt-0 w-full overflow-y-scroll">
		{@render children()}
	</div>
	<footer class="sticky bottom-0 flex justify-center gap-5 pb-10">
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

<style>
	footer {
		padding-top: 15px;
		margin-top: auto;
		background-color: #000000;
		height: 0px;
	}
	.social {
		width: 27px;
	}
</style>
