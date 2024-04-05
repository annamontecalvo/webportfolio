<script>
export default {
	setup() {
		return {
			bios: [
				{
					id: 1,
					bio:
						'Name: Anna Mae Montecalvo',
				},
				{
					id: 2,
					bio:
						'From: Ibabao, Agus LapuLapu City 20 years of age Studied Bachelor of science in information technology',
				},
			],
		};
	},
};
</script>

<template>
	<div class="block sm:flex sm:gap-10 mt-10 sm:mt-20">
		<!-- About profile image -->
		<div class="w-full sm:w-1/4 mb-7 sm:mb-0">
			<img
				src="@/assets/images/anna.jpg"
				class="rounded-xl w-96"
				alt="anna"
			/>
		</div>

		<!-- About details -->
		<div class="w-full sm:w-3/4 text-left">
			<p
				v-for="bio in bios"
				:key="bio.id"
				class="font-general-regular mb-4 text-ternary-light dark:text-ternary-light text-lg"
			>
				{{ bio.bio }}
			</p>
		</div>
	</div>
</template>
