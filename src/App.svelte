<script>
	let name
</script>

<main>
	<header class="main__header">
		<img src="/logo.svg" alt="logo" class="logo">
		<div class="text-container">
			<h1>
                <span class="text-container-main"> Hello, I am Armaan &#x1F366;</span>
				<span class="text-container-sub">A fulstack webdev and an AI enthusiast.</span>
			</h1>
		</div>
	</header>
</main>

<style>
	.main__header {
		background-image: linear-gradient(to right bottom, rgb(12, 5, 41), #212121);
		height: 95vh;
		clip-path: polygon(0 0, 100% 0, 100% 87%, 0 100%);
		color: white;
		position: relative;
	}

	.main__header .text-container {
		text-transform: uppercase;
	}

	.text-container {
		position: absolute;
		top: 40%;
		left: 50%;
		transform: translate(-50%);
	}

	.text-container-main {
		font-size: 30px;
		display: block;
		animation: animateTextMain 0.5s ease-out;
	}
	.text-container-sub {
		font-size: 20px;
		display: block;
		animation: animateTextSub 0.5s ease-out;
	}

	.logo {
		width: 66px;
		position: absolute;
		top: 30px;
		left: 30px;
	}
</style>