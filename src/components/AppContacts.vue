<script>
export default {
    name: "AppContacts"
}
</script>

<template>
    <section class="ms_contacts py-5">
        <div class="ms_container">
            <div class="row align-items-center">
                <div class="col-8 pe-5">
                    <div class="col-6">
                        <div class="ms_heading">
                            <h4 class="pt-5">send a message</h4>
                            <h2 class="py-4">Get in Touch</h2>
                            <p class="pb-4">Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                        </div>
                    </div>
                    <div class="ms_form-contacts">
                        <div class="row g-3">
                            <div class="col-md">
                                <div class="form-floating">
                                    <input type="name" class="form-control" id="floatingNameForm" placeholder="name@example.com">
                                    <label for="floatingNameForm">Name</label>
                                </div>
                            </div>
                            <div class="col-md">
                                <div class="form-floating">
                                    <input type="email" class="form-control" id="floatingEmailForm" placeholder="name@example.com">
                                    <label for="floatingEmailForm">Email address</label>
                                </div>
                            </div>
                        </div>
                        <div class="row g-3 py-3">
                            <div class="col-md">
                                <div class="form-floating">
                                    <input type="number" class="form-control" id="floatingNumberForm" placeholder="321 4567890" >
                                    <label for="floatingNumberForm">Phone</label>
                                </div>
                            </div>
                            <div class="col-md">
                                <div class="form-floating">
                                    <select class="form-select" id="floatingSelectForm">
                                        <option selected></option>
                                        <option value="1">One</option>
                                        <option value="2">Two</option>
                                        <option value="3">Three</option>
                                    </select>
                                    <label for="floatingSelectForm">More Info</label>
                                </div>
                            </div>
                        </div>
                            
                        <div class="form-floating">
                            <textarea class="form-control" placeholder="Leave a comment here" id="floatingTextarea2" style="height: 100px"></textarea>
                            <label for="floatingTextarea2">Comments</label>
                        </div>
                        <div class="col-12">
                            <button type="submit" class="ms_btn ms_main-btn my-3">Send</button>
                        </div>
                    </div>
                </div>
                <div class="col-4 ps-3">
                    <div class="ms_right-col">
                        <h3 class="py-3">Example Inc.</h3>
                        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                        <div class="ms_icons-contacts">
                            <div class="row">
                                <div class="col-3">
                                    <i class="fa-solid fa-phone p-3 my-2"></i>
                                    <i class="fa-solid fa-envelope p-3 my-2"></i>
                                    <i class="fa-solid fa-location-dot p-3 my-2"></i>
                                </div>
                                <div class="col-9 d-flex flex-column justify-content-around">
                                    <span>+ 1 (350) 1234-5678</span>
                                    <span>hello@example.com</span>
                                    <span>Main Avenue,987</span>
                                </div>
                            </div>
                        </div>
                        <button class="ms_btn ms_outline-btn mt-3">view map</button>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<style lang="scss" scoped>
@use "../styles/partials/variables" as *;
.ms_contacts {
    width: 100%;
    .ms_form-contacts {
        input,
        select,
        textarea {
            background-color: #ececec;
            border: none;
        }
        label {
            color: $secondary-text;
        }
        textarea {
            min-height: 150px;
        }
    }
    .ms_right-col {
        p {
            color: $secondary-text;
        }
        .ms_icons-contacts {
            i {
                color: $color-main;
                font-size: 22px;
                background-color: rgba($color: $color-main, $alpha: 0.2);
                border-radius: 50%;
            }
            span {
                color: $color-main;
            }
        }
        .ms_outline-btn {
            color: $color-main;
        }
    }
}
</style>