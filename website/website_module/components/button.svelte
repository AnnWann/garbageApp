<script lang=ts>
    export let login:string;
</script>

<style>
    input[type=submit] {
        width: 100%;
        height: 100%;
        background-color: #E65ECF;
        color: black;
        padding: 14px 20px;
        margin: 14px 20px;
        border: 6px solid #9CE685;     
        border-radius: 60px;
        cursor: pointer;
        font-weight: bold;
    }

    input[type=submit]:hover{
        background-color: #e65ecfc5;
    }
</style>

<div>
    <input type="submit" id="text_field" value={login}>
</div>