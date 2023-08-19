<script>
import { defineComponent } from 'vue';

import BaseButton from '../UI/BaseButton.vue';

export default defineComponent({
    components: {
        BaseButton
    }
})
</script>

<template>
    <section class="my-story">
        <div class="the-story">
            <h1>MY STORY</h1>
        </div>
        <div class="story">
            <div class="first-block">
                <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Odit culpa deleniti autem dignissimos nemo porro molestias. Veritatis similique aperiam placeat accusamus blanditiis dicta alias numquam laborum aliquid sed asperiores tenetur aliquam, error quam! Dolore iure expedita, molestias sequi atque, ipsa quaerat illo cum magnam deserunt ad cumque reiciendis soluta vel.</p>
                <br>
                <h3>&quot;Lorem ipsum dolor sit amet consectetur adipisicing elit. Repudiandae ipsam nobis adipisci.&quot;</h3>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Repudiandae laboriosam omnis, eveniet dignissimos illo quis ipsam iure nemo iusto, reiciendis, mollitia cum sit culpa. Natus soluta veritatis recusandae laudantium vero maxime facilis quos libero similique suscipit officiis, commodi quod repellat sed non obcaecati quo accusantium fugit repellendus ipsum inventore. Dolores quo quos eos beatae omnis officiis ea reprehenderit! Deleniti est veritatis quidem veniam, placeat cupiditate laudantium sunt. Suscipit, nesciunt sapiente!
                </p>
            </div>
            <div class="second-block">
                <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Odit culpa deleniti autem dignissimos nemo porro molestias. Veritatis similique aperiam placeat accusamus blanditiis dicta alias numquam laborum aliquid sed asperiores tenetur aliquam, error quam! Dolore iure expedita, molestias sequi atque, ipsa quaerat illo cum magnam deserunt ad cumque reiciendis soluta vel.
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Repudiandae laboriosam omnis, eveniet dignissimos illo quis ipsam iure nemo iusto, reiciendis, mollitia cum sit culpa.</p>
                <br>
                <h3>&quot;Lorem ipsum dolor sit amet, consectetur adipisicing elit. Suscipit, ratione!&quot;</h3>
                <p>Natus soluta veritatis recusandae laudantium vero maxime facilis quos libero similique suscipit officiis, commodi quod repellat sed non obcaecati quo accusantium fugit repellendus ipsum inventore. Dolores quo quos eos beatae omnis officiis ea reprehenderit! Deleniti est veritatis quidem veniam, placeat cupiditate laudantium sunt. Suscipit, nesciunt sapiente!
                </p>
            </div>
        </div>
        <div class="button">
            <BaseButton>
                <h3>LET'S WORK TOGETHER</h3>
            </BaseButton>
        </div>
    </section>
</template>

<style scoped>
.my-story {
    width: 80%;
    margin: 0 auto;
    padding-bottom: 70px;
}

.the-story {
    width: 100%;
    margin: 30px auto;
    display: flex;
    justify-content: center;
}

.the-story h1 {
    font-size: 46px;
    font-weight: 500;
    color: coral;
}

.story {
    width: 100%;
    padding: 20px;
    display: flex;
    flex-direction: row;
    justify-content: center;
    align-items: start;
    gap: 10px;
}

p {
    font-size: 22px;
    margin-bottom: 7px;
}

h3 {
    font-size: 26px;
    font-weight: 400;
    margin: 10px 0;
}

.first-block {
    flex: 1;
    flex-basis: 50%;
    padding-right: 10px;
}

.second-block {
    flex: 2;
    flex-basis: 50%;
    padding-left: 10px;
}

.button {
    width: 100%;
    margin: 0 auto;
    display: flex;
    justify-content: center;
}
</style>