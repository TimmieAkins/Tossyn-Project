<script>
import { defineComponent } from "vue"; 

import BaseButton from "./BaseButton.vue";

export default defineComponent({
    components: {
        BaseButton
    }
})
</script>

<template>
    <div class="card-container">
        <div class="card">
            <div class="card-img">
                <img src="../img/pexels-shvets-production-7176233.jpg" alt="">
            </div>
            <div class="card-writeup">
                <h3>Lorem ipsum dolor sit amet, consectetur adipisicing elit.</h3>
                <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Minima sit nisi, voluptate itaque iste explicabo mollitia laudantium omnis numquam ut, inventore minus tempore est atque.</p>
                <h4>Lorem ipsum dolor sit, amet consectetur adipisicing.</h4>
            </div>
            <div class="card-button">
                <base-button>
                    <h3>EXPLORE THE GROWTH HUB</h3>
                </base-button>
            </div>
        </div>
        <div class="card">
            <div class="card-img">
                <img src="../img/pexels-shvets-production-7176233.jpg" alt="">
            </div>
            <div class="card-writeup">
                <h3>Lorem ipsum dolor sit amet, consectetur adipisicing elit.</h3>
                <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Minima sit nisi, voluptate itaque iste explicabo mollitia laudantium omnis numquam ut, inventore minus tempore est atque.</p>
                <h4>Lorem ipsum dolor sit, amet consectetur adipisicing.</h4>
            </div>
            <div class="card-button">
                <base-button>
                    <h3>EXPLORE THE GROWTH HUB</h3>
                </base-button>
            </div>
        </div>
        <div class="card">
            <div class="card-img">
                <img src="../img/pexels-shvets-production-7176233.jpg" alt="">
            </div>
            <div class="card-writeup">
                <h3>Lorem ipsum dolor sit amet, consectetur adipisicing elit.</h3>
                <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Minima sit nisi, voluptate itaque iste explicabo mollitia laudantium omnis numquam ut, inventore minus tempore est atque.</p>
                <h4>Lorem ipsum dolor sit, amet consectetur adipisicing.</h4>
            </div>
            <div class="card-button">
                <base-button>
                    <h3>EXPLORE THE GROWTH HUB</h3>
                </base-button>
            </div>
        </div>
    </div>
</template>

<style>
.card-container {
    width: 80%;
    margin: 0px auto;
    padding-bottom: 50px;
    display: flex;
    flex-direction: row;
    gap: 40px;
    align-items: center;
    justify-content: space-around;
}

.card {
    width: 300px;
    /* border: 2px solid red; */
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
}

.card-img img{
    margin: 0;
    padding: 0;
    width: 295px;
    height: 360px;
    border-top-left-radius: 45%;
    border-top-right-radius: 45%;
}

img {
    width: 100%;
    height: 100%;
}

.card-writeup {
    width: 100%;
    height: 330px;
    padding: 20px 10px;
    display: flex;
    flex-direction: column;
    align-items: center;
    /* justify-content: center; */
    text-align: center;
    background-color: rgba(207, 208, 209, 0.2);
}

.card-writeup h3 {
    /* margin: 10px 0; */
    font-size: 25px;
}

.card-writeup p {
    margin: 10px 0;
    font-size: 17px;
}

.card-writeup h4 {
    font-size: 20px;
    padding-bottom: 5px;
    margin-bottom: 10px;
}

.card-button {
    margin-top: 0;
}
</style>