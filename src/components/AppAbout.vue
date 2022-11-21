<script>
export default {
    name: "AppAbout"
}
</script>

<template>
    <section class="ms_about d-flex">
        <div class="row row-cols-2">
            <div class="col d-flex flex-column align-items-end justify-content-center">

                <div class="ms_text-about">
                    <div class="ms_heading">
                        <h4>about the network</h4>
                        <h2>The Company</h2>
                        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Consequatur a repellat quaerat asperiores minus totam beatae.</p>
                    </div>
                    <div class="ms_card-about d-flex flex-column">
                        <div class="row row-cols-2">
                            <div class="col">
                                <h3>Tradition</h3>
                                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                            </div>
                            <div class="col">
                                <h3>Tradition</h3>
                                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                            </div>
                        </div>
                        <div class="row row-cols-2">
                            <div class="col">
                                <h3>Tradition</h3>
                                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                            </div>
                            <div class="col">
                                <h3>Tradition</h3>
                                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            <div class="col">
                <img src="../assets/images/about-3.jpg" alt="">
            </div>
        </div>
    </section>
</template>

<style lang="scss" scoped>
.ms_about {
    width: 100%;
    .ms_text-about {
        width: 70%;
    }

}    
</style>