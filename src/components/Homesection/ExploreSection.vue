<template>
    <section class="explore">
        <div class="blur-overlay"></div>
        <div class="ex-content">
            <h1>LET'S EXPLORE HOW YOU CAN GET STARTED</h1>
            <P>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Ratione eveniet debitis sunt enim dolorem voluptas?
            </P>
            <BaseButton>START YOUR JOURNEY</BaseButton>
        </div>
    </section>
</template>

<style scoped>
.explore {
    width: 100%;
    height: 100vh;
    padding: 40px;
    background-image: url(..\img\pexels-tima-miroshnichenko-5711163.jpg);
    background-repeat: no-repeat;
    background-size: cover;
    background-position: center;
    position: relative;
    display: flex;
    align-items: center;
    justify-content: center;
}

.blur-overlay {
    width: 100%;
    height: 100%;
    position: absolute;
    top: 0;
    left: 0;
    backdrop-filter: blur(3px);
    background-color: rgba(255, 255, 255, 0.1);
}

.ex-content {
    width: 80%;
    margin: 30px auto;
    padding: 40px 0;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    background-color: antiquewhite;
    border-radius: 20px;
    z-index: 1;
}

.ex-content h1 {
    font-size: 40px;
    margin-bottom: 20px;
}

.ex-content p {
    font-size: 20px;
    margin-bottom: 15px;
}
</style>