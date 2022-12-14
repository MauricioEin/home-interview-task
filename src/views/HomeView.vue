
<template>
  <app-header />
  <main class="app-main">
    <app-hero />
    <feature-list />
    <middle-banner />
    <review-list />
    <signup />
  </main>
  <app-footer />
</template>

<script>
import appHeader from '../cmps/app-header.vue'
import appHero from '../cmps/app-hero.vue'
import featureList from '../cmps/feature-list.vue'
import middleBanner from '../cmps/middle-banner.vue'
import reviewList from '../cmps/review-list.vue'
import signup from '../cmps/signup.vue'
import appFooter from '../cmps/app-footer.vue'

export default {
  components: {
    appHeader,
    appHero,
    featureList,
    middleBanner,
    reviewList,
    signup,
    appFooter
  },
  data() {
    return {

    }
  },
  computed: {},
  methods: {},
}
</script>
