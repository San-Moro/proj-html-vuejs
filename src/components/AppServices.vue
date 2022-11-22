<script>
export default {
    name: "AppServices"
}
</script>

<template>
    <section class="ms_services py-5">
        <div class="ms_container">
            <div class="ms_text-services">
                <div class="ms_heading">
                    <h4 class="pt-5">our business areas</h4>
                    <h2 class="py-4">Excellence in Services</h2>
                    <p class="pb-4">Lorem ipsum dolor sit amet consectetur adipisicing elit. Consequatur a repellat quaerat asperiores minus totam beatae. Lorem ipsum dolor sit amet.</p>
                </div>
                <div class="ms_card-services d-flex flex-column">
                    <div class="row row-cols-3 g-4">
                        <div class="col">
                            <div class="ms_card-dark p-5">
                                <i class="fa-solid fa-diagram-project pb-3"></i>
                                <h3 class="py-3">Audit & assurance</h3>
                                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                                <button class="ms_btn ms_outline-btn mt-3">read more</button>
                            </div>
                        </div>
                        <div class="col">
                            <div class="ms_card-dark p-5">
                                <i class="fa-solid fa-briefcase pb-3"></i>
                                <h3 class="py-3">Finalcial Advisor</h3>
                                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                                <button class="ms_btn ms_outline-btn mt-3">read more</button>
                            </div>
                        </div>
                        <div class="col">
                            <div class="ms_card-dark p-5">
                                <i class="fa-solid fa-chart-simple pb-3"></i>
                                <h3 class="py-3">Analytics</h3>
                                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                                <button class="ms_btn ms_outline-btn mt-3">read more</button>
                            </div>
                        </div>
                        <div class="col">
                            <div class="ms_card-dark p-5">
                                <i class="fa-solid fa-plane pb-3"></i>
                                <h3 class="py-3">Middle Marketing</h3>
                                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                                <button class="ms_btn ms_outline-btn mt-3">read more</button>
                            </div>
                        </div>
                        <div class="col">
                            <div class="ms_card-dark p-5">
                                <i class="fa-solid fa-scale-balanced pb-3"></i>
                                <h3 class="py-3">Legal Consulting</h3>
                                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                                <button class="ms_btn ms_outline-btn mt-3">read more</button>
                            </div>
                        </div>
                        <div class="col">
                            <div class="ms_card-dark p-5">
                                <i class="fa-regular fa-folder-open pb-3"></i>
                                <h3 class="py-3">Regulatory Risk</h3>
                                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                                <button class="ms_btn ms_outline-btn mt-3">read more</button>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<style lang="scss" scoped>
@use "../styles/partials/variables" as *;
.ms_services {
    width: 100%;
    color: white;
    background-color: $dark-bg;
    .ms-heading {
        width: 80%;
    }
    .ms_card-dark {
        background-color: #19191f;
        border-radius: 8px;
        i {
            color: $color-main;
            font-size: 32px;
        }
        p {
            color: $secondary-text;
        }
        
        &:hover {
            transform: translateY(-15px);
        }
    }
}
</style>