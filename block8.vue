<!-- @format -->

<template>
	<div id="block8">
		<div id="bigtext">Наши партнеры</div>
		<div class="imgs">
			<img src="../../DESKTOP/ИКОНКА AB VOLUNTEERS.png" alt="" @click='openAb'/>
			<img src="../../DESKTOP/ИКОНКА CODEKOMEK.png" @click='codekomek' alt="" />
		</div>
	</div>
</template>
<style scoped>
	@media only screen and (min-width: 1100px) {
		#block8 {
			width: 90%;
			margin-left: 5%;
			font-family: "Montserrat", sans-serif;
			margin-top: 5%;
			font-weight: bold;
		}
		#bigtext {
			text-align: center;
			font-size: 30px;
		}
		.imgs {
			display: flex;
			justify-content: flex-start;
		}
		img:first-child {
			width: 15%;
			height: 15%;
		}

		img:last-child {
			width: 15%;
			height: 15%;
			padding-top: 4%;
		}
	}

@media only screen and (min-width: 801px){
#block8 {
			width: 90%;
			margin-left: 5%;
			font-family: "Montserrat", sans-serif;
			margin-top: 5%;
			font-weight: bold;
		}
		#bigtext {
			text-align: center;
			font-size: 25px;
		}
		.imgs {
			display: flex;
			justify-content: flex-start;
			
		}
		img:first-child {
			margin-left: 32.5%;
			width: 15%;
			height: 15%;
		}

		img:last-child {
			width: 15%;
			height: 15%;
			padding-top: 4%;
		}
			
	
}

	@media only screen and (max-width: 800px) {
		#block8 {
			width: 90%;
			margin-left: 5%;
			font-family: "Montserrat", sans-serif;
			margin-top: 5%;
			font-weight: bold;
		}
		#bigtext {
			font-size: 25px;
		}
		.imgs:not(:first-child) {
            width: 150%;
            height:150%;
			display: flex;
			justify-content: flex-start;
		}
		img:first-child {
				margin-left: 2.5%;
			width: 20%;
			height: 20%;
		}

		img:last-child {
			width: 20%;
			height: 20%;
			padding-top: 4%;
		}
	}
</style>

<script>
export default {
	methods:{
		codekomek(){
			window.open('https://code-komek.info')
		},
		openAb(){
			window.open("https://www.instagram.com/ab_volunteers/")
		}
	}
}
</script>
