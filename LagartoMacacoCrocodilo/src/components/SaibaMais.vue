<template>
    <a href="#" class="button">
        <span>Saiba mais</span>
    </a>
</template>

<script>
    export default{
        name: "button"
    }
</script>

<style>
    .button{
        width: 200px;
        height: 30px;
        color: #fff;
        transition: .2s;
        border-radius: 10px;
        background-color: #000;
        border: #000 solid 2px;
        display: block;
        margin-left: 75px;
    }

    .button:hover{
        color: black;
        background-color: #fff;
    }

    span{
        text-transform: uppercase;
        position: relative;
        font-size: 16px;
        top: 2px;
        left: 50px;
    }

    span::after{
        content: '+';
        display: inline;
        width: 40px;
        height: 40px;
        margin-left: 30px;
    }

</style>