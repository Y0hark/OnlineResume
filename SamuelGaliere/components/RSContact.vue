<template>
    <div>
        <img :src="icon"><a :href="accountLink" target="_blank">{{ accountName }}</a>
    </div>
</template>

<script>
export default {
    name: "RSContact",
    props: ["icon", "accountLink", "accountName"]
}
</script>

<style>

</style>