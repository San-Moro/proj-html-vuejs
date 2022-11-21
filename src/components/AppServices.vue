<script>
export default {
    name: "AppServices"
}
</script>

<template>
    <section class="ms_services py-5">
        <div class="ms_container">
            <div class="ms_text-services">
                    <div class="ms-heading">
                        <h4>about the network</h4>
                        <h2>The Company</h2>
                        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Consequatur a repellat quaerat asperiores minus totam beatae.</p>
                    </div>
                    <div class="ms_card-services d-flex flex-column">
                        <div class="row row-cols-3 g-4">
                            <div class="col">
                                <div class="ms_card-dark p-5">
                                    <i class="fa-solid fa-user-group p-3"></i>
                                    <h3 class="py-3">Human Capital</h3>
                                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                                </div>
                            </div>
                            <div class="col">
                                <div class="ms_card-dark p-5">
                                    <i class="fa-solid fa-user-group p-3"></i>
                                    <h3 class="py-3">Human Capital</h3>
                                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                                </div>
                            </div>
                            <div class="col">
                                <div class="ms_card-dark p-5">
                                    <i class="fa-solid fa-user-group p-3"></i>
                                    <h3 class="py-3">Human Capital</h3>
                                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                                </div>
                            </div>
                            <div class="col">
                                <div class="ms_card-dark p-5">
                                    <i class="fa-solid fa-user-group p-3"></i>
                                    <h3 class="py-3">Human Capital</h3>
                                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                                </div>
                            </div>
                            <div class="col">
                                <div class="ms_card-dark p-5">
                                    <i class="fa-solid fa-user-group p-3"></i>
                                    <h3 class="py-3">Human Capital</h3>
                                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                                </div>
                            </div>
                            <div class="col">
                                <div class="ms_card-dark p-5">
                                    <i class="fa-solid fa-user-group p-3"></i>
                                    <h3 class="py-3">Human Capital</h3>
                                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
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
    .ms_card-dark {
        background-color: #19191f;
    }
}
</style>