<script>
	import '../app.css';
	import Navigation from '$lib/components/navigation/navigation.svelte';
	import Footer from '$lib/components/footer/footer.svelte';
</script>

<Navigation/>

<slot></slot>

<Footer/>
