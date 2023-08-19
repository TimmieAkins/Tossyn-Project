<script>
import { defineComponent } from "vue";

import BaseButton from "../UI/BaseButton.vue";

export default defineComponent({
    components: {
        BaseButton
    }
})
</script>

<template>
    <section>
        <div class="process">
            <div class="process-wu">
                <h2>THE TRANSFORMATION PROCESS</h2>
                <P>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Facilis, quisquam saepe magni velit reiciendis
                    quod iste est repellat voluptatum repudiandae pariatur tenetur vel veritatis quis consectetur libero!
                    Voluptatum, eveniet eaque. </P>
            </div>
            <div class="process-flex">
                <div class="pf-1 pf">
                    <h3>1. Lorem ipsum dolor sit.</h3>
                    <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Omnis ad repellat nobis!</p>
                </div>
                <div class="pf-2 pf">
                    <h3>2. Lorem ipsum dolor sit.</h3>
                    <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Error, eaque.</p>
                </div>
                <div class="pf-3 pf">
                    <h3>3. Lorem, ipsum dolor.</h3>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Labore, ab ipsa.</p>
                </div>
                <div class="pf-4 pf">
                    <h3>3. Lorem ipsum dolor sit.</h3>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Accusamus eum voluptatibus facilis.</p>
                </div>
            </div>
            <base-button>
                <h3>START YOUR JOURNEY</h3>
            </base-button>
        </div>
    </section>
</template>

<style scoped>
.process {
    width: 80%;
    margin: 20px auto;
    padding-bottom: 50px;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
}

.process-wu {
    padding: 40px 300px 0 0;
    margin: 40px 0 30px 0;
}

.process-wu h2 {
    font-size: 46px;
    color: coral;
}

.process-wu p {
    font-size: 20px;
}

.process-flex {
    margin-bottom: 20px;
    display: flex;
    flex-direction: row;
    align-items: start;
    justify-content: space-between;
}

.pf {
    padding-right: 25px;
    /* margin-top: auto; */
}
</style>