<template>
    <section>
        <div class="blog">
            <div class="blog-heading">
                <h1>LATEST FROM THE BLOG</h1>
            </div>
            <div class="blog-posts">
                <div class="blog-post">
                    <h3><strong>Lorem ipsum, dolor sit amet consectetur adipisicing.</strong></h3>
                    <hr>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Eius animi cumque perspiciatis nostrum esse
                        doloremque veritatis nam corrupti, ad iste, placeat expedita, voluptatum nihil assumenda illum sunt
                        ut quae in porro possimus numquam voluptatibus. Ad, inventore.</p>
                </div>
                <div class="blog-post">
                    <h3><strong>Lorem ipsum dolor sit amet consectetur.</strong></h3>
                    <hr>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Exercitationem ipsam consequatur assumenda
                        dolorem minima quae in, fuga voluptates nihil neque libero velit esse rem rerum?</p>
                </div>
                <div class="blog-post">
                    <h3><strong>Lorem ipsum dolor sit amet.</strong></h3>
                    <hr>
                    <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Delectus aut reprehenderit expedita at ab,
                        modi vitae obcaecati, id amet tempore reiciendis corporis non esse aspernatur totam enim illo?</p>
                </div>
            </div>
            <div class="blog-button">
                <button>READ MORE</button>
            </div>
        </div>
    </section>
</template>

<style scoped>
.blog {
    width: 80%;
    /* height: 100vh; */
    margin: 50px auto;
    display: flex;
    flex-direction: column;
    align-items: start;
    /* justify-content:space-between; */
}

.blog-posts {
    margin: 20px 0;
    text-align: start;
}

.blog-post {
    margin-bottom: 20px;
}

.blog-heading h1 {
    font-size: 46px;
    color: coral;
    margin-bottom: 20px;
}

.blog-post h3 {
    font-size: 30px;
    margin-bottom: 10px;
    /* color: rgb(254, 151, 114); */
}

.blog-post hr {
    width: 100px;
    height: 3px;
    background-color: coral;
    border: none;
    border-radius: 2px;
}

.blog-post p {
    font-size: 20px;
}

.blog-button {
    display: flex;
    align-self: center;
    justify-content: center;
}
</style>