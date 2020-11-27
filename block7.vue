<!-- @format -->

<template>
	<div class="main">
		<div class="mobile" id="block4">
			<div id="block4-text">Зачем изучать программирование?</div>
			<div class="block4-first">
				<div id="blocks1">
					<div id="imgdiv">
						<img src="../../DESKTOP/ИКОНКА ТВОРЧЕСТВО.png" alt="" />
					</div>
					<div id="text">
						Программирование даёт максимальную свободу творчеству
					</div>
				</div>
				<div id="blocks2">
					<div id="imgdiv">
						<img src="../../DESKTOP/ИКОНКА ДОХОД.png" alt="" />
					</div>
					<div id="text">
						Сделает вас очень востребованным и высокооплачиваемым специалистом
					</div>
				</div>
				<div id="blocks2">
					<div id="imgdiv">
						<img src="../../DESKTOP/ИКОНКА PROBLEM SOLVING.png" alt="" />
					</div>

					<div id="text">
						Обучает жизненно необходимым навыкам таким как problem solving
					</div>
				</div>
				<div id="blocks2">
					<div id="imgdiv">
						<img src="../../DESKTOP/ИКОНКА НОВЫЕ ЗНАКОМТСВА.png" alt="" />
					</div>
					<div id="text">
						Имеет колоссальную роль в развитии общества
					</div>
				</div>
			</div>
		</div>
		<div class="desk">
			<div id="block4-text">Зачем изучать программирование?</div>
			<div class="block4-first">
				<div id="blocks1">
					<div id="imgdiv">
						<img src="../../DESKTOP/ИКОНКА ТВОРЧЕСТВО.png" alt="" />
					</div>
					<div id="text">
						Программирование даёт максимальную свободу творчеству
					</div>

					<div id="imgdiv">
						<img src="../../DESKTOP/ИКОНКА ДОХОД.png" alt="" />
					</div>
					<div id="text">
						Сделает вас очень востребованным и высокооплачиваемым специалистом
					</div>
				</div>

				<div id="blocks2">
					<div id="imgdiv">
						<img src="../../DESKTOP/ИКОНКА PROBLEM SOLVING.png" alt="" />
					</div>

					<div id="text">
						Обучает жизненно необходимым навыкам таким как problem solving
					</div>

					<div id="imgdiv">
						<img src="../../DESKTOP/ИКОНКА НОВЫЕ ЗНАКОМТСВА.png" alt="" />
					</div>
					<div id="text">
						Имеет колоссальную роль в развитии общества
					</div>
				</div>
			</div>
		</div>
	</div>
</template>

<style scoped>
	@media only screen and (min-width: 1100px) {
		.desk {
			font-family: "Montserrat", sans-serif;
			width: 90%;
			margin-left: 5%;
		}

		.main {
			margin-top: 5%;
		}
		.mobile {
			display: none;
		}
		.sec {
			margin-left: 5%;
		}

		.block4-first {
			box-sizing: border-box;
			margin-top: 5%;
		}
		.block4-first > div {
			display: flex;
			justify-content: space-between;
		}
		#imgdiv {
			width: 10%;
		}
		.block4-first > div > div > img {
			height: 100%;
			width: 100%;
		}
		#text{
				margin-right: 8%;
			margin-top: 2%;
			padding-top: 1%;
			font-size: 25px;
			width: 30%;
			height: 30%;
		}
		#block4 {
			font-family: "Montserrat", sans-serif;

			margin-top: 5%;
			width: 90%;
			margin-left: 5%;
		}
		#block4-text {
			text-align: center;
			font-size: 30px;
			font-weight: bold;
		}
		#block4-first {
		}
	
		#blocks2 {
			margin-top: 3%;
		}
	}

	@media only screen and (min-width: 801px) {
		.desk {
			font-family: "Montserrat", sans-serif;
			width: 90%;
			margin-left: 5%;
		}

		.main {
			margin-top: 5%;
		}
		.mobile {
			display: none;
		}
		.sec {
			margin-left: 5%;
		}

		.block4-first {
			box-sizing: border-box;
			margin-top: 5%;
		}
		.block4-first > div {
			display: flex;
			justify-content: space-between;
		}
		#imgdiv {
			width: 10%;
		}
		.block4-first > div > div > img {
			height: 100%;
			width: 100%;
		}

		#block4 {
			font-family: "Montserrat", sans-serif;

			margin-top: 5%;
			width: 90%;
			margin-left: 5%;
		}
		#block4-text {
			text-align: center;
			font-size: 25px;
			font-weight: bold;
		}
		#block4-first {
		}
		#text {
			width: 30%;
			height: 30%;
			margin-right: 8%;
			margin-top: 2%;
			padding-top: 1%;
			font-size: 20px;
		}
		#blocks2 {
			margin-top: 3%;
		}
	}

	@media only screen and (max-width: 800px) {
		.desk {
			display: none;
		}
		.sec {
			margin-left: 5%;
		}

		.block4-first {
			box-sizing: border-box;
			margin-top: 5%;
		}
		.block4-first > div {
			display: flex;
		}
		#imgdiv {
			width: 25%;
		}
		.block4-first > div > div > img {
			height: 100%;
			width: 100%;
		}
		#text {
				margin-right: 8%;
			margin-top: 2%;
			padding-top: 1%;
			font-size: 18px;
			margin-left: 10%;
			width: 70%;
			height: 30%;
		}
		#block4 {
			font-family: "Montserrat", sans-serif;

			margin-top: 5%;
			width: 90%;
			margin-left: 5%;
		}
		#block4-text {
			font-size: 30px;
			font-weight: bold;
		}
		#block4-first {
		}
	
		#blocks2 {
			margin-top: 3%;
		}
	}
</style>
