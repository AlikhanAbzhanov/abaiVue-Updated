<!-- @format -->

<template>
	<div class="block2">
		<div class="label">Этот проект для вас, если вы:</div>
		<div class="icons">
			<div>
				<img src="../../DESKTOP/ИКОНКА ВЫБОР ПОЗИЦИИ.png" alt="" />
				<div>
					Школьник, который хочет
					<br />
					изучить новое и связать свою
					<br />
					жизнь с IT
				</div>
			</div>
			<div>
				<img src="../../DESKTOP/ИКОНКА СТУДЕНТ.png" alt="" />
				<div>
					Студент, который хочет освоить
					<br />
					новый навык для карьерных
					<br />
					перспектив
				</div>
			</div>

			<div>
				<img src="../../DESKTOP/ИКОНКА МЕНТОР.png" alt="" />
				<div>
				Ментор, который готов<br> поделиться своими знаниямии <br>направить на верный путь
				</div>
			</div>
		</div>
		<div class="iconsmobile">
			<div>
				<img src="../../DESKTOP/ИКОНКА ВЫБОР ПОЗИЦИИ.png" alt="" />
				<div>
					Школьник, который хочет
					<br />
					изучить новое и связать свою
					<br />
					жизнь с IT
				</div>
			</div>
			<div>
				<img src="../../DESKTOP/ИКОНКА СТУДЕНТ.png" alt="" />
				<div>
					Студент, который хочет освоить
					<br />
					новый навык для карьерных
					<br />
					перспектив
				</div>
			</div>

			<div>
				<img src="../../DESKTOP/ИКОНКА МЕНТОР.png" alt="" />
				<div>
								Ментор, который готов<br> поделиться своими знаниямии <br>направить на верный путь

				</div>
			</div>
		</div>
	</div>
</template>
<style scoped>
	@media only screen and (min-width: 1100px) {
		.iconsmobile {
			display: none;
		}
		.icons > div {
			width: 33%;
			margin-top: 5%;
		}
		.icons > div > pre {
		}
		.block2 {
			width: 90%;
			margin-left: 5%;
			margin-top: 7%;
		}
		.label {
			text-align: center;
			font-size: 35px;
			font-weight: bold;

			font-family: "Montserrat", sans-serif;
		}
		.icons {
			display: flex;
		}
		.icons > div > img {
			height: 60%;
			width: 45%;
		}
		.icons > div > img:first-child {
			margin-left: 13%;
		}

		.icons > div > pre:not(:first-child) {
			padding-right: 100px;
		}
		.icons > img:not(:first-child) {
			margin-left: 18%;
			margin-top: 5%;
		}
		.icons > img {
		}
			.icons>div>div{
		
          padding-left: 10%;
			font-size: 25px;
		}
	}



	@media only screen and (min-width: 801px){
	.iconsmobile {
			display: none;
		}
		.icons > div {
			width: 33%;
			margin-top: 5%;
		}
		.icons > div > pre {
		}
		.block2 {
			width: 90%;
			margin-left: 10%;
			margin-top: 7%;
		}
		.label {

			text-align: center;
			font-size: 25px;
			font-weight: bold;

			font-family: "Montserrat", sans-serif;
		}
		.icons {
			display: flex;
		}
		.icons > div > img {
			height: 60%;
			width: 45%;
		}
		.icons > div > img:first-child {
			margin-left: 13%;
		}

		.icons > div > pre:not(:first-child) {
			padding-right: 100px;
		}
		.icons > img:not(:first-child) {
			margin-left: 15%;
			margin-top: 5%;
		}
		.icons > img {
		}
		.icons>div>div{
		
          padding-left: 10%;
			font-size: 20px;
		}
}







	@media only screen and (max-width: 800px) {
		.label {
			text-align: center;
			font-size: 25px;
			font-weight: bold;
			font-family: "Montserrat", sans-serif;
		}
		.icons {
			display: none;
		}
		.iconsmobile {
			display: flex;
			margin-left: 10%;
			width: 80%;
			display: flex;
			flex-direction: column;
		}
		.iconsmobile > div > img {
			height: 23vh;
			padding-left: 35%;
			width: 30%;
		}
		.iconsmobile > div > div {
			width: 100%;
			font-size: 20px;
			text-align: center;
		}
		.iconsmobile > div {
			margin-top: 5%;
		}
	}
</style>
