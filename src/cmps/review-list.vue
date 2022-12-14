<template>
    <section class="review-list flex">
        <review-preview/>
        <review-preview/>
        <review-preview/>
        <div class="ornament">“KISHUT</div>
    </section>
</template>


<script>
import reviewPreview from './review-preview.vue'
export default {
    props: [],
    components: {reviewPreview},
    data() {
        return {

        }
    },
    computed: {},
    methods: {},
}

</script>