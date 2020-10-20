<template>
	<section class="landing-container">
		<div class="landing-wrapper">
			<img src="../assets/images/logo.png" alt="logo" class="logo" />
			<h1 class="title">Devcast: The Lead’s Story</h1>
			<p class="description">
				Devcast is a podcast on DSC Leads and Google Developer Experts that is
				proudly organized by Developer Student Club Loyola from the Ateneo de
				Manila University. Tackling the experiences of coming into technology
				and growing as a Developer Student Clubs lead, Devcast aims to do this
				and that and this and that and more words.
			</p>
		</div>
		<div class="illustration landing-wrapper">
			<img src="../assets/images/illustration.png" alt="illustration" />
		</div>
	</section>
</template>

<script></script>

<style scoped>
.logo {
	width: 90px;
	height: 90px;
	margin-bottom: 30px;
}

.landing-container {
	display: flex;
	justify-content: space-between;
}

.title {
	font-style: normal !important;
	font-weight: bold !important;
	font-size: 36px !important;
	line-height: 120% !important;
	color: #000000 !important;
	margin-bottom: 16px !important;
}

.description {
	font-style: normal;
	font-weight: normal;
	font-size: 16px;
	line-height: 28px;
}

.landing-wrapper {
	width: 45%;
}

.illustration {
	display: flex;
	align-items: center;
	justify-content: center;
}

@media screen and (max-width: 1024px) {
	.landing-wrapper {
		width: 40%;
	}
}

@media screen and (max-width: 900px) {
	.landing-wrapper {
		width: auto;
	}

	.landing-container {
		display: flex;
		justify-content: center;
		flex-direction: column;
	}
}

@media screen and (max-width: 540px) {
	.illustration img {
		width: 100%;
	}

	.title {
		font-size: 24px !important;
	}
}
</style>
