<script lang="ts">
	import AppFooter from '../../components/AppFooter.svelte';
</script>

<svelte:head>
	<title>About Sonofield Ear Trainer</title>
	<meta
		name="description"
		content="Sonofield Ear Trainer Education Ltd. is a Canadian company. We want to help people improve their ability to recognize, understand and play music."
	/>
	<meta
		name="keywords"
		content="Sonofield, Ear Trainer, Solfege, App, Training, Music Theory, Canadian"
	/>
	<meta name="author" content="Sonofield" />
</svelte:head>

<div class="prose prose-zinc lg:prose-lg">
	<header>
		<h1>About Sonofield Ear Trainer Education Ltd.</h1>
	</header>
	<main>
		<section>
			<h2>Who We Are</h2>
			<p>
				Sonofield Ear Trainer Education Ltd. is a Canadian company. We want to help people improve
				their ability to recognize, understand and play music.
			</p>
		</section>
		<section>
			<h2>Our App: Sonofield Ear Trainer</h2>
			<p>
				Sonofield is a melodic ear training app that helps you learn to identify scale degrees by
				playing them over a drone. The goal is to sharpen your ear and train you to recognize
				musical notes by how they feel, not just how they sound.
			</p>
		</section>
		<section>
			<h2>Contact Us</h2>
			<p>
				Have questions or need support? Reach out to us at <a href="mailto:support@sonofield.com"
					>support@sonofield.com</a
				>.
			</p>
		</section>
		<section>
			<h2>More</h2>
			<p>
				Find our music and ear training related videos on <a
					href="https://www.youtube.com/@maxkonyi">YouTube</a
				>.
			</p>
			<p>
				Find out more on <a href="https://www.maxkonyi.com/">Max's Website</a> and
				<a href="https://www.sonic-sorcery.com/">Sonic Sorcery</a>.
			</p>
			<p>
				Join our <a href="https://discord.gg/9zGU9XhYNB">Discord</a>.
			</p>
		</section>
	</main>
</div>

<AppFooter></AppFooter>

<style>
	div {
		margin: 0 auto;
		padding: 64px 16px;
	}

	h1,
	h2 {
		color: #d3d0d0;
	}

	a,
	div {
		color: #d3d0d0;
	}
</style>
