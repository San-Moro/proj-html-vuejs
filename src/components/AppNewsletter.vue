<script>
export default {
    name: "AppNewsletter"
}
</script>

<template>
    <section class="ms_newsletter d-flex align-items-center">
        <div class="ms_small-container">
            <div class="row align-items-center">
                <div class="col-6">
                    <div class="ms_heading">
                        <h4>about the network</h4>
                        <h2>The Company</h2>
                        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Consequatur a repellat quaerat asperiores minus totam beatae.</p>
                    </div>
                </div>
                <div class="col-6">
                    <div class="form-floating mb-3">
                        <input type="name" class="form-control" id="floatingName" placeholder="Name">
                        <label for="floatingName">Name</label>
                    </div>
                    <div class="form-floating">
                        <input type="email" class="form-control" id="floatingEmail" placeholder="name@example.com">
                        <label for="floatingEmail">Email</label>
                    </div>
                    <div class="col-12">
                        <button type="submit" class="ms_btn ms_main-btn my-3">Subscribe</button>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<style lang="scss" scoped>
.ms_newsletter {
    width: 100%;
    height: 400px;
    background-image: url("../assets/images/bg-1.jpg");
    background-size: cover;
    background-position: center;

    .ms_small-container {
        width: 60%;
        margin: 0 auto;
        .ms_heading {
            color: white;

        }
    }
}
</style>