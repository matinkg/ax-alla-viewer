<template>
	<v-app>
		<v-main class="blue lighten-5">
			<v-container class="d-flex justify-center">
				<v-col class="white rounded-lg elevation-3" cols="12" md="8">
					<div class="text-justify">
						سلام! 👋 من به شما کمک میکنم فیلم های آلا رو با مدیا پلیر بهتری مشاهده کنین! 😎 لطفا لینک کلیپ رو بهم بده :
					</div>

					<div class="mt-2 pa-2 inline-input-button" style="position: relative;">
						<v-text-field label="لینک آلا :" placeholder="لطفا لینک آلا رو اینجا وارد کن" outlined hide-details="true"></v-text-field>
						<v-btn depressed color="primary" style="position: absolute; left: 18px; top: 18px;">
							مشاهده
						</v-btn>
					</div>

					<axone></axone>

					<a href="https://github.com/axone13/ax-alla-viewer" class="no-link">
						<div class="text-center text-caption" dir="ltr" style="margin-top: -5px">
							<v-icon style="color: #999;">mdi-github</v-icon>
							<span style="vertical-align: middle; color: #999;" class="ml-1">github</span>
						</div>
					</a>
				</v-col>
			</v-container>
		</v-main>
	</v-app>
</template>

<script>
import Axone from "./components/Axone";

export default {
	name: "App",

	components: {
		Axone,
	},

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

body,
.v-application {
	font-family: Iransans !important;
}

.inline-input-button input {
	padding-left: 95px !important;
}

.no-link{
    text-decoration: none;
    color: inherit;
}
</style>
