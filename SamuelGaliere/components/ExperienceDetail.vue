<template>
    <div>
     <h2>{{ ExperienceTitre }}</h2> <span> - {{ date }}</span>
     <p>{{ description }}</p>

    </div>    
</template>

<script>
export default {
    name: 'ExperienceDetail',
    props: ["ExperienceTitre", "date", "description"]
}
</script>


<style>

</style>