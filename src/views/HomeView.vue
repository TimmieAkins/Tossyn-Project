<script>
import { defineComponent } from "vue";

import BaseButton from "../components/UI/BaseButton.vue";
import HelpCard from "../components/UI/HelpCard.vue";
import HomePage from "../components/Homesection/HomePage.vue";
import IntroSection from "../components/Homesection/IntroSection.vue";
import HelpSection from "../components/Homesection/HelpSection.vue";
import ProcessSection from "../components/Homesection/ProcessSection.vue";
import TestimonySection from "../components/Homesection/TestimonySection.vue";
import ContainerSection from "../components/Homesection/ContainerSection.vue";
import BlogSection from "../components/Homesection/BlogSection.vue";
import ExploreSection from "../components/Homesection/ExploreSection.vue";
import FooterSection from "../components/Homesection/FooterSection.vue";

export default defineComponent({
  components: {
    BaseButton,
    HelpCard,
    HomePage,
    IntroSection,
    HelpSection,
    ProcessSection,
    TestimonySection,
    ContainerSection,
    BlogSection,
    ExploreSection,
    FooterSection,
  }
})
</script>

<template>
  <HomePage />
  <IntroSection />
  <HelpSection />
  <ProcessSection />
  <TestimonySection />  
  <ContainerSection />
  <BlogSection />  
  <ExploreSection />
  <FooterSection />
</template>
