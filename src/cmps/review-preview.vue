<template>
    <article class="review-preview flex column space-between">

<p class="review-txt smaller">{{review.txt}}</p>
<div class="reviewer flex">
    <img :src="imgSrc"/>
    <div class="reviewer-info">
        <p class="reviewer-name"> {{review.name}}</p>
        <p class="reviewer-pos"> {{review.pos}}</p>
    </div>
</div>

    </article>
</template>


<script>
export default {
    props: ['review'],
    components: {},

    computed: {
        imgSrc() {
            return new URL(this.review.imgPath, import.meta.url).href
        }
    },
}

</script>