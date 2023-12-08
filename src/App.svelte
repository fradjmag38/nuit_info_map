<script>
	import Navbar from './components/Navbar.svelte';
	import Map from './components/Map.svelte';
  import sidebar from './components/sidebar.svelte';
    import Sidebar from './components/sidebar.svelte';
</script>

<div class="app">
  <Navbar/>
	<Map/>
  <Sidebar/>
</div>

<style>
  .app {
    text-align: center;
  }
</style>
