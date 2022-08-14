<svelte:head>
	<title>Nikomus Games</title>
	<link rel="preconnect" href="https://fonts.googleapis.com" />
	<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
	<link
		href="https://fonts.googleapis.com/css2?family=Comfortaa:wght@400;700&display=swap"
		rel="stylesheet"
	/>
	<link href="/reset.css" rel="stylesheet" />
</svelte:head>

<div class="content">
	<main>
		<h1>
			<img class="logo shadow" src="/banner.png" alt="Nikomus Games" />
		</h1>

		<div class="message shadow">
			<p>New website coming soon!</p>
		</div>
	</main>
	<footer class="shadow">© Nikomus Games Ltd 2021</footer>
</div>

<style>
	.content {
		background-color: #f5f5f5;
		min-height: 100vh;
		display: flex;
		flex-direction: column;
		align-items: center;
		font-family: 'Comfortaa', sans-serif;
	}

	main {
		width: 100%;
		display: flex;
		flex-direction: column;
		flex: 1;
		align-items: center;
	}
	h1 {
		color: white;
		font-family: 'Comfortaa', sans-serif;
		font-size: 2rem;
	}

	.logo {
		width: 24rem;
		height: 24rem;
		max-height: 60vw;
		max-width: 60vw;
		border-radius: 1.5rem;
		margin: 4rem 0;
	}

	.message {
		background-color: #ffffff;
		border-radius: 1.5rem;
		min-height: 4rem;
		display: flex;
		align-items: center;
		justify-content: center;
		max-width: 80%;
		padding: 0 2rem;
	}

	footer {
		display: block;
		background-color: #ffffff;
		border-top-left-radius: 1.5rem;
		border-top-right-radius: 1.5rem;
		max-width: 80%;
		height: 4rem;
		display: flex;
		align-items: center;
		justify-content: center;
		padding: 0 2rem;
		font-size: 80%;
	}

	.shadow {
		box-shadow: 1px 2px 2px hsl(0deg 0% 50% / 0.2), 2px 4px 4px hsl(0deg 0% 50% / 0.2),
			4px 8px 8px hsl(0deg 0% 50% / 0.2), 8px 16px 16px hsl(0deg 0% 50% / 0.2),
			16px 32px 32px hsl(0deg 0% 50% / 0.2);
	}
</style>
