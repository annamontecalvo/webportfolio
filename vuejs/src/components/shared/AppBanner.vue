<script>


export default {
	name: 'Home',

};
</script>

<template>
    <body>


	<section
		class="flex flex-col sm:justify-between items-center sm:flex-row mt-12 sm:mt-10"
	>
		<!-- Banner left contents -->
		<div class="w-full md:w-1/3 text-left">
			<h1
				class="font-general-semibold text-3xl md:text-3xl xl:text-4xl text-center sm:text-center text-ternary-light uppercase"
			>
				Anna Mae Montecalvo.
			</h1>
            <p class="font-general-semibold text-sm text-center sm:text-center text-ternary-light">Portfolio</p>



		</div>

		<!-- Banner right illustration -->
		<div class="w-25 md:w-2/3 text-right float-right">
			<img

				src="@/assets/images/anna.jpg"
				alt="Anna" class="anna"
			/>

		</div>
	</section>
    </body>
</template>

<style scoped>
.anna{
    width: 250px;
     height: 250px;
    margin-left: 20%;
}

</style>
