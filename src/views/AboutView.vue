<script>
import { defineComponent } from 'vue';

import AboutIntro from '../components/AboutSection/AboutIntro.vue';
import MyStory from '../components/AboutSection/MyStory.vue';
import FooterSection from '../components/HomeSection/FooterSection.vue';

export default defineComponent({
    components: {
        AboutIntro,
        MyStory,
        FooterSection
    }
})
</script>

<template>
    <AboutIntro />
    <MyStory />
    <FooterSection />
</template>

<style>
</style>
