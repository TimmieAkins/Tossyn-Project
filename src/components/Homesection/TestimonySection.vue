<template>
    <section class="testimony">
        <div class="testimonials">
            <h1>TESTIMONIALS</h1>
        </div>
        <div class="test-name">
            <h3>T. HENRY</h3>
            <h4>Reclaim & Rise</h4>
            <hr class="style-hr">
        </div>
        <div class="test-word">
            <h3><strong> &quot;Lorem ipsum dolor sit amet consectetur adipisicing.&quot;</strong></h3>
            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Excepturi atque officia minima doloremque ad
                distinctio tenetur quo nemo exercitationem id blanditiis sapiente quos illo, labore quisquam. Numquam saepe
                maiores recusandae eius eaque dignissimos qui atque assumenda nam in tenetur iure architecto mollitia nobis
                vel, quia, suscipit, sed iusto nisi voluptate.</p>
        </div>
        <div class="test-ratings">
            <div class="star-rating">
                <input type="radio" id="star5" name="rating" value="5">
                <label for="star5" class="fa-solid fa-star"></label>
                <input type="radio" id="star4" name="rating" value="4">
                <label for="star4" class="fa-solid fa-star"></label>
                <input type="radio" id="star3" name="rating" value="3">
                <label for="star3" class="fa-solid fa-star"></label>
                <input type="radio" id="star2" name="rating" value="2">
                <label for="star2" class="fa-solid fa-star"></label>
                <input type="radio" id="star1" name="rating" value="1">
                <label for="star1" class="fa-solid fa-star"></label>
            </div>
        </div>
        <base-button>
            <h3>READ MORE</h3>
        </base-button>
    </section>
</template>

<style scoped>
.testimony {
    width: 80%;
    /* height: 100vh; */
    margin: 50px auto;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
}

.test-name {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
}

.testimonials h1 {
    font-size: 46px;
    color: coral;
}

.test-name h3 {
    font-size: 30px;
    color: rgb(254, 151, 114);
}

.test-name h4 {
    font-size: 22px;
    color: rgb(255, 177, 149);
}

.style-hr {
    border: none;
    color: black;
    background-color: #333;
    margin: 10px 0;
}

.test-word {
    margin: 20px auto;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    text-align: center;
}

.test-word h3 {
    font-size: 24px;
    margin-bottom: 10px;
}

.test-word p {
    font-size: 20px;
}

.test-ratings {
    margin: 20px auto;
}

.star-rating {
    display: flex;
    flex-direction: row;
    color: lightcoral;
}

.star-rating input {
    display: none;
}

.star-rating input+label {
    font-size: 20px;
}
</style>