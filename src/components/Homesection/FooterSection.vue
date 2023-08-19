<template>
    <footer>
        <div class="thefooter">
            <div class="container">
                <div class="footer-ex">
                    <h2>EXPLORE</h2>
                    <div class="footer-link">
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
                    </div>
                    <div class="footer-contact">
                        <button>CONTACT US</button>
                        <div class="footer-icons"></div>
                    </div>
                </div>
                <div class="footer-words">
                    <div class="word-h3">
                        <h3>Get your Monday Reminder</h3>
                        <p>Receive a dose of inspiration and love directly in your inbox every week.</p>
                    </div>
                    <div class="privacy">
                        <ul>
                            <li>
                                <router-link to="/privacy">Privacy Policy</router-link>
                            </li>
                            <li>
                                <router-link to="/terms">Teams To Use</router-link>
                            </li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>
        <div class="copyright">
            <h4> copyright &copy Oluwatosin Akinde</h4>
        </div>
    </footer>
</template>

<style scoped>
footer {
    width: 100%;
    display: flex;
    flex-direction: column;
}

.thefooter {
    width: 100%;
    height: 300px;
    display: flex;
    flex-direction: row;
    gap: 20px;
    align-items: start;
    justify-content: space-between;
    background-color: peru;
}

.container {
    width: 80%;
    margin: 0 auto;
    display: flex;
}

.footer-ex {
    width: 250px;
    margin-right: 30px;
    background-color: rgb(200, 237, 250);
    position: relative;
    top: -45px;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
}

h2 {
    font-size: 24px;
    margin: 20px 0
}

ul {
    /* margin: 0 20px; */
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    align-items: start;
    list-style-type: none;
}

li {
    margin: 0.3rem 0;
    font-size: 1rem;
}

a {
    text-decoration: none;
    color: #222831;
    font-weight: bold;
    border-bottom: 2px solid transparent;
    padding-bottom: 0.25rem;
    transition: all .50s ease;
}

.footer-words {
    margin: 30px 20px;
    display: flex;
    flex-direction: column;
    align-items: end;
    justify-content:start;
}

.word-h3 {
    text-align: end;
}


.copyright {
    width: 100%;
    height: 25px;
    background-color: indianred;
    text-align: center;
}

.copyright h4 {
    padding: 5px 0;
}
</style>