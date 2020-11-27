<!-- @format -->

<template>
	<div id="app">
		<block1 class="block1" @formidti="gotoForm" @gotoform2="gotoForm2" />
		<block2 class="block2" />
		<block3 class="block3" id="block3" />
		<blockAbout id ='blockAbout' />
		<block4 class="block4" />
		<block5 class="block5" />
		<block6
			v-bind:message="info"
			id="block6"
			class="block6"
			@add-todo="addTodo"
		/>
		<block7 />
		<block8 />
		<block9 />
		<a href="#test"></a>
	</div>
</template>

<script>
	export default {};
</script>
<script>
	"use strict";
	async function postData(url = "https://abaiapi.ew.r.appspot.com", data) {
		// Default options are marked with *
		const response = await fetch(url, {
			method: "POST",
			headers: {
				"Content-Type": "application/json",
				// 'Content-Type': 'application/x-www-form-urlencoded',
			},

			body: JSON.stringify(data), // body data type must match "Content-Type" header
		});
		return response.json(); // parses JSON response into native JavaScript objects
	}
	import block1 from "./components/block1.vue";
	import block2 from "./components/block2.vue";
	import block3 from "./components/block3.vue";
	import block4 from "./components/block4.vue";
	import block5 from "./components/block5.vue";
	import block6 from "./components/block6.vue";
	import block7 from "./components/block7.vue";
	import block8 from "./components/block8.vue";
	import block9 from "./components/block9.vue";
	import blockAbout from "./components/blockAbout.vue";

	export default {
		name: "App",

		components: {
			block1,
			block2,
			block3,
			block4,
			block5,
			block6,
			block7,
			block8,
			block9,
			blockAbout,
		},

		data() {
			return {
				info: "",
			};
		},

		methods: {
			addTodo(post) {
				if (post.student === "Mentor") post.student = false;
				else if (post.student === "Uchenik") post.student = true;
				else post.student = undefined;

				postData("https://abaiapi.ew.r.appspot.com", {
					name: post.name,
					email: post.email,
					lang: post.lang,
					place: post.place,
					student: post.student,
					number: post.number,
				}).then(data => {
					this.info = data.message; // JSON data parsed by `data.json()` call
				});
			},
			gotoForm(info) {
				let el = document.getElementById("block6");
				console.log(el.offsetTop);
				window.scrollTo(0, el.offsetTop);
			},
			gotoForm2() {
				let el = document.getElementById("blockAbout");
				console.log(el.offsetTop);
				window.scrollTo(0, el.offsetTop );
			},
		},
	};
</script>

<style>
	template {
		box-sizing: border-box;
		font-family: "Montserrat", sans-serif;

	}
	#app {
						background-color: #f5f5f5;

	}
	.block1 {
	}
</style>
