<script>

export default {
    name: "AppStrengths"
}
</script>

<template>
    <section class="ms_strengths d-flex align-items-center">
        <div class="ms_container">
            <div class="row row-cols-3">
                <div class="col">
                    <div class="ms_card-strengths p-5">
                        <i class="fa-solid fa-user-group p-3"></i>
                        <h3 class="py-3">Human Capital</h3>
                        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptates, eos. Laborum, nemo? Odio!</p>
                    </div>
                </div>
                <div class="col">
                    <div class="ms_card-strengths p-5">
                        <i class="fa-solid fa-chart-pie p-3"></i>
                        <h3 class="py-3">Core Business</h3>
                        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptates, eos. Laborum, nemo? Odio!</p>
                    </div>
                </div>
                <div class="col">
                    <div class="ms_card-strengths p-5">
                        <i class="fa-solid fa-gauge-high p-3"></i>
                        <h3 class="py-3">Performance</h3>
                        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptates, eos. Laborum, nemo? Odio!</p>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<style lang="scss" scoped>
@use "../styles/partials/variables" as *;
.ms_strengths {
    width: 100%;
    height: 500px;
    background-color: $light-bg;
    .ms_card-strengths {

        background-color: white;
        border-radius: 8px;
        i {
            color: $color-main;
            font-size: 22px;
            background-color: rgba($color: $color-main, $alpha: 0.2);
            border-radius: 50%;
        }
        h3 {
            color: $title-section;
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