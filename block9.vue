<!-- @format -->

<template>
	<div class="block9">
		<div id="bigtext">Наши контакты</div>
		<div class="contact">
			<img src="../../DESKTOP/call 1.png" alt="" />
			<div>
				<div>+ 7 (777) 472 - 88 - 69</div>
				<div>+ 7 (705) 279 - 10 - 00</div>
			</div>
		</div>
		<div class="contact">
			<img src="../../DESKTOP/email 1.png" alt="" />
			<div>abvolunteers777@gmail.com</div>
		</div>
	</div>
</template>

<style scoped>
	@media only screen and (min-width: 1100px) {
		img {
			width: 2%;
			height: 2%;
		}
		.block9 {
			margin-top: 5%;
			width: 90%;
			margin-left: 5%;

			font-family: "Montserrat", sans-serif;
		}
		#bigtext {
			text-align: center;
			font-size: 30px;
			font-weight: bold;

			font-family: "Montserrat", sans-serif;
		}
		.contact {
				margin-top: 5%;
			margin-left: 37.5%;
			display: flex;
			font-size: 20px;
		}
		.contact > div {
			padding-left: 2%;
		}
	}
	@media only screen and (min-width: 801px) {
		img {
			width: 2%;
			height: 2%;
		}
		.block9 {
			margin-top: 5%;
			width: 90%;
			margin-left: 5%;

			font-family: "Montserrat", sans-serif;
		}
		#bigtext {
			text-align: center;

			font-size: 30px;
			font-weight: bold;

			font-family: "Montserrat", sans-serif;
		}
		.contact {
			margin-top: 5%;
			margin-left: 37.5%;
			display: flex;
			font-size: 20px;
		}
		.contact > div {
			padding-left: 2%;
		}
	}
	@media only screen and (max-width: 800px) {
		img {
			width: 5%;
			height: 5%;
		}
		.block9 {
			margin-top: 5%;
			width: 90%;
			margin-left: 5%;

			font-family: "Montserrat", sans-serif;
		}
		#bigtext {
			font-size: 25px;
			font-weight: bold;

			font-family: "Montserrat", sans-serif;
		}
		.contact {
			margin-top: 3%;
			display: flex;
			font-size: 20px;
		}
		.contact > div {
			padding-left: 2%;
		}
	}
</style>
