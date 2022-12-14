<template>
    <header class="app-header flex space-between">

    <logo/>
    <nav class="flex space-between">
        <a href="#">Features</a>
        <a href="#">Team</a>
        <a href="#">Sign in</a>
    </nav>
    </header>
</template>


<script>
import logo from './logo.vue'
export default {
    props: [],
    components: {logo},
    data() {
        return {

        }
    },
    computed: {},
    methods: {},
}

</script>