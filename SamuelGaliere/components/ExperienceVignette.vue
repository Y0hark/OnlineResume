<template>
    <div>
        <h3>{{ titre }}</h3>
        <img :src="imageURL">
    </div>
</template>


<script>
export default {
    name: 'ExperienceVignette',
    props: ["titre", "imageURL" ]
}
</script>


<style>

</style>