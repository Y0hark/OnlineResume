<template>
    <div>
        <div class="blockExperience">
            <h3>{{ nomEntreprise }}</h3>
            <img :src="logoEntreprise">
        </div>
        <div class="blockExperience">
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
    .blockExperience{
        display: inline-block;
        text-align: left;
        position: relative;
        width: 30%;
        vertical-align:top;
        padding: 0.5%;
    }
</style>