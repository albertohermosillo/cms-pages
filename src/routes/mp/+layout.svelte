<script>
	import '../../app-mp.css'; // Tailwind kit?
	import favicon from '$lib/assets/favicon.svg';
	//import Header from '$lib/_global-header.svelte';
</script>

<svelte:head>
	<link rel="stylesheet" href="/app-mp.css">
	<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/7.0.0/css/all.min.css">
	<link rel="icon" href={favicon} />
</svelte:head>


<!-- Shared Header -->
<!-- <Header /> -->

<!-- Page content slot is inserted here -->
<slot></slot>

<!-- Shared Footer -->
<!-- <Footer /> -->
