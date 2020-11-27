<!-- @format -->

<template>
	<div class="main">
		<div id="text-main">
			Зарегистрируйтесь на участие в проекте и наши кураторы свяжут вас с
			ментором или учеником
		</div>
		<div class="main-content">
			<div>
				<form action="" @submit.prevent="onSubmit">
					<div id="symbmax">Поле вмещает в себя не больше 100 символов</div>
					<input
						type="text"
						id="lname"
						name="lname"
						placeholder="Имя и фамилия"
						v-model="form.name"
					/>
					<br />
					<br />
					<input
						type="text"
						id="lname"
						name="lname"
						placeholder="Почта"
						v-model="form.email"
					/>
					<br />
					<br />
					<input
						type="text"
						id="lname"
						name="lname"
						placeholder="Номер телефона"
						v-model="form.number"
					/>
					<br />
					<br />
					<input
						type="text"
						id="lname"
						name="lname"
						placeholder="Место обучения/работы"
						v-model="form.place"
					/>
					<br />
					<br />
					<input
						type="text"
						id="lname"
						name="lname"
						placeholder="Желаемый язык программирования "
						v-model="form.lang"
					/>
					<br />
					<br />
					<select name="cars" id="cars" v-model="form.student">
						<option value="Mentor">Ментор</option>
						<option value="Uchenik">Ученик</option>
					</select>
					<div id="status">{{ message }}</div>
					
					<br>
					<input type="submit" value="Зарегистрироваться" id="register" />
					
				</form>
				
			</div>

			<img src="../../DESKTOP/КАРТИНКА-2.png" alt="" />
		</div>
	</div>
</template>
<style scoped>
	@media only screen and (min-width: 1100px) {
	
		#symbmax {
			font-size: 20px;
			font-weight: 100;
			color: rgb(168, 164, 164);
		}
		#status {
			font-size: 20px;
			padding-top: 5%;
			padding-left: 18%;
		}
		.main {
			margin-top: 5%;
			width: 90%;
			margin-left: 5%;
			font-family: "Montserrat", sans-serif;
		}
		#text-main {
			font-size: 35px;
			font-weight: bold;
		}
		img {
			margin-left: 15%;
			width: 40%;
			height: 30%;
		}
		.main-content {
			display: flex;
			margin-top: 3%;
		}
		.main-content > div {
			border-radius: 2% 2%;
			width: 30%;
			background-color: rgb(255, 255, 255);
		}
		option {
			font-size: 18px;
		}
		select {
			background-color: white;
			border: none;
			box-shadow: 1px 1px 1.5px 1.5px #8d8d8d;
			text-decoration: none;
			width: 60%;
			height: 5vh;
			margin-left: 20%;
			border-radius: 20px;
		}
		.main-content > div > form > input {
			border: none;
			box-shadow: 1px 1px 1.5px 1.5px #8d8d8d;
			text-decoration: none;
			width: 60%;
			height: 5vh;
			margin-left: 20%;
			border-radius: 20px;
		}
		input:first-child {
			margin-top: 10%;
		}
		input:last-child {
			height: 100vh;
			background-color: rgb(68, 87, 255);
			color: white;
			font-size: 20px;
			font-weight: bold;
		}
		input:last-child:hover {
			transition: 0.2s;
			background-color: rgb(10, 47, 255);
		}
		::placeholder {
			padding-left: 3%;
		}
		form {
			text-decoration: none;
		}
		input {
			text-decoration: none;
		}
	}

	@media only screen and (min-width: 801px) {
		#symbmax {
			font-size: 15px;
			font-weight: 100;
			color: rgb(168, 164, 164);
		}
		#status {
			font-size: 18px;
			padding-top: 5%;
			padding-left: 18%;
		}
		.main {
			margin-top: 5%;
			width: 90%;
			margin-left: 5%;
			font-family: "Montserrat", sans-serif;
		}
		#text-main {
			font-size: 25px;
			font-weight: bold;
		}
		img {
			margin-left: 15%;
			width: 40%;
			height: 30%;
		}
		.main-content {
			display: flex;
			margin-top: 3%;
		}
		.main-content > div {
			border-radius: 2% 2%;
			width: 30%;
			background-color: rgb(255, 255, 255);
		}
		option {
			font-size: 15px;
		}
		select {
			background-color: white;
			border: none;
			box-shadow: 1px 1px 1.5px 1.5px #8d8d8d;
			text-decoration: none;
			width: 60%;
			height: 5vh;
			margin-left: 20%;
			border-radius: 17px;
		}
		.main-content > div > form > input {
			border: none;
			box-shadow: 1px 1px 1.5px 1.5px #8d8d8d;
			text-decoration: none;
			width: 60%;
			height: 5vh;
			margin-left: 20%;
			border-radius: 17px;
		}
		input:first-child {
			margin-top: 10%;
		}
		input:last-child {
			width:120%;
			background-color: rgb(68, 87, 255);
			color: white;
			font-size: 15px;
			font-weight: bold;
		}
		input:last-child:hover {
			transition: 0.2s;
			background-color: rgb(10, 47, 255);
		}
		::placeholder {
			padding-left: 3%;
		}
		form {
			text-decoration: none;
		}
		input {
			text-decoration: none;
		}
	}

	@media only screen and (max-width: 800px) {
		#symbmax {
			font-size: 15px;
			font-weight: 100;
			color: rgb(168, 164, 164);
		}
		#status {
			font-size: 20px;
			padding-top: 5%;
			padding-left: 18%;
		}
		.main {
			margin-top: 10%;
			width: 90%;
			margin-left: 5%;
			font-family: "Montserrat", sans-serif;
		}
		#text-main {
			font-size: 25px;
			font-weight: bold;
		}
		img {
			margin-top: 5%;
			width: 100%;
			height: 100%;
		}
		.main-content {
			display: flex;
			flex-direction: column;
			margin-top: 3%;
			
		}
		.main-content > div {
			border-radius: 2% 2%;
			width: 100%;
			background-color: rgb(255, 255, 255);
		}
		option {
			font-size: 18px;
		}
		select {
			background-color: white;
			border: none;
			box-shadow: 1px 1px 1.5px 1.5px #8d8d8d;
			text-decoration: none;
			width: 60%;
			height: 5vh;
			margin-left: 20%;
			border-radius: 20px;
		}
		.main-content > div > form > input:not(:last-child) {
			border: none;
			box-shadow: 1px 1px 1.5px 1.5px #8d8d8d;
			text-decoration: none;
			width: 60%;
			height: 5vh;
			margin-left: 20%;
			border-radius: 20px;
		}
		input:first-child {
			margin-top: 10%;
		}
		input:last-child {
				border: none;
			box-shadow: 1px 1px 1.5px 1.5px #8d8d8d;
			text-decoration: none;
			width: 80%;
			height: 8vh;
			margin-left: 10%;
			border-radius: 20px;
			background-color: rgb(68, 87, 255);
			color: white;
			font-size: 20px;
			font-weight: bold;
		}
		input:last-child:hover {
			transition: 0.2s;
			background-color: rgb(10, 47, 255);
		}
		::placeholder {
			padding-left: 3%;
		}
		form {
			text-decoration: none;
		}
		input {
			text-decoration: none;
		}
	}
</style>
<script>
	export default {
		name: "block6",
		props: ["message"],

		data() {
			return {
				form: {},
			};
		},

		methods: {
			onSubmit() {
				let post = this.form;
				this.$emit("add-todo", post);
			},
		},
	};
</script>
