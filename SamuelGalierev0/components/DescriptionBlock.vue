<template>
    <div class="block">
        <h3 class="test">{{ titre }}</h3> 
        <p>{{ contenu }}</p>
    </div>
</template>


<script>
export default {
    name: 'DescriptionBlock',
    props: ["titre", "contenu"]
}
</script>


<style>
 .test{
     color: #88bedd;
 }
 .block{
    display: inline-block;
    text-align: left;
    position: relative;
    width: 30%;
    vertical-align:top;
    padding: 0.5%;
 }
</style>