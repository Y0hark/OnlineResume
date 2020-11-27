<template>
    <div class="contactBlock">
        <form class="contactButton" action="mailto:samuelgaliere.pro@gmail.com"> <button type="submit" class="btn btn-primary">Mail</button> </form>
        <button type="button" class="btn btn-primary contactButton" onClick="window.open('https://www.linkedin.com/in/samuel-galiere/', '_blank')">LinkedIn</button>
        <button type="button" class="btn btn-primary contactButton" onClick="window.open('https://drive.google.com/file/d/15gXie4t8jI1cxd1JN4N44nOo5AQ6geyc/view?usp=sharing', '_blank')">C.V</button>
    </div>
</template>

<script>
export default {
    name: "Contact"
}
</script>

<style>
.contactButton{
    display: inline-block;
}

.contactBlock{
    position: absolute;
    top: 40%;
    left: 17%;
}

</style>