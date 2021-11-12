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

    .card {
        width: calc(100% / 6);
        padding-bottom: 1rem;
        img {
             width: 170px;
             height: 170px;
             object-fit: cover;
             object-position: top;
        }

        p {
            margin: 0.5rem 0;
            margin-right: 1rem;
        }
    }

</style>