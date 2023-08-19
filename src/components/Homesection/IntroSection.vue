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
    <section class="introduction">
    <div class="aor">
        <div class="aor-img">
            <img src="../img/pexels-antoni-shkraba-7579190.jpg" alt="">
        </div>
        <div class="intro">
            <h1>HELLO, I'M OLUWATOSIN</h1>
            <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Dolorem, aliquam? Esse quasi odit possimus porro aliquid deleniti ullam ratione mollitia explicabo? Magni, voluptate enim atque architecto rerum sequi officiis aliquid inventore autem, illo obcaecati vitae.</p>
            &nbsp;
            <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Alias illo dolore et cum quam a, exercitationem esse accusamus quod quos magni quibusdam blanditiis accusantium? Doloremque ea pariatur rerum temporibus ducimus nam id saepe nihil voluptatem quia debitis minima modi tempora eligendi nemo quisquam, reprehenderit, eos eveniet porro expedita, numquam error.</p>
            <base-button>
                <h3>START YOUR JOURNEY</h3>
            </base-button>
        </div>
    </div>
    </section>
</template>


<style scoped>
.introduction {
width: 80%;
margin: 50px auto;
padding: 0 40px;
/* background-color:antiquewhite; */
color:black;
display: flex;
flex-direction: row;
align-items: center;
justify-content: space-between;
}

.aor {
padding-top: 50px;
display: flex;
flex-direction: row;
align-items: center;
justify-content: space-between;
}

.aor div {
width: 50%;
/* height: 100vh; */
}

.aor-img img{
width: 400px;
height: 500px;
border-radius: 20px;
display: flex;
justify-content: ;
}

.intro {
text-align: start;
}

.intro h1 {
font-size: 40px;
font-weight: 800;
}

.intro p {
font-size: 20px;
}
</style>