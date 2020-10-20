<template>
	<v-app>
		<v-main>
			<div class="wrapper"><Landing /></div>
		</v-main>
		<Footer />
	</v-app>
</template>

<script>
import Landing from '@/components/Landing'
import Footer from '@/components/Footer'

export default {
	components: {
		Landing,
		Footer,
	},
}
</script>

<style>
@font-face {
	font-family: 'Google Sans';
	src: url('./assets/fonts/googlesans-regular.woff') format('woff');
	font-weight: normal;
}
@font-face {
	font-family: 'Google Sans';
	src: url('./assets/fonts/googlesans-medium.woff') format('woff');
	font-style: normal;
	font-weight: 500;
}

html,
body,
* {
	margin: 0;
	padding: 0;
	font-family: 'Google Sans', Helvetica, Arial, sans-serif;
}

.wrapper {
	padding: 60px 0 !important;
	width: 75% !important;
	margin: auto !important;
}

@media screen and (max-width: 768px) {
	.wrapper {
		padding: 30px 0 !important;
		width: 75% !important;
		margin: auto !important;
	}
}
</style>
