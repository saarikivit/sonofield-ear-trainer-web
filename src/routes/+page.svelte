<script lang="ts">
	import screenshot from '$lib/assets/screenshot.webp';
</script>

<svelte:head>
	<title>Sonofield Ear Trainer</title>
	<meta
		name="description"
		content="Sonofield Ear Trainer (SET) is a revolutionary app designed to help you intuitively play the melodies you hear and imagine."
	/>
	<meta name="keywords" content="Sonofield, Ear Trainer, Solfege, App, Training, Music Theory" />
	<meta name="author" content="Sonofield" />
</svelte:head>

<section>
	<img alt="Sonofield Ear Trainer screenshot" src={screenshot} />
	<div class="text">
		<p class="smallp">Get notified when Sonofield Ear Trainer releases</p>
		<a class="link" href="https://www.sonic-sorcery.com/set">https://www.sonic-sorcery.com/set</a>
	</div>
</section>

<article class="prose prose-zinc lg:prose-lg">
	<h1>Sonofield Ear Trainer</h1>
	<p>
		Sonofield Ear Trainer (SET) is a revolutionary app designed to help you intuitively play the
		melodies you hear and imagine. Instead of relying on traditional methods, The Sonofield Method
		focuses on helping you feel the unique character of each note within a key. By using sustained
		drones to create a tonal foundation, you’ll learn to recognize scale degrees based on their <b
			>feeling</b
		>, not just how they sound.
	</p>

	<p>The app offers a variety of ways to do ear training:</p>
	<ul>
		<li>
			Degrees Mode - Identify individual notes against the drone by feeling. The heart of SET.
		</li>
		<li>Melody Mode - Identify short melodic phrases, preparing you for real music.</li>
		<li>Voice Mode - Sing the requested scale degree into your microphone.</li>
		<li>Pocket Mode - Hands-free training for when you're on the go.</li>
		<li>Free Play - An interactive instrument for exploration.</li>
	</ul>

	<h2>Why is Sonofield Ear Trainer the best ear training app?</h2>
	<p>
		With its intuitive, color-coded interface, thoughtfully designed progression path, and multiple
		difficulty levels, SET adapts to your skill level while keeping practice engaging. Whether
		you're a beginner or an experienced musician, SET is your guide to unlocking true musical
		fluency through intuitive, feeling-based ear training.
	</p>
</article>

<style>
	section {
		display: flex;
		flex-direction: column; /* Removed for mobile view */
		justify-content: center;
		align-items: center;
		padding: 64px 16px;
	}

	.text {
		width: 100%; /* Full width for text container */
		text-align: center;
	}

	img {
		height: 50vh;
		width: auto;
		border-width: 4px;
		border-color: #111;
		border-radius: 16px;
		margin-bottom: 32px; /* Add spacing after image on mobile */
	}

	.smallp {
		color: #d3d0d0;
		font-size: 14px;
	}
	.link {
		color: #5858ff;
		font-size: 14px;
	}

	article {
		margin: 0 auto;
		padding: 0 16px 64px;
	}

	h1,
	h2 {
		color: #d3d0d0;
	}

	a,
	article {
		color: #d3d0d0;
	}
</style>
