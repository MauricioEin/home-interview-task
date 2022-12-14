<template>
    <section class="review-list flex space-between">
        <review-preview v-for="(review, index) in reviews" :key="index" :review="review" />
        <img class="quotes-img" src="../assets/imgs/bg-quotes.png" />
    </section>
</template>


<script>
import reviewPreview from './review-preview.vue'
export default {
    props: [],
    components: { reviewPreview },
    data() {
        return {
            reviews: [
                {
                    txt: 'Fylo has improved our team productivity by an order of magnitude. Since making the switch our team has become a well-oiled collaboration machine.',
                    name: 'Satish Patel',
                    pos: 'Founder & CEO, Huddle',
                    imgPath: '../assets/imgs/profile-1.jpg'
                },
                {
                    txt: 'Fylo has improved our team productivity by an order of magnitude. Since making the switch our team has become a well-oiled collaboration machine.',
                    name: 'Bruce McKenzie',
                    pos: 'Founder & CEO, Huddle',
                    imgPath: '../assets/imgs/profile-2.jpg'
                },
                {
                    txt: 'Fylo has improved our team productivity by an order of magnitude. Since making the switch our team has become a well-oiled collaboration machine.',
                    name: 'Iva Boyd',
                    pos: 'Founder & CEO, Huddle',
                    imgPath: '../assets/imgs/profile-3.jpg'
                }
            ]

        }
    },
    computed: {},
    methods: {},
}

</script>