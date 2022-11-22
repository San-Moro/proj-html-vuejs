<script>
export default {
    name: "AppBlog"
}
</script>

<template>
    <section class="ms_blog py-5">
        <div class="ms_container">
            <div class="ms_heading">
                <h4 class="pt-5">our editorial content</h4>
                <h2 class="py-4">Latest News</h2>
                <p class="pb-4">Lorem ipsum dolor sit amet consectetur adipisicing elit asperiores minus totam.</p>
            </div>
            <div class="row row-cols-3 pb-5">
                <div class="col">
                    <div class="card text-bg-dark">
                        <img src="../assets/images/news-1.jpg" class="card-img" alt="...">
                        <div class="card-img-overlay p-5 text-center d-flex flex-column justify-content-end ms_card-blog">
                            <p class="card-text pb-5">
                                <small><i class="fa-regular fa-user pe-1"></i>Andrea Miller <i class="fa-regular fa-clock ps-3 pe-1"></i> 2 mins ago</small>
                            </p>
                            <h4 class="card-title py-3 pt-5">Card title Lorem ipsum dolor sit adipisicing.</h4>
                            <p class="card-text">This is a wider card with supporting text.</p>
                        </div>
                    </div>
                </div>
                <div class="col">
                    <div class="card text-bg-dark">
                        <img src="../assets/images/news-2.jpg" class="card-img" alt="...">
                        <div class="card-img-overlay p-5 text-center d-flex flex-column justify-content-end ms_card-blog">
                            <p class="card-text pb-5">
                                <small><i class="fa-regular fa-user pe-1"></i>Andrea Miller <i class="fa-regular fa-clock ps-3 pe-1"></i> 2 mins ago</small>
                            </p>
                            <h4 class="card-title py-3 pt-5">Card title Lorem ipsum dolor sit adipisicing.</h4>
                            <p class="card-text">This is a wider card with supporting text.</p>
                        </div>
                    </div>
                </div>
                <div class="col">
                    <div class="card text-bg-dark">
                        <img src="../assets/images/news-3.jpg" class="card-img" alt="...">
                        <div class="card-img-overlay p-5 text-center d-flex flex-column justify-content-end ms_card-blog">
                            <p class="card-text pb-5">
                                <small><i class="fa-regular fa-user pe-1"></i>Andrea Miller <i class="fa-regular fa-clock ps-3 pe-1"></i> 2 mins ago</small>
                            </p>
                            <h4 class="card-title py-3 pt-5">Card title Lorem ipsum dolor sit adipisicing.</h4>
                            <p class="card-text">This is a wider card with supporting text.</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<style lang="scss" scoped>
.ms_blog {
    width: 100%;
    img {
        opacity: 0.4;
    }
    .card {
        border: none;
        .ms_card-blog {
            h4 {
                font-weight: 600;
                margin-bottom: 0;
            }
            p {
                display: none;
            }
            &:hover p {
                display: block;
            }
        }
    }
}
</style>