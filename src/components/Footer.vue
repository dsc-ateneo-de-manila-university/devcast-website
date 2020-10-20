<template>
	<footer>
		<div id="questions" class="container">
			<h2>Questions?</h2>
			<p>Contact us through our social media accounts</p>
			<social-icons color="black"></social-icons>
			<p>
				Or email us at
				<a href="mailto:dsc.ateneo@gmail.com">dsc.ateneo@gmail.com</a>.
			</p>
			<hr />
			<div class="row align-items-center justify-content-between">
				<div class="col-12 col-md-6">
					<router-link to="/">
						<img
							src="../assets/images/logo.svg"
							alt="Developer Student Clubs Loyola logo"
						/>
					</router-link>
				</div>
				<div class="col-12 col-md-6">
					<small>
						© 2020 Developer Student Clubs Loyola. All Rights Reserved.
					</small>
				</div>
			</div>
		</div>
	</footer>
</template>

<script>
import SocialIcons from './SocialIcons'

export default {
	components: {
		SocialIcons,
	},
}
</script>

<style scoped>
footer {
	padding: 40px 32px;
	border-top: 1px solid #eaeaea;
}

#questions {
	flex-direction: column;
	text-align: left;
}

#questions a {
	color: #4285f4;
}

h6 {
	font-size: 16px;
	line-height: 20px;
	margin-bottom: 8px;
	font-weight: 500;
}

ul {
	list-style: none;
}

li > a {
	line-height: 30px;
	font-size: 15px;
}

small {
	font-size: 14px;
	color: #828282;
}

hr {
	border: none;
	height: 1px;
	background-color: #eaeaea;
	color: #eaeaea;
	margin: 20px 0 40px;
}

.list {
	padding-top: 10px;
	padding-bottom: 10px;
}

.list hr {
	margin: 0 0 20px;
	width: 30px;
}

.row:last-child div:last-child {
	text-align: right;
}

@media screen and (max-width: 767px) {
	footer {
		padding-bottom: 100px;
	}

	footer,
	.row:last-child div:last-child,
	.row:last-child div {
		text-align: center;
	}

	img {
		width: 100%;
		margin-bottom: 10px;
	}

	#questions {
		padding-top: 35px;
		padding-bottom: 35px;
	}

	footer > div.container {
		padding-left: 0 !important;
		padding-right: 0 !important;
	}

	.list hr {
		margin: 0 auto 20px;
	}
}

.blue {
	border-bottom: 2px solid #4285f4;
}

.red {
	border-bottom: 2px solid #ea4335;
}

.yellow {
	border-bottom: 2px solid #fbbc04;
}

.green {
	border-bottom: 2px solid #0f9d58;
}
</style>
