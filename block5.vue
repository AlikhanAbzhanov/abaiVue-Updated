<!-- @format -->

<template>
	<div class="block2">
		<div class="label">Как работает наша платформа?</div>
		<div class="icons">
			<div>
				<img src="../../DESKTOP/ИКОНКА ВЫБОР ПОЗИЦИИ.png" alt="" />
				<div id = 'tekst'>
  Вы проходите регистрацию
  и выбираете свою позицию 
      (ученик/ментор)
                            </div>
				
			</div>
			<div>
				<img src="../../DESKTOP/УЧЕНИКА.png" alt="" />
				<div id = 'tekst'>     Вся ваша информация обрабатывается в базе данных 
      и мы выбираем вам      ученика/учителя.
                            </div>
			</div>

			<div>
				<img src="../../DESKTOP/ИКОНКА КУРАТОР.png" alt="" />
				<div id = 'tekst'>
 В течении всего курса с вами
будет куратор, который будет
     помогать в случае
       необходимости<div class="br"></div>
                     </div>
			</div>
		</div>
		
				<div class="iconsmobile">
			<div>
				<img src="../../DESKTOP/ИКОНКА ВЫБОР ПОЗИЦИИ.png" alt="" />
				<div id = 'tekst'>
  Вы проходите регистрацию
  и выбираете свою позицию  
      (ученик/ментор)
                            </div>
				
			</div>
			<div>
				<img src="../../DESKTOP/УЧЕНИКА.png" alt="" />
				<div id = 'tekst'>     Вся ваша информация обрабатывается в базе данных 
      и мы выбираем вам      ученика/учителя.
                            </div>
			</div>

			<div>
				<img src="../../DESKTOP/ИКОНКА КУРАТОР.png" alt="" />
				<div id = 'tekst'>
 В течении всего курса с вами
будет куратор, который будет
     помогать в случае
       необходимости<div class="br"></div>
                     </div>
			</div>
		</div>
	</div>
</template>
<style scoped>
	@media only screen and (min-width: 1100px) {
		img{
			padding-left: 15%;
		}
		#tekst{
			text-align: center;
			font-size: 20px;
		}
		.label{
			text-align: center;
		}
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
		
			margin-top: 7%;
		}
		.label {
			font-size: 30px;
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
		
		}

		.icons > div > pre:not(:first-child) {
			
		}
		.icons > img:not(:first-child) {
			
			margin-top: 5%;
		}
		.icons > img {
		}
	}
@media only screen and (min-width: 801px){
	#tekst{
	
		font-size: 20px;
	}
	img{
			padding-left: 15%;
		}
		.label{
			text-align: center;
		}
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
			padding-right: 90px;
		}
		.icons > img:not(:first-child) {
			margin-left: 18%;
			margin-top: 5%;
		}
		.icons > img {
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
		.icons > div {
			margin-top: 5%;
		}
	}
</style>
