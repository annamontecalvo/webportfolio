<script>
// export default {
// 	props: ['showModal', 'isOpen'],
// };
</script>

<template>
    <body>


	<!-- Header links -->
	<div
		:class="isOpen ? 'block' : 'hidden'"
		class="m-0 sm:ml-4 mt-5 sm:mt-3 sm:flex p-5 sm:p-0 justify-center items-center "
	>
    <router-link
    to="/"
    class="font-general-medium block text-left text-lg font-medium text-primary-light   sm:mx-4 mb-2 sm:py-2 border-t-2 pt-3 sm:pt-2 sm:border-t-0 border-primary-light "
    aria-label="Home"
    >Home</router-link
>

		<router-link
			to="/about"
			class="font-general-medium block text-left text-lg font-medium text-primary-light   sm:mx-4 mb-2 sm:py-2 border-t-2 pt-3 sm:pt-2 sm:border-t-0 border-primary-light "
			aria-label="About Me"
			>About Me</router-link
		>
		<router-link
			to="/contact"
			class="font-general-medium block text-left text-lg font-medium text-primary-light   sm:mx-4 mb-2 sm:py-2 border-t-2 pt-3 "
			aria-label="Contact"
			>Contact</router-link
		>
		<div
			class="border-t-2 pt-3 sm:pt-0 sm:border-t-0 "
		>

		</div>
	</div>
    </body>
</template>

<style scoped>

</style>
