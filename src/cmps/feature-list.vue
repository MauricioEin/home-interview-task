<template>
    <section class="feature-list">
        <article class="feature-preview">
            <img src="../assets/svgs/icon-access-anywhere.svg" />
            <h3>{{ features[0].title }}</h3>
            <p class="smaller">{{ features[0].desc }}</p>
        </article>
        <article class="feature-preview">
            <img src="../assets/svgs/icon-security.svg" />
            <h3>{{ features[1].title }}</h3>
            <p class="smaller">{{ features[1].desc }}</p>
        </article>
        <article class="feature-preview">
            <img src="../assets/svgs/icon-collaboration.svg" />
            <h3>{{ features[2].title }}</h3>
            <p class="smaller">{{ features[2].desc }}</p>
        </article>
        <article class="feature-preview">
            <img src="../assets/svgs/icon-any-file.svg" />
            <h3>{{ features[3].title }}</h3>
            <p class="smaller">{{ features[3].desc }}</p>
        </article>

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
                    title: 'Access your files, anywhere',
                    desc: 'The ability to use a smartphone, tablet, or computer to access your account means your files follow you everywhere.'
                },
                {
                    img: '../assets/svgs/icon-security.svg',
                    title: 'Security you can trust',
                    desc: '2-factor authentication and user-controlled encryption are just a couple of the security features we allow to help secure your files.'
                },
                {
                    title: 'Real-time collaboration',
                    desc: 'Securely share files and folders with friends, family and colleagues for live collaboration. No email attachments required.'
                },
                {
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