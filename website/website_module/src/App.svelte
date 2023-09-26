<script lang="ts">
	import Button from '../components/button.svelte';
import TextField from './../components/text_field.svelte';
</script>

<main>
  <div>
    <TextField hint="usuário"/>
    <TextField hint="senha"/>
    <Button login="login"/>
  </div>
</main>

<style>
  
</style>
