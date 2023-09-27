<script lang="ts">
	import Upperbar from './../components/upperbar.svelte';
  import LoginView from '../views/login_view.svelte';

  let a = 1;
  function login(){
    a++;
  }
</script>

<Upperbar></Upperbar>


<main>
  <div class="background">
    <div class="content">
      <LoginView></LoginView>
    </div>
  </div>
  
</main>

<style>
  .background{
    background-color: #84FF5E;
    min-height: 100vh;
    width: 100%;
    position: fixed;
    top: 52px;
    left: 0;
  }

</style>
