<script>
import { defineComponent } from "vue";

import HelpCard from "../UI/HelpCard.vue";

export default defineComponent({
    components: {
        HelpCard
    }
})
</script>

<template>
    <section class="help-you">
        <div class="help-intro">
            <h3>Lorem ipsum dolor sit amet, consectetur adipisicing.</h3>
            <h1>Lorem ipsum dolor sit amet consectetur.</h1>
        </div>
        <help-card></help-card>
    </section>
</template>

<style scoped>
.help-you {
width: 100%;
/* height: 100vh; */
padding: 20px 40px 0 40px;
background-color:antiquewhite;
}

.help-intro {
margin: 20px 0;
display: flex;
flex-direction: column;
align-items: center;
justify-content: center;
}

.help-intro h3 {
/* margin-bottom: 10px; */
font-size: 30px;
}

.help-intro h1 {
font-size: 60px;
margin-bottom: 10px;
}
</style>