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
                        <h4 class="pt-5">newsletter</h4>
                        <h2 class="py-4"><span>Know</span> First</h2>
                        <p class="pb-4">Lorem ipsum dolor sit amet consectetur adipisicing elit. Sit totam dolore neque?</p>
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
@use "../styles/partials/variables" as *;
.ms_newsletter {
    width: 100%;
    height: 400px;
    background-image: url("../assets/images/bg-1.jpg");
    background-size: cover;
    background-position: center;

    .ms_small-container {
        width: 50%;
        margin: 0 auto;
        .ms_heading {
            color: white;
            span {
                padding: 0 15px;
                background-color: rgba($color: $color-main, $alpha: 0.2);
                border-radius: 8px;
            }
        }
        input {
            opacity: 0.5;
            border: none;
        }
        label {
            color: $secondary-text;
        }
    }
}
</style>