<!-- @format -->
<template>
	<div class="block1">
		<div class="highmenu">
				<img src="../../DESKTOP/ЛОГО.png" alt="" width="100px" height="100px" id='kodekomek' @click="codekomek"/>
			<div id="about" @click="gotoform2">О проекте</div>
			<div id="about" @click="gotoform">Ученикам</div>
			<div id="about" @click="gotoform">Менторам</div>
			<div></div>
		</div>
		<div class="main">
			<div>
				<p>
					Обучение программированию
					<br />
					для учеников
					<br />
					от менторов
				</p>
				<div id="fordesk">
					Пройдите тернистый путь программиста вместе с Ab.ai и освойте профессию будущего максимально быстро!
				</div>
			</div>
			<img src="../../DESKTOP/КАРТИНКА.png" alt="" />
			<div id="formobile">
				Пройдите тернистый путь программиста вместе с Ab.ai и освойте
				<br />
				профессию будущего максимально быстро!
			</div>
		</div>

		<div class="btns">
			<button id="" @click="gotoform">
				Хочу стать
				<br />
				учеником/ментором
			</button>
			<button id="btn2" @click="gotoform2">
				<div>
					О проекте
				</div>
			</button>
			<br />
		</div>
		<div class="subtext">
			<div>
				Оставь заявку на участие и получи гайд
				<br />
				по дальнейшему развитию в этой сфере
			</div>
			<img src="../../DESKTOP/ГАЙД.png" alt="" />
		</div>
		<div class="subtextdesk">
			<div>
				Оставь заявку на участие
				<br />
				и получи гайд по дальнейшему
				<br />
				развитию в этой сфере
			</div>
			<img src="../../DESKTOP/ГАЙД.png" alt="" />
		</div>
	</div>
</template>
<style scoped>
	@media only screen and (min-width: 1100px) {
		.subtextdesk {
			display: none;
		}
		#formobile {
			display: none;
		}
		#about:hover {
			transition: 0.2s;
			font-size: 23px;
		}
		.block1 {
			font-family: "Montserrat", sans-serif;
			width: 90%;
			margin-left: 5%;
		}

		.bottom-text {
			margin-top: -7%;
			font-size: 16px;
			display: flex;
		}

		.highmenu {
			display: flex;
		}
		.highmenu > div {
			font-size: 20px;
			margin-top: 1.5%;
			margin-left: 10%;
		}
		.highmenu > div:first-child {
			margin-left: 5%;
		}
		a{
			text-decoration: none;
		}
		.highmenu > a > img {
			
		
		}
		.main {
			display: flex;
		}
		.main > img {
			width: 40%;
			height: 40%;
		}

		.main > div > p {
			font-style: normal;
			font-weight: bold;
			font-size: 50px;
			line-height: 61px;
		}
		.btns {
		}
		.btns > button {
			margin-top: -5%;
			width: 30%;
		}
		.btns > button:first-child {
			font-family: "Montserrat", sans-serif;

			background-color: #ffb355;
			border: none;
			border-radius: 10vh;
			font-style: normal;
			font-weight: 600;
			font-size: 24px;
			line-height: 32px;
			/* or 133% */

			text-align: center;
		}
		#btn2 {
			padding-top: 0%;
			width: 30%;

			border-radius: 10vh;

			border-color: #ffb355;
			margin-left: 3%;
			font-style: normal;
			font-weight: 600;
			font-size: 24px;
			line-height: 32px;
			text-align: center;
		}

		.subtext {
			margin-top: 5%;
			display: flex;
		}
		img {
			width: 10%;
			height: 10%;
			padding-left: 5%;
		}
	}

	@media only screen and (min-width: 801px) {
		.subtextdesk {
			display: none;
		}
		#formobile {
			display: none;
		}
		#about:hover {
			transition: 0.2s;
			font-size: 20px;
		}
		.block1 {
			font-family: "Montserrat", sans-serif;
			width: 90%;
			margin-left: 5%;
		}

		.bottom-text {
			margin-top: -7%;
			font-size: 14px;
			display: flex;
		}

		.highmenu {
			display: flex;
		}
		.highmenu > div {
			font-size: 17px;
			padding-top: 2.2%;
			margin-left: 10%;
		}
		.highmenu > div:first-child {
			margin-left: 5%;
		}
		.highmenu > img {
			width: 10%;
			height: 10%;
		}
		.main {
			display: flex;
		}
		.main > img {
			width: 40%;
			height: 40%;
		}

		.main > div > p {
			font-style: normal;
			font-weight: bold;
			font-size: 40px;
			line-height: 50px;
		}
		.btns {
			margin-top: 5%;
			display: flex;
		}
		.btns > button {
			width: 30%;
		}
		.btns > button:first-child {
			font-family: "Montserrat", sans-serif;

			background-color: #ffb355;
			border: none;
			border-radius: 10vh;
			font-style: normal;
			font-weight: 600;
			font-size: 20px;
			line-height: 25px;
			/* or 133% */

			text-align: center;
		}
		#btn2 {
			padding-top: 0%;
			width: 30%;

			border-radius: 10vh;

			border-color: #ffb355;
			margin-left: 3%;
			font-style: normal;
			font-weight: 600;
			font-size: 24px;
			line-height: 32px;
			text-align: center;
		}

		.subtext {
			margin-top: 5%;
			display: flex;
		}
		img {
			width: 10%;
			height: 10%;
			padding-left: 5%;
		}
	}

	@media only screen and (max-width: 800px) {
		#about {
			display: none;
		}
		.highmenu > img {
			width: 30%;
			height: 30%;
		}
		.block1 {
			font-family: "Montserrat", sans-serif;
		}
		.main {
			display: flex;
			flex-direction: column;
		}
		.main > img {
			width: 100%;
			height: 100%;
		}

		.main > div > p {
			font-style: normal;
			font-weight: bold;
			font-size: 30px;
			line-height: 41px;
			text-align: center;
		}
		#formobile {
			font-size: 20px;
			margin-top: 5%;
			display: flex;
			text-align: center;
		}
		#fordesk {
			display: none;
		}

		.btns {
			margin-top: 5%;
			display: flex;
			flex-direction: column;
		}
		.btns > button {
		}
		.btns > button:first-child {
			height: 10vh;
			width: 70%;
			margin-left: 15%;
			font-family: "Montserrat", sans-serif;
			text-align: center;
			background-color: #ffb355;
			border: none;
			font-style: normal;
			font-weight: 600;
			font-size: 20px;
			/* or 133% */
			border-radius: 10vh;

			text-align: center;
		}
		#btn2 {
			margin-left: 15%;

			width: 70%;
			text-align: center;
			margin-top: 5%;
			height: 10vh;
			border-radius: 10vh;

			border-color: #ffb355;
			font-style: normal;
			font-weight: 600;
			font-size: 20px;
		}
		.subtext {
			display: none;
		}
		.subtextdesk {
			font-size: 20px;
			margin-top: 0%;
			display: flex;
			flex-direction: column;
			text-align: center;
		}
		.subtextdesk > img {
			width: 30%;
			height: 30%;
			padding-left: 39%;
		}
	}
</style>
<script>


	export default {
	
		name: "block1",

		methods: {
			gotoform() {
				let r = "gotoform";
				this.$emit("formidti", r);
			},
			gotoform2() {
				this.$emit("gotoform2");
			},
			codekomek(){
				window.open("https://code-komek.info")
			}
		},
	};
</script>
