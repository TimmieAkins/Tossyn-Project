<template>
    <nav>
        <ul>
            <li>
                <router-link to="/">Home</router-link>
            </li>
            <li>
                <router-link to="/about">About</router-link>
            </li>
            <li>
                <router-link to="/services">Services</router-link>
            </li>
            <li>
                <router-link to="/self-care">Self-care Course</router-link>
            </li>
            <li>
                <router-link to="/speaking">Speaking</router-link>
            </li>
            <li>
                <router-link to="/contact">Contact</router-link>
            </li> 
        </ul>
    </nav>
</template>

<style scoped>
ul {
    margin: 0 20px;
    display: flex;
    justify-content: space-between;
    align-items: center;
    list-style-type: none;
}

li {
    margin: 0 1rem;
    font-size: 1.2rem;
}

a {
    text-decoration: none;
    color: #222831;
    font-weight: bold;
    border-bottom: 2px solid transparent;
    padding-bottom: 0.25rem;
    transition: all .50s ease;
}

/* a:hover,
a:active,
a.router-link-active {
    color: #151c5c;
    border-color: #151c5c;
} */
</style>