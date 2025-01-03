<script lang="ts">
	import '../app.css';
	let { children } = $props();
</script>

{@render children()}

<footer>
	<p class="text-center">&copy; 2025 Sonofield Ear Trainer Education Ltd. All rights reserved.</p>
</footer>

<style>
	footer {
		color: #575757;
	}
</style>
