<template> 
    <div class="card">
        <img :src="image" alt="#">
        <p>
            {{description}}
        </p>
    </div>
</template>

<script>
    export default {
        name: "card",
        props: {
            image: String,
            description: String,
        }
    }
</script>

<style lang="scss">
    @import "../assets/css_var/colors.scss";

</style>