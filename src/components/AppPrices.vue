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
                <h2 class="py-4"><span>Pricing</span> Table</h2>
                <p class="pb-4">Lorem ipsum dolor sit amet consectetur adipisicing elit. Consequatur a repellat quaerat asperiores minus totam beatae.</p>
            </div>
            <div class="ms_card-prices d-flex flex-column">
                <div class="row row-cols-3">
                    <div class="col">
                        <div class="ms_card p-5 text-center">
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
                        <div class="ms_card ms_card-popular pt-3">
                            <div class="ms_label-card-popular py-1">
                                <p>Most polular</p>
                            </div>
                            <div class="text-center ps-5 pb-5 pe-5">
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
                    </div>
                    <div class="col">
                        <div class="ms_card p-5 text-center">
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
    </section>
</template>

<style lang="scss" scoped>
@use "../styles/partials/variables" as *;
.ms_prices {
    width: 100%;
    background-color: $light-bg;
    .ms_heading {
        text-align: center;

        :nth-child(2) {
            color: $title-section;
            span {
                color: $color-main;
                padding: 0 15px;
                background-color: rgba($color: $color-main, $alpha: 0.2);
                border-radius: 8px;
            }
        }
    }
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
        &:hover {
            transform: scale(0.95)
        }
    }
    .ms_card-popular {
        transform: scale(1.05);
        margin: 0 10px;
        .ms_label-card-popular {
            width: 80px;
            background-color: $label-card-bg;
            border-radius: 0 40px 40px 0;
            p {
                font-size: 14px;
                line-height: 16px;
                font-weight: 400;
                color: white;
                margin-bottom: 0;
                padding-left: 10px;
            }
        }

    }

}
</style>