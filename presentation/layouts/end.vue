<template>
	<div class="slidev-layout end">
		<a
			href="https://www.estg.ipp.pt"
			target="_blank"
			class="
				abs-tl
				top-6
				left-6
				opacity-50
				!hover:opacity-100
				no-border no-decoration
				shadow-none
			"
		>
			<img src="/media/logos/pporto.png" class="w-75px" alt="P.Porto" />
		</a>

		<DarkToggle class="abs-tr right-6 top-6" />

		<h1 class="text-white text-2xl text-center font-bold no-mb">
			Obrigado
		</h1>
		<h3 class="mt-1">pelo tempo disponibilizado!</h3>

		<div class="abs-br mx-6 my-6">
			<span
				@click="$slidev.nav.prev"
				class="arrow-container cursor-pointer text-white"
				hover="bg-altBlue bg-opacity-75 text-white"
			>
				<carbon:chevron-left class="inline" />
			</span>
		</div>
	</div>
</template>

<style scopde lang="postcss">
.slidev-layout.end {
	@apply text-white text-xl tracking-widest h-full text-center grid place-content-center select-none bg-blend-overlay;
	background-image: url('/media/backgrounds/athlete.jpeg');
	background-size: cover;
	background-position: center;
	background-repeat: no-repeat;
	background-color: rgba(0, 0, 0, 0.85);
}

.slidev-layout.end h3 {
	color: #fff;
	opacity: 1;
}
</style>
