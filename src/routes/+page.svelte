<script lang="ts">
	import screenshot from '$lib/assets/screenshot.webp';
</script>

<section>
	<img alt="Sonofield Ear Trainer screenshot" src={screenshot} />
	<div class="text">
		<p>Get notified when Sonofield Ear Trainer releases</p>
		<a class="link" href="https://www.sonic-sorcery.com/set">https://www.sonic-sorcery.com/set</a>
		<br />
		<a class="text-gray-700" href="/privacy-policy">Privacy Policy</a>
		<br />
		<a class="text-gray-700" href="/about">About Us</a>
	</div>
</section>

<style>
	section {
		display: flex;
		flex-direction: column; /* Removed for mobile view */
		justify-content: center;
		align-items: center;
		height: 100vh;
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
	.link {
		color: #5858ff;
		font-size: 14px;
	}
</style>
