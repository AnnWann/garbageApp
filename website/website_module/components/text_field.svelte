<script lang=ts>
    export let hint:string;
</script>

<style>
    input{
        width: 100%;
        height: 100%;
        padding: 12px 20px;
        margin: 8px 0;
        display: inline-block;
        border: 6px solid #9CE685;
        background-color: white;
        color: black;
        border-radius: 60px;
        box-sizing: border-box;
    }
</style>
<div>
    <input type="text" id="text_field" placeholder={hint}>
</div>