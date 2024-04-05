<script>


import ContactDetails from '@/components/contact/ContactDetails.vue';

export default {
	components: {

		ContactDetails,
	},
	data: () => {
		return {
			contacts: [
				{
					id: 1,
					name: 'Agus, Lapu-lapu, Philippines',
					icon: 'map-pin',
				},
				{
					id: 2,
					name: 'annamaemontecalvo@gmail.com',
					icon: 'mail',
				},
				{
					id: 3,
					name: '09956711226',
					icon: 'phone',
				},
			],
		};
	},

};
</script>

<template>
	<div
		class="container mx-auto flex flex-col-reverse md:flex-row py-5 md:py-10 md:mt-10 "
	>


		<!-- Contact details -->
		<ContactDetails :contacts="contacts" />
	</div>
</template>
