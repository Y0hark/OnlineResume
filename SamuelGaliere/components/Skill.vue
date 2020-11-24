<template>
    <div>
        <label :for="label">{{ label }}</label>
        <progress :id="label" :value="progress" max="100"></progress>
    </div>
</template>

<script>
export default {
    name: 'Skill',
    props: [ "label", "progress",]
}
</script>

<style>

</style>