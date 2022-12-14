<template>
    <section class="feature-preview">
<img :src="imgSrc"/>
<h3>{{feature.title}}</h3>
<p class="smaller">{{feature.desc}}</p>
    </section>
</template>


<script>
export default {
    props: ['feature', 'imgSrc'],
    components: {},
    data() {
        return {

        }
    },
    computed: {},
    methods: {},
}

</script>