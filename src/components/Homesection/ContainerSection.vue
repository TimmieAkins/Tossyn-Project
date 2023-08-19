<template>
    <section>
        <div class="con-container">
            <div class="con-img">
                <img src="..\img\pexels-antoni-shkraba-7579315.jpg" alt="">
            </div>
            <div class="con-words">
                <div class="con-theword">
                    <h1>RECEIVE YOUR MONDAY REMINDER</h1>
                    <p>Every Monday, I sprinkle a dose of love in your inbox so you start your week feeling inspired to move
                        closer to being the next best version of yourself.</p>
                </div>
                <div class="con-form">
                    <form action="">
                        <div class="form-name">
                            <input type="text" id="name" placeholder="Name (required)" required>
                        </div>
                        <div class="form-email">
                            <input type="email" id="email" placeholder="Email (required)" required>
                        </div>
                        <div class="form-checkbox">
                            <label for="confirmation">
                                <input type="checkbox" name="agreement" id="confirmation" value="confirmation">
                                I agree to receive confirmation emails
                            </label>
                            <label for="terms">
                                <input type="checkbox" name="agreement" id="terms" value="terms">
                                I agree to the Terms & Conditions
                            </label>
                        </div>
                        <div class="form-btn">
                            <button>SEND ME A REMINDER</button>
                        </div>
                    </form>
                </div>
            </div>
        </div>
    </section>
</template>

<style scoped>
.con-container {
    width: 80%;
    /* height: 100vh; */
    margin: 30px auto;
    display: flex;
    flex-direction: row;
    align-items: start;
    justify-content: center;
}

.con-img {
    width: 50%;
    /* height: 300px; */
}

.con-img img {
    width: 80%;
    height: 450px;
    margin-top: 20px;
    border: none;
    border-radius: 20px 0 20px 0;
}

.con-words {
    width: 50%;
}

.con-theword {
    margin: 20px 0 30px 0;
}

.con-theword h1 {
    font-size: 46px;
}

.con-theword p {
    font-size: 20px;
}

input[type="text"] {
    width: 300px;
    padding: 12px 20px;
    margin: 8px 0;
    display: inline-block;
    border: 1px solid #ccc;
    border-radius: 4px;
}

input[type="email"] {
    width: 300px;
    padding: 12px 20px;
    margin: 8px 0;
    display: inline-block;
    border: 1px solid #ccc;
    border-radius: 4px;
}

input[type=checkbox]+label {
    display: block;
}

/* input[type=checkbox] {
  display: none;
} */

input[type=checkbox]+label:before {
    content: "\2714";
    border: 0.1em solid #000;
    border-radius: 0.2em;
    display: inline-block;
    width: 1em;
    height: 1em;
    padding-left: 0.2em;
    padding-bottom: 0.3em;
    vertical-align: middle;
    position: relative;
    bottom: 1px;
}

label {
    display: block;
}

.form-checkbox {
    display: flex;
    flex-direction: column;

}
</style>