<script lang="ts">
  import Mapgen from '../vendor/mapgen/Mapgen.svelte';
</script>

<style>
  .mapgen-container {
    position: fixed;
    height: 100%;
    width: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
  }
</style>

<div class="mapgen-container">
  <Mapgen />
</div>
