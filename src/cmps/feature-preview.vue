<template>
    <section class="feature-preview">
        <img :src="imgSrc" />
        <h3>{{ feature.title }}</h3>
        <p class="smaller">{{ feature.desc }}</p>
    </section>
</template>


<script>
export default {
    props: ['feature'],
    components: {},
    computed: {
        imgSrc() {
            return new URL(this.feature.imgPath, import.meta.url).href
        }
    },
}

</script>