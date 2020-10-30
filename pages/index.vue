<template>
	<div class="main text-center flex flex-col items-center justify-center">
		<!-- <logo /> -->
		<h1 class="title"><< n u x t - u p s k i l l >></h1>
		<h2 class="subtitle">etc etc etc</h2>
	</div>
</template>

<script>
	// import Logo from '~/components/Logo.vue'
	export default {
		// components: {
		//   Logo
		// },
		head() {
			return {
				script: [{ src: 'https://identity.netlify.com/v1/netlify-identity-widget.js' }]
			}
		}
	}
</script>