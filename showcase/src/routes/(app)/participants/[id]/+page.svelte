<div class="card shadow-lg p-3 mb-5 bg-body-tertiary rounded" style="width: 50%;">
	<img
		src="https://vignette.wikia.nocookie.net/callofduty/images/e/e4/You've_earned_it_CoDG.jpg/revision/latest?cb=20160916023007"
		class="card-img-top"
		alt="..."
	/>
	<div class="card-body">
		<h5 class="card-title">Title</h5>
		<p class="card-text">
			Some quick example text to build on the card title and make up the bulk of the card's content.
		</p>
		<a href="#" class="btn btn-primary btn-bg">PORTFOLIE LINK</a>

		<div>
			<a
				href="#"
				id="facebook"
				class="fa fa-facebook btn btn-primary"
			/><!--class="btn btn-primary"-->
			<a href="#" id="twiter" class="fa fa-twitter btn btn-primary" />
			<a href="#" id="instagram" class="fa fa-instagram btn btn-primary" />
			<a href="#" id="google" class="fa fa-google btn btn-primary" />
		</div>
	</div>
</div>

<svelte:head>
	<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
</svelte:head>

<style>
	.btn-bg {
		background-color: white;
		color: black;
		border: 1px solid black;
	}

	.btn-bg:hover {
		opacity: 0.7;
		filter: blur(1px);
		background-color: orangered;
	}
	.fa {
		padding: 10px;
		font-size: 30px;
		width: 50px;
		text-align: center;
		text-decoration: none;
		margin: 5px 2px;
		border: 1px solid black;
	}

	#twiter:hover {
		color: #1da1f2;
	}
	#facebook:hover {
		color: #3b5998;
	}
	#instagram:hover {
		color: #e44055;
	}
	#google:hover {
		color: #2d2d2d;
	}

	.fa:hover {
		opacity: 0.7;
		filter: blur(1px);
		background-color: orangered;
	}

	.fa-facebook {
		background: white;
		color: black;
	}

	.fa-twitter {
		background: white;
		color: black;
	}

	.fa-instagram {
		background: white;
		color: black;
	}

	.fa-twitter {
		background: white;
		color: black;
	}

	.fa-google {
		background: white;
		color: black;
	}

	* {
		justify-content: center;
		text-align: center;
	}

	img {
		/* border-radius: 45%; */
		width: 100%;
	}

	div.card {
		margin: 25px auto;
	}
</style>
