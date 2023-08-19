<script>
import { defineComponent } from 'vue';

import TheNavigation from "./TheNavigation.vue";

export default defineComponent({
    components: {
        TheNavigation
    }
})
</script>

<template>
    <header>
        <h1>
            <router-link to='/'>Oluwatosin</router-link>
        </h1>
        <TheNavigation />
    </header>
</template>


<style scoped>
header {
    width: 100%;
    height: 10vh;
    padding: 0 50px;
    display: flex;
    justify-content: space-between;
    align-items: center;
    background-color: #f9f9f9;
    color: #222831;
}

h1 {
    color: #FFC8DD;
    font-size: 40px;
    font-weight: 400;
}

ul {
    margin: 0 20px;
    display: flex;
    justify-content: space-between;
    align-items: center;
    list-style-type: none;
}

li {
    margin: 0 1rem;
    font-size: 1.5rem;
}

a {
    text-decoration: none;
    color: #222831;
    font-weight: bold;
    padding-bottom: 0.25rem;
    transition: all .50s ease;
}

a.router-link-active {
    color: #f34949;
    border-color: #151c5c;
}

i {
    font-size: 50px;
    margin-top: 10px;
    cursor: pointer;
    /* display: none; */
}

</style>