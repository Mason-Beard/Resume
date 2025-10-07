<script lang="ts">
    export let title: string
    export let body: string    
</script>
<div>
    <h1>
        {title}
    </h1>
    {body}
</div>

<style>
    div{
        background-color: #474747; 
        width: 400px;
        height: 250px;
        grid-column: auto;
        margin: auto;
        border-radius: 5%;
        display: grid;
        place-items: center;
        color: #ffffff;
        outline-style:solid;
        outline-color: #303030;
    }

</style>