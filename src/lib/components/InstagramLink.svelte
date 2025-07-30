<script lang="ts">   
  import IconLink from './IconLink.svelte';

  export let path: string; 
  export let small = false;
</script>

<IconLink href="https://instagram.com/{path}" icon="bxl-instagram" label="Instagram" {small} />
