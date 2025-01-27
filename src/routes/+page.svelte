<script lang="ts">
	import screenshot from '$lib/assets/screenshot.webp';
</script>

<svelte:head>
	<title>Sonofield Ear Trainer</title>
	<meta
		name="description"
		content="Sonofield Ear Trainer (SET) is a revolutionary app designed to help you intuitively play the melodies you hear and imagine. Download it on Apple App Store and Google Play Store!"
	/>
	<meta name="keywords" content="Sonofield, Ear Trainer, Solfege, App, Training, Music Theory" />
	<meta name="author" content="Sonofield" />
</svelte:head>

<section>
	<img class="screenshot" alt="Sonofield Ear Trainer screenshot" src={screenshot} />
	<div class="links">
		<a class="storelink" href="https://apps.apple.com/app/sonofield-ear-trainer/id6740409139">
			<img
				class="storeimage"
				src="https://upload.wikimedia.org/wikipedia/commons/3/3c/Download_on_the_App_Store_Badge.svg"
				alt="Download on Apple App Store"
			/>
		</a>
		<a class="storelink" href="https://play.google.com/store/apps/details?id=com.sonofield.et">
			<img
				class="storeimage"
				src="https://upload.wikimedia.org/wikipedia/commons/7/78/Google_Play_Store_badge_EN.svg"
				alt="Download on Google Play Store"
			/>
		</a>
	</div>
</section>

<article class="prose prose-zinc lg:prose-lg">
	<h1>Sonofield Ear Trainer</h1>
	<p>
		Sonofield Ear Trainer (SET) is a revolutionary app designed to help you <u
			>intuitively play the melodies you hear and imagine.</u
		>
		Instead of relying on traditional methods, The Sonofield Method focuses on helping you feel the unique
		character of each note within a key. By using sustained drones to create a tonal foundation, you’ll
		learn to recognize scale degrees based on their <u>feeling</u>, not just how they sound.
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

	.links {
		width: 100%; /* Full width for text container */
		text-align: center;
		display: flex;
		justify-content: center;
		margin: 3vw 0;
	}

	.screenshot {
		height: 50vh;
		width: auto;
		border-width: 4px;
		border-color: #111;
		border-radius: 16px;
		margin-bottom: 32px; /* Add spacing after image on mobile */
	}

	.storeimage {
		height: auto;
		width: 40vw;
		max-width: 160px;
		margin: 0 2vw;
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
