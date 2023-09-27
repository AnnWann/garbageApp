<script>
    import Button from "../components/button.svelte";
    import PasswordField from "../components/password_field.svelte";
    import TextField from "../components/text_field.svelte";
    import {login_title_str, user_str, password_str, login_button_str} from '../resources/strings.json';

    function validate_login(){

    }

</script>

<div class="view">
    <div class="form_div">
        <h1 style="font-weight: bold; color: black; margin-bottom: 10px">{login_title_str}</h1>
        <form class="form">
            <TextField hint={user_str} />
            <PasswordField hint={password_str} />
            <Button message={login_button_str} method={validate_login} />
        </form>
    </div>
    
    <div class="side_img">
        <div class="img_container">
            <img src="../resources/download.jpg" alt="">
        </div>
    </div>
</div>

<style>
    .view{
        display: flex;
        align-items: flex-start;
        margin: 20px;
    }
    .form_div{
        flex: 1;
        display: flex;
        flex-direction: column;
        align-items: flex-start;
        text-align: center;
        padding: 20px;
    }
    .side_img{
        flex: 1;
    }
    .img_container{
        border-radius: 10px;
        overflow: hidden;
        margin-top: 20px;
    }

    .img_container img{
        width: 100%;
        height: auto;
    }

</style>