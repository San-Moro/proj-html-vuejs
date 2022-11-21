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
                        <div class="card-img-overlay p-5 text-center d-flex align-items-end ms_card-blog">
                            <!-- <p class="card-text"><small>Last updated 3 mins ago</small></p> -->
                            <h4 class="card-title">Card title Lorem ipsum dolor sit adipisicing.</h4>
                            <!-- <p class="card-text">This is a wider card with supporting text.</p> -->
                        </div>
                    </div>
                </div>
                <div class="col">
                    <div class="card text-bg-dark">
                        <img src="../assets/images/news-2.jpg" class="card-img" alt="...">
                        <div class="card-img-overlay p-5 text-center d-flex align-items-end ms_card-blog">
                            <!-- <p class="card-text"><small>Last updated 3 mins ago</small></p> -->
                            <h4 class="card-title">Card title Lorem ipsum dolor sit adipisicing.</h4>
                            <!-- <p class="card-text">This is a wider card with supporting text.</p> -->
                        </div>
                    </div>
                </div>
                <div class="col">
                    <div class="card text-bg-dark">
                        <img src="../assets/images/news-3.jpg" class="card-img" alt="...">
                        <div class="card-img-overlay p-5 text-center d-flex align-items-end ms_card-blog">
                            <!-- <p class="card-text"><small>Last updated 3 mins ago</small></p> -->
                            <h4 class="card-title">Card title Lorem ipsum dolor sit adipisicing.</h4>
                            <!-- <p class="card-text">This is a wider card with supporting text.</p> -->
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
}
</style>