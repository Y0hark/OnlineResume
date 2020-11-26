<template>
    <div>
        <div class="blockColomn">
            <h3>{{ nomEntreprise }}</h3>
            <img :src="logoEntreprise">
        </div>
        <div class="blockColomn">
            <h3>{{ ExperienceTitre }}</h3> <span> - {{ date }}</span>
            <p>{{ description }}</p>
        </div>
    </div>    
</template>

<script>
export default {
    name: 'ExperienceDetail',
    props: ["nomEntreprise", "logoEntreprise", "ExperienceTitre", "date", "description"]
}
</script>


<style>
    .blockColomn{
        display: inline-block;
        text-align: left;
        position: relative;
        width: 30%;
        vertical-align:top;
        padding: 0.5%;
    }
</style>