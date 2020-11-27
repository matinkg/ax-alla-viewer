<template>
	<v-app>
		<v-main class="blue lighten-5">
			<v-container class="d-flex justify-center">
				<v-col class="white rounded-lg" cols="8">
					سلام! من به شما کمک میکنم فیلم های آلا رو با پلیر بهتری مشاهده کنین! لطفا جهت ادامه لینک آلا رو بهم بده :
				</v-col>
			</v-container>
		</v-main>
	</v-app>
</template>

<script>
//import HelloWorld from './components/HelloWorld';

export default {
	name: "App",

	components: {},

	data: () => ({}),
};
</script>

<style>
@font-face {
	font-family: "Iransans";
	src: url("./assets/fonts/IRANSansWeb.woff") format("woff"),
		url("./assets/fonts/IRANSansWeb.ttf") format("truetype");
	font-style: normal;
	font-weight: 400;
}

@font-face {
	font-family: "IransansNum";
	src: url("./assets/fonts/IRANSansWebNum.woff") format("woff"),
		url("./assets/fonts/IRANSansWebNum.ttf") format("truetype");
	font-style: normal;
	font-weight: 400;
}

body , .v-application{
	font-family: Iransans !important;
}
</style>
