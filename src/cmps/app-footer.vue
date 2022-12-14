<template>
    <footer class="app-footer">
        <logo />
        <section class="footer-info">
            <div class="flex">
                svg
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore
                    et dolore magna aliqua</p>
            </div>
            <ul class="clean-list smaller">
                <li><a href="#">svg <span>+1-543-123-4567</span></a></li>
                <li><a href="#">svg <span>example@fylo.com</span></a></li>
            </ul>
            <ul class="clean-list">
                <li><a href="#">About Us</a></li>
                <li><a href="#">Jobs</a></li>
                <li><a href="#">Press</a></li>
                <li><a href="#">Blog</a></li>
            </ul>
            <ul class="clean-list">
                <li><a href="#">Contact Us</a></li>
                <li><a href="#">Terms</a></li>
                <li><a href="#">Privacy</a></li>
            </ul>

            <div class="social-links">link link link</div>
        </section>

    </footer>
</template>


<script>
import logo from './logo.vue'
export default {
    props: [],
    components: { logo },
    data() {
        return {

        }
    },
    computed: {},
    methods: {},
}

</script>