<template>
    <div class="blockSkill">
        <label :for="label">{{ label }}</label>
        <div class="progress">
            <div class="progress-bar progress" role="progressbar" :style="progress" aria-valuenow="25" aria-valuemin="0" aria-valuemax="100"></div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'Skill',
    props: [ "label", "progress",]
}
</script>

<style>

.blockSkill{
    padding: 1%;
}

</style>