<script>
export default {
    name: "AppPrices"
}
</script>

<template>
    <section class="ms_prices py-5">
        <div class="ms_container">
            <div class="ms_heading">
                <h4>about the network</h4>
                <h2>The Company</h2>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Consequatur a repellat quaerat asperiores minus totam beatae.</p>
                <div class="ms_card-prices d-flex flex-column">
                    <div class="row row-cols-3">
                        <div class="col">
                            <div class="ms_card p-5">
                                <i class="fa-solid fa-user-group p-3"></i>
                                <h3 class="py-3">Standard</h3>
                                <p>$ 490/ mo</p>
                                <ul>
                                    <li class="d-flex justify-content-between">
                                        Standard
                                         <span>&check;</span>
                                    </li>
                                    <li class="d-flex justify-content-between">
                                        Standard
                                         <span>&check;</span>
                                    </li>
                                    <li class="d-flex justify-content-between">
                                        Standard
                                         <span>&cross;</span>
                                    </li>
                                    <li class="d-flex justify-content-between">
                                        Standard
                                         <span>&cross;</span>
                                    </li>
                                    <li class="d-flex justify-content-between">
                                        Standard
                                         <span>&cross;</span>
                                    </li>
                                    <li class="d-flex justify-content-between">
                                        Standard
                                         <span>&cross;</span>
                                    </li>
                                </ul>
                            </div>
                        </div>
                        <div class="col">
                            <div class="ms_card p-5">
                                <i class="fa-solid fa-user-group p-3"></i>
                                <h3 class="py-3">Standard</h3>
                                <p>$ 490/ mo</p>
                                <ul>
                                    <li class="d-flex justify-content-between">
                                        Standard
                                         <span>&check;</span>
                                    </li>
                                    <li class="d-flex justify-content-between">
                                        Standard
                                         <span>&check;</span>
                                    </li>
                                    <li class="d-flex justify-content-between">
                                        Standard
                                         <span>&cross;</span>
                                    </li>
                                    <li class="d-flex justify-content-between">
                                        Standard
                                         <span>&cross;</span>
                                    </li>
                                    <li class="d-flex justify-content-between">
                                        Standard
                                         <span>&cross;</span>
                                    </li>
                                    <li class="d-flex justify-content-between">
                                        Standard
                                         <span>&cross;</span>
                                    </li>
                                </ul>
                            </div>
                        </div>
                        <div class="col">
                            <div class="ms_card p-5">
                                <i class="fa-solid fa-user-group p-3"></i>
                                <h3 class="py-3">Standard</h3>
                                <p>$ 490/ mo</p>
                                <ul>
                                    <li class="d-flex justify-content-between">
                                        Standard
                                         <span>&check;</span>
                                    </li>
                                    <li class="d-flex justify-content-between">
                                        Standard
                                         <span>&check;</span>
                                    </li>
                                    <li class="d-flex justify-content-between">
                                        Standard
                                         <span>&cross;</span>
                                    </li>
                                    <li class="d-flex justify-content-between">
                                        Standard
                                         <span>&cross;</span>
                                    </li>
                                    <li class="d-flex justify-content-between">
                                        Standard
                                         <span>&cross;</span>
                                    </li>
                                    <li class="d-flex justify-content-between">
                                        Standard
                                         <span>&cross;</span>
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
            ul {
                text-align: start;
            }
        }
    }
}
</style>