<script lang="ts">
	import { navbarData } from './../resources/linkUtil.js';
  import Navbar from '../components/navbar.svelte';
  import LoginView from '../views/login_view.svelte';
    import Signup from '../views/signup.svelte';

</script>

<Navbar data={navbarData}></Navbar>

<main>
  <div class="background">
    <div class="content">
      <Signup></Signup>
    </div>
  </div>
  
</main>

<style>
  .background{
    position:fixed;
    padding:0;
    margin:0;

    top:0;
    left:0;

    width: 100%;
    height: 100%;
    background:#84FF5E;
  }

</style>
