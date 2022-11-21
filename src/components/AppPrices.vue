<script>
export default {
    name: "AppPrices"
}
</script>

<template>
    <section class="ms_prices py-5">
        <div class="ms_container">
            <div class="ms_heading">
                <h4 class="pt-5">Monthly plans</h4>
                <h2 class="py-4">Pricing Table</h2>
                <p class="pb-4">Lorem ipsum dolor sit amet consectetur adipisicing elit. Consequatur a repellat quaerat asperiores minus totam beatae.</p>
                <div class="ms_card-prices d-flex flex-column">
                    <div class="row row-cols-3">
                        <div class="col">
                            <div class="ms_card p-5">
                                <i class="fa-solid fa-rocket p-2"></i>
                                <h3 class="py-3">Standard</h3>
                                <p><span>$</span> 490 <span><small>/mo</small></span></p>
                                <ul>
                                    <li class="d-flex justify-content-between">
                                        Standard Accounting
                                         <i class="fa-solid fa-check"></i>
                                    </li>
                                    <li class="d-flex justify-content-between">
                                        Platform Access
                                         <i class="fa-solid fa-check"></i>
                                    </li>
                                    <li class="d-flex justify-content-between">
                                        Business Orientation
                                         <i class="fa-solid fa-xmark"></i>
                                    </li>
                                    <li class="d-flex justify-content-between">
                                        Dedicated Consultant
                                         <i class="fa-solid fa-xmark"></i>
                                    </li>
                                    <li class="d-flex justify-content-between">
                                        Personal Assistance
                                         <i class="fa-solid fa-xmark"></i>
                                    </li>
                                </ul>
                            </div>
                        </div>
                        <div class="col">
                            <div class="ms_card ms_card-popular p-5">
                                <i class="fa-solid fa-briefcase p-2"></i>
                                <h3 class="py-3">Professional</h3>
                                <p><span>$</span> 890 <span><small>/mo</small></span></p>
                                <ul>
                                    <li class="d-flex justify-content-between">
                                        Standard Accounting
                                         <i class="fa-solid fa-check"></i>
                                    </li>
                                    <li class="d-flex justify-content-between">
                                        Platform Access
                                         <i class="fa-solid fa-check"></i>
                                    </li>
                                    <li class="d-flex justify-content-between">
                                        Business Orientation
                                         <i class="fa-solid fa-xmark"></i>
                                    </li>
                                    <li class="d-flex justify-content-between">
                                        Dedicated Consultant
                                         <i class="fa-solid fa-xmark"></i>
                                    </li>
                                    <li class="d-flex justify-content-between">
                                        Personal Assistance
                                         <i class="fa-solid fa-xmark"></i>
                                    </li>
                                </ul>
                            </div>
                        </div>
                        <div class="col">
                            <div class="ms_card p-5">
                                <i class="fa-regular fa-gem p-2"></i>
                                <h3 class="py-3">Ultimate</h3>
                                <p><span>$</span> 1390 <span><small>/mo</small></span></p>
                                <ul>
                                    <li class="d-flex justify-content-between">
                                        Standard Accounting
                                         <i class="fa-solid fa-check"></i>
                                    </li>
                                    <li class="d-flex justify-content-between">
                                        Platform Access
                                         <i class="fa-solid fa-check"></i>
                                    </li>
                                    <li class="d-flex justify-content-between">
                                        Business Orientation
                                         <i class="fa-solid fa-xmark"></i>
                                    </li>
                                    <li class="d-flex justify-content-between">
                                        Dedicated Consultant
                                         <i class="fa-solid fa-xmark"></i>
                                    </li>
                                    <li class="d-flex justify-content-between">
                                        Personal Assistance
                                         <i class="fa-solid fa-xmark"></i>
                                    </li>
                                </ul>
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
.ms_prices {
    width: 100%;
    background-color: $light-bg;
    .ms_heading {
        text-align: center;
        .ms_card {
            background-color: white;
            border-radius: 10px;
            i {
                color: $color-main;
                font-size: 40px;
            }
            p {
                color: $color-main;
                font-size: 35px;
                font-weight: 600;
                span {
                    font-weight: 400;
                    font-size: 20px;
                }
            }
            ul {
                text-align: start;
                padding-left: 0;
                li {
                    color: $secondary-text;
                    padding: 8px 0;
                    i {
                        color: $color-main;
                        font-size: 18px;
                        font-weight: 900;
                    }
                }
            }
        }
        .ms_card-popular {
            transform: scale(1.05);
            margin: 0 10px;
        }
    }
}
</style>