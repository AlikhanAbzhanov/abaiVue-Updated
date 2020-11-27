<!-- @format -->

<template>
	<div class="head">
		<div class="about-project">О проекте</div>
		<div class="founders-content third">
			<div>
				<p>
					Ab.ai - крупнейшая в Казахстане платформа для менторского обучения
					программированию. Этот проект объединяет учеников и учителей
					заинтересованных в IT со всех точек страны.
					<br />
					<br />
					Ab.ai был создан с целью популяризации профессии будущего путём
					создания сообщества единомышленников. Мы искренне верим, что Ab.ai
					будет способствовать усилению конкурентоспособности Казахстана в
					мировом рынке информационных технологий.
					<br />
					<br />
					Самое главное, любой желающий может стать частью нашего сообщества
					абсолютно бесплатно выбрав путь ученика или ментора. .
				</p>
			</div>
			<div>
				<img src="../../DESKTOP/КАРТИНКА-1.png" alt="" />
			</div>
		</div>
	</div>
</template>

<style scoped>
	@media only screen and (min-width: 1100px) {
	
		.about-project{
			text-align: center;
		}
		* {
			font-family: "Montserrat", sans-serif;
		}
		.about-project {
			font-family: "Montserrat", sans-serif;
			font-size: 30px;
			font-weight: bold;
			margin-top: 10%;
		}
		.third {
			margin-top: 2%;
		}
		.second {
			margin-top: 6%;
		}
		.founders-content {
			margin-top: 5%;
			display: flex;
		}
		.founders-content > div > img {
			margin-left: 40%;
			width: 60%;
			height: 80%;
		}
		.founders-content > div {
			width: 50%;
		}
		.head {
			width: 90%;
			margin-left: 4.5%;
			margin-top: 2%;
		}
		.founders {
			font-family: "Montserrat", sans-serif;
			font-size: 30px;
			font-weight: bold;
		}
	}
	@media only screen and (min-width: 801px){
		.about-project{
			text-align: center;
		}
	* {
			font-family: "Montserrat", sans-serif;
		}
		.about-project {
			font-family: "Montserrat", sans-serif;
			font-size: 25px;
			font-weight: bold;
			margin-top: 10%;
		}
		.third {
			margin-top: 2%;
		}
		.second {
			margin-top: 6%;
		}
		.founders-content {
			display: flex;
		}
		.founders-content > div > img {
			margin-left: 10%;
			width: 90%;
			height: 80%;
		}
		.founders-content > div {
			width: 50%;
		}
		.head {
			width: 90%;
			margin-left: 4.5%;
			margin-top: 2%;
		}
		.founders {
			font-family: "Montserrat", sans-serif;
			font-size: 25px;
			font-weight: bold;
		}
}


	@media only screen and (max-width: 800px) {
		* {
			font-family: "Montserrat", sans-serif;
		}
		.about-project {
			font-family: "Montserrat", sans-serif;
			font-size: 25px;
			font-weight: bold;
			margin-top: 10%;
            text-align: center;
		}
		.third {
			margin-top: 2%;
		}
		.second {
			margin-top: 6%;
		}
		.founders-content {
			display: flex;
            flex-direction: column;
		}
		.founders-content > div > img {
			width: 100%;
			height: 100%;
		}
		.founders-content > div {
			width: 100%;
            text-align: center;
		}
		.head {
			width: 90%;
			margin-left: 4.5%;
			margin-top: 2%;
		}
		.founders {
			font-family: "Montserrat", sans-serif;
			font-size: 30px;
			font-weight: bold;
		}
	}
</style>
