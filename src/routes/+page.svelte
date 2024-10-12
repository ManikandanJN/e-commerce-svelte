<script>
  import Dashboard from '../components/dashboard/dashboard.svelte';
  import Sidebar from '../components/sidebar/sidebar.svelte';
</script>

<div class="main-page">
  <Sidebar />
  <Dashboard />
  <!-- <h1 class="text-3xl font-bold underline">Hello world</h1> -->
</div>

<style>
  .main-page{
    display: flex;
    flex-direction: row;
    height: 100%;
  }
</style>