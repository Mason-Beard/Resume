<script lang="ts">
    export let title: string
    export let body: string    
</script>
<div>
    <h1>
        {body}
    </h1>
    {body}
</div>

<style>
    div{
        background-color: #474747;
        width: 100px;
        height: 100px;
        margin: auto;
        border-radius: 15%;
        display: grid;
        place-items: center;
        color: #000000;
        outline-color: aqua;
    }

</style>