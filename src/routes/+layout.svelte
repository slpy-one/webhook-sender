<script lang="js">
	import './main.css'

  import Navbar from '$lib/components/Navbar.svelte';
  import Footer from '$lib/components/Footer.svelte';
</script>

<div class="bg-ctp-base text-ctp-text min-h-screen w-full">
  <Navbar />
	<main>
		<slot />
	</main>
  <Footer />
</div>

<style>
</style>