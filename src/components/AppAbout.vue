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
                        <h2 class="py-4"><span>The</span> Company</h2>
                        <p class="pb-4">Lorem ipsum dolor sit amet consectetur adipisicing elit. Consequatur a repellat quaerat asperiores minus totam beatae.</p>
                    </div>
                    <div class="ms_card-about d-flex flex-column mt-5">
                        <div class="row row-cols-2 pb-4">
                            <div class="col">
                                <h3><span><i class="fa-solid fa-award"></i></span> Tradition</h3>
                                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                            </div>
                            <div class="col">
                                <h3><span><i class="fa-solid fa-lock"></i></span> Security</h3>
                                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                            </div>
                        </div>
                        <div class="row row-cols-2">
                            <div class="col">
                                <h3><span><i class="fa-solid fa-pen-to-square"></i></span> Certificate</h3>
                                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                            </div>
                            <div class="col">
                                <h3><span><i class="fa-solid fa-graduation-cap"></i></span>Expertise </h3>
                                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            <div class="col ms_col-right-images">
                <div class="ms_detail-img">
                    <img class="ms_detail-top" src="../assets/images/detail.png" alt="">
                    <!-- <img class="ms_detail-bottom" src="../assets/images/detail.png" alt=""> -->
                </div>
                <img src="../assets/images/about-3.jpg" alt="">
            </div>
        </div>
    </section>
</template>

<style lang="scss" scoped>
@use "../styles/partials/variables" as *;
.ms_about {
    width: 100%;
    .ms_text-about {
        width: 60%;
        h2 {
            color: $title-section;
            span {
                color: $color-main;
                padding: 0 15px;
                background-color: rgba($color: $color-main, $alpha: 0.2);
                border-radius: 8px;
            }
        }
        h4 {
            font-size: 16px;
            font-weight: 600;
            color: $color-main;
            text-transform: uppercase;
        }
        p {
            color: $secondary-text;
        }
        .ms_card-about {
            h3 {
                padding-bottom: 15px;
            }
            span {
                font-size: 20px;
                color: $color-main;
                padding-right: 8px;
            }
        }
    }
    .ms_col-right-images {
        .ms_detail-img {
            position: relative;
            img.ms_detail-top {
                width: 150px;
                opacity: 0.5;
                position: absolute;
                transform: translate(-50%, -50%);

            }
        }
        
    }

}    
</style>