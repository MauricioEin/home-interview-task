<template>
    <section class="feature-list">
        <feature-preview v-for="(feature, index) in features"
         :key="index" :feature="feature" />
    </section>
</template>


<script>
import featurePreview from './feature-preview.vue'
export default {
    props: [],
    components: { featurePreview },
    data() {
        return {
            features: [
                {
                    imgPath: '../assets/svgs/icon-access-anywhere.svg',
                    title: 'Access your files, anywhere',
                    desc: 'The ability to use a smartphone, tablet, or computer to access your account means your files follow you everywhere.'
                },
                {
                    imgPath: '../assets/svgs/icon-security.svg',
                    title: 'Security you can trust',
                    desc: '2-factor authentication and user-controlled encryption are just a couple of the security features we allow to help secure your files.'
                },
                {
                    imgPath: '../assets/svgs/icon-collaboration.svg',
                    title: 'Real-time collaboration',
                    desc: 'Securely share files and folders with friends, family and colleagues for live collaboration. No email attachments required.'
                },
                {
                    imgPath: '../assets/svgs/icon-any-file.svg',
                    title: 'Store any type of file',
                    desc: 'Whether you\'re sharing holidays photos or work documents, Fylo has you covered allowing for all file types to be securely stored and shared.'
                },

            ]

        }
    },
    computed: {},
    methods: {},
}

</script>