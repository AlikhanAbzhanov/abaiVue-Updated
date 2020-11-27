<!-- @format -->

<template>
	<div>
		<div class="mobile" id="block4">
			<div id="block4-text">Что получает ученик по окончании курса?</div>
			<div class="block4-first">
				<div id="blocks1">
					<div id="imgdiv">
						<img src="../../DESKTOP/ИКОНКА ПРАКТИЧЕСКИЕ ЗНАНИЯ.png" alt="" />
					</div>
					<div id="text">
						1. Практические знания
						<br />
						и навыки по выбранному
						<br />
						направлению
					</div>
				</div>
				<div id="blocks2">
					<div id="imgdiv">
						<img src="../../DESKTOP/ИКОНКА ТЕОРЕТИЧЕСКАЯ БАЗА.png" alt="" />
					</div>

					<div id="text">2. Крепкая теоретическая база</div>
				</div>
				<div id="blocks2">
					<div id="imgdiv">
						<img src="../../DESKTOP/ИКОНКА ПРОЕКТЫ.png" alt="" />
					</div>
					<div id="text">
						2.Собственные проекты,
						<br />
						как и простые, так и сложные
					</div>
				</div>
				<div id="blocks2">
					<div id="imgdiv">
						<img src="../../DESKTOP/ИКОНКА НОВЫЕ ЗНАКОМТСВА.png" alt="" />
					</div>
					<div id="text">
						4.Новые знакомства
						<br />
						c единомышленниками
					</div>
				</div>
			</div>
		</div>
		<div class="desk">
			<div id="block4-text">Что получает ученик по окончании курса?</div>
			<div class="block4-first">
				<div id="blocks1">
					<div id="imgdiv">
						<img src="../../DESKTOP/ИКОНКА ПРАКТИЧЕСКИЕ ЗНАНИЯ.png" alt="" />
					</div>
					<div id="text">
						1. Практические знания
						<br />
						и навыки по выбранному
						<br />
						направлению
					</div>

					<div id="imgdiv">
						<img src="../../DESKTOP/ИКОНКА ТЕОРЕТИЧЕСКАЯ БАЗА.png" alt="" />
					</div>

					<div id="text">2. Крепкая теоретическая база</div>
				</div>

				<div id="blocks2">
					<div id="imgdiv">
						<img src="../../DESKTOP/ИКОНКА ПРОЕКТЫ.png" alt="" />
					</div>
					<div id="text">
						2.Собственные проекты,
						<br />
						как и простые, так и сложные
					</div>

					<div id="imgdiv">
						<img src="../../DESKTOP/ИКОНКА НОВЫЕ ЗНАКОМТСВА.png" alt="" />
					</div>
					<div id="text">
						4.Новые знакомства
						<br />
						c единомышленниками
					</div>
				</div>
			</div>
		</div>
	</div>
</template>

<style scoped>
	@media only screen and (min-width: 1100px) {
		.block4-text{
			text-align: center;
		}
		#text {
			font-size: 20px;
		}
		.mobile {
			display: none;
		}
		.sec {
			margin-left: 5%;
		}
		.desk {
			font-family: "Montserrat", sans-serif;
			width: 90%;
			margin-left: 5%;
		}

		#text {
		}
		.block4-first {
			box-sizing: border-box;
			margin-top: 5%;
		}
		.block4-first > div {
			display: flex;
			justify-content: space-between;
		}
		#imgdiv > img {
		}
		.block4-first > div > div > img {
			height: 100%;
			width: 100%;
		}

		#text {
			width: 30%;
			height: 30%;
		}
		#block4 {
			font-family: "Montserrat", sans-serif;

			margin-top: 5%;
			width: 90%;
			margin-left: 10%;
		}
		#block4-text {
			text-align: center;
			font-size: 30px;
			font-weight: bold;
		}
		#block4-first {
		}
		#text {
			margin-right: 8%;
			margin-top: 2%;
			padding-top: 1%;
			font-size: 25px;
		}
		#blocks2 {
			margin-top: 3%;
		}
	}
	@media only screen and (min-width: 801px) {	.mobile {
			display: none;
		}



		
		.block4-text{
			text-align: center;
		}
		.desk {
			font-family: "Montserrat", sans-serif;
			width: 90%;
			margin-left: 5%;
		}

		.main {
			margin-top: 5%;
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
		#text > div {
			font-size: 20px;
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
			font-family: "Montserrat", sans-serif;
			font-size: 25px;
			font-weight: bold;
		}
		#block4-first {
		}
		#text {
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
			width: 20%;
		}
		.block4-first > div > div > img {
			height: 100%;
			width: 100%;
		}
		#text {
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
		#text {
			margin-right: 8%;
			margin-top: 2%;
			padding-top: 1%;
			font-size: 18px;
		}
		#blocks2 {
			margin-top: 3%;
		}
	}
</style>
