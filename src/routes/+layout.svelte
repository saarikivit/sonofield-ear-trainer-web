<script lang="ts">
	import '../app.css';
	let { children } = $props();
</script>

{@render children()}

<footer>
	<p class="text-center">&copy; 2025 Sonofield Ear Trainer Education Ltd. All rights reserved.</p>
	<br />
	<a class="text-gray-700" href="/">Download</a>
	<br />
	<a class="text-gray-700" href="/privacy-policy">Privacy Policy</a>
	<br />
	<a class="text-gray-700" href="/terms-of-service">Terms of Service</a>
	<br />
	<a class="text-gray-700" href="/about">About Us</a>
	<br />
	<a class="text-gray-700" href="https://www.youtube.com/@maxkonyi">YouTube</a>
	<br />
	<a class="text-gray-700" href="https://discord.gg/9zGU9XhYNB">Discord</a>
	<br />
	<a class="text-gray-700" href="https://www.sonic-sorcery.com/">More on Sonic Sorcery</a>
</footer>

<style>
	footer {
		color: #575757;
		display: flex;
		flex-direction: column; /* Removed for mobile view */
		justify-content: center;
		align-items: center;
		padding: 16px;
	}
</style>
