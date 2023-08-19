<template>
    <section class="intro">
        <div class="about-intro">
            <div class="about-writeup">
                <h1>HELLO, <br> I'M <span>OLUWATOSIN AKINDE</span></h1>
                <h3>Transformation Coach</h3>
                <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Repellendus eum sequi obcaecati ducimus voluptatibus esse eos quaerat veritatis commodi deleniti magnam, tempore non exercitationem necessitatibus voluptate laudantium blanditiis! Dolore cupiditate tempora maxime rerum, veritatis ea fuga dolorem ducimus perferendis neque velit dolor architecto assumenda corporis eveniet consequuntur repellat adipisci vitae delectus laudantium et similique, ullam odit illo? Molestiae iure rem necessitatibus? Ad atque sed, similique.</p>
                <p>Esse, cupiditate nesciunt inventore repellat illum quos commodi omnis! Perspiciatis obcaecati magnam recusandae exercitationem! Fuga inventore accusantium enim ex quasi saepe facere ea quod impedit consequatur nemo, ducimus quas perspiciatis? reiciendis repellendus voluptatem possimus dolores quaerat, accusamus quidem aspernatur quia officia vel officiis.</p>
                <p>Fuga soluta sed sapiente veniam perspiciatis magnam, quas at eligendi dolor consequatur dolorem alias deleniti blanditiis. Dolorem nulla quisquam maxime a culpa eligendi, aliquam, adipisci ea omnis natus pariatur sequi tempora laboriosam commodi. Quisquam officia eligendi deserunt voluptas excepturi fugit in possimus, veniam recusandae alias.</p>
            </div>
            <div class="about-img">
                <div class="the-img">
                    <img src="../img/pexels-antoni-shkraba-7579315.jpg" alt="">
                </div>
            </div>
        </div>
    </section>
</template>

<style>
section {
    width: 80%;
    margin: 0 auto;
}

.about-intro {
    width: 100%;
    padding: 30px 0;
    display: flex;
    flex-direction: row;
    gap: 10px;
}

.about-writeup {
    flex: 1;
    flex-basis: 50%;
}

.about-writeup h1 {
    font-size: 46px;
    /* margin-bottom: 5px; */
}

span {
    color: coral
}

h3 {
    font-size: 22px;
    color: rgb(254, 151, 114);
    margin-bottom: 30px;
}

p {
    font-size: 22px;
    margin-bottom: 7px;
}

.about-img {
    height: 600px;
    flex: 2;
    flex-basis: 50%;
}

.the-img img{
    width: 100%;
    height: 100%;
    border-radius: 20px;
}
</style>