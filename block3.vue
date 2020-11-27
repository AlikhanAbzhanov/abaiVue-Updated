<!-- @format -->

<template>
	<div class="head">
		<div class="founders">Основатели проекта</div>
		<div class="founders-content">
			<div>
				<p id="p">
					<strong>Аманмырза Жүсіпхан</strong>
					<br />
					<br />
					Я являюсь основателем Волонтерской Организации "AB Volunteers". Ab.ai
					является одной из веток организации
					<br />
					<br />
					В 15 лет я начал изучать глобальные проблемы
					<br />
					и проводил исследования. В итоге, я понял, что многие проблемы
					решаются с помощью технологий.
					<br />
					<br />

					После ситуации с COVID-19 не у всех есть возможность позволить себе
					курсы по программированию. Тем не менее, в нашей стране много
					талантливых программистов, которые могут помочь решить эту проблему.
					<br />
					<br />

					Также, у многих детей появились ноутбуки благодаря различным
					программам. Я бы хотел помочь им в новом направлении и развивать IT в
					селах. После школьных занятий, это было бы хорошим времяпровождением.
				</p>
			</div>

			<img src="../../DESKTOP/ФОТО АМАНМЫРЗЫ.png" alt="" />
		</div>

		<div class="founders-content second">
			<div>
				<p>
					<strong>Абжанов Алихан</strong>
					<br />
					<br />
					Я активно увлекаюсь программированием с 13 лет интересуясь разными
					направлениями этой профессии, в особенности проблемами искусственного
					интеллекта.
					<br />
					<br />

					Больше всего нравятся языки программирования Python, C++ и Java.
					<br />
					<br />

					Также мне очень нравится заниматься спортом, в частности фехтованием.
					<br />
					<br />

					Я являюсь обладателем призовых мест в республиканских конкурсах и
					соревнованиях по информатике и фехтованию.
					<br />
					<br />

					Для яркого будущего, я бы искренне хотел сделать собственный вклад в
					развитие технологической отрасли в Казахстане, и в первую очередь, я
					считаю что нам нужно помогать другу другу в изучении современных
					технологий.
				</p>
			</div>

			<img src="../../DESKTOP/ФОТО АЛИХАНА.png" alt="" />
		</div>
	</div>
</template>

<style scoped>
	@media only screen and (min-width: 1100px) {
		#namemobile {
			display: none;
		}
		* {
			font-family: "Montserrat", sans-serif;
		}
		.about-project {
			font-family: "Montserrat", sans-serif;
			font-size: 30px;
			font-weight: bold;
			margin-top: 0%;
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
		.founders-content > img {
			margin-left: 20%;
			border-radius: 10vh;
			width: 30%;
			height: 70vh;
		}

		.founders-content > div {
			width: 50%;
		}
		.founders-content > div >p{
			font-size: 27px;
		}
		.head {
			width: 90%;
			margin-left: 4.5%;
			margin-top: 4%;
		}
		.founders {
			text-align: center;
			font-family: "Montserrat", sans-serif;
			font-size: 30px;
			font-weight: bold;
		}
	}

	@media only screen and (min-width: 801px) {
			.founders-content > img {
			margin-left: 20%;
			border-radius: 10vh;
			width: 30%;
			height: 70vh;
		}
		#namemobile {
			display: none;
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
		.founders-content > div >p{
			font-size: 20px;
		}
	
		.founders-content > div > img {
			border-radius: 10vh;

			margin-left: 60%;
			width: 120%;
			height: 50%;
		}

		.founders-content > div {
			width: 50%;
		}
		.head {
			width: 90%;
			margin-left: 4.5%;
			margin-top: 10%;
		}
		.founders {
			text-align: center;
			font-family: "Montserrat", sans-serif;
			font-size: 25px;
			font-weight: bold;
		}
	}
	@media only screen and (max-width: 600px) {

		* {
			font-family: "Montserrat", sans-serif;
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
		.founders-content > img {
			border-radius: 10vh;

			margin-left: 25%;
			width: 40vw;
			height: 40vh;
		}

		.founders-content > div > div > p {
			text-align: center;
		}

		.founders-content > div {
			text-align: center;
			font-size: 20px;
		}
		.head {
			width: 90%;
			margin-left: 4.5%;
			margin-top: 5%;
		}
		.founders {
			font-family: "Montserrat", sans-serif;
			font-size: 25px;
			font-weight: bold;
			text-align: center;
		}
	}

		@media only screen and (max-width: 800px) {

	* {
			font-family: "Montserrat", sans-serif;
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
		.founders-content > img {
			border-radius: 10vh;

			margin-left: 25%;
			width: 40vw;
			height: 50vh;
		}

		.founders-content > div > div > p {
			text-align: center;
		}

		.founders-content > div {
			text-align: center;
			font-size: 20px;
		}
		.head {
			width: 90%;
			margin-left: 4.5%;
			margin-top: 5%;
		}
		.founders {
			font-family: "Montserrat", sans-serif;
			font-size: 25px;
			font-weight: bold;
			text-align: center;
		}



		}
</style>
