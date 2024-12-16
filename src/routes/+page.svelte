<script lang="ts">
	import screenshot from '$lib/assets/screenshot.webp';
</script>

<section>
	<img alt="Sonofield Ear Trainer screenshot" src={screenshot} />
	<div class="text">
		<p>Get notified when Sonofield Ear Trainer releases</p>
		<a href="https://www.sonic-sorcery.com/set">https://www.sonic-sorcery.com/set</a>
	</div>
</section>

<style>
	section {
		display: flex;
		flex-direction: column; /* Removed for mobile view */
		justify-content: center;
		align-items: center;
		height: 100vh;
		background-color: #0a0a0d;
		padding: 0 16px;
	}

	.text {
		width: 100%; /* Full width for text container */
		text-align: center;
	}

	img {
		height: 50vh;
		width: auto;
		border-radius: 16px;
		margin-bottom: 32px; /* Add spacing after image on mobile */
	}

	p {
		color: #d3d0d0;
		font-size: 14px;
	}
	a {
		color: #5858ff;
		font-size: 14px;
	}
</style>
