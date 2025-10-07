<script lang="ts">
    import { cubicOut } from "svelte/easing";
import Box from "./lib/Box.svelte";
import { fade, blur, fly, slide, scale } from "svelte/transition";
</script>

<main>
  <h1 in:slide='{{ delay: 500, easing: cubicOut }}' >Mason Beard</h1>
  <Box title="About Me" body = ""/>
  <Box title="" body = ""/>   
</main>

<style>
  h1{
    text-align: center;
    font-size: 75px;
    font-family: sans-serif;
    
  }

</style>
