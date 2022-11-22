<script>
export default {
    name: "AppBanner",
    data() {
        return {
            links: [
                {
                    title: "home",
                    href: ""
                },
                {
                    title: "about",
                    href: ""
                },
                {
                    title: "services",
                    href: ""
                },
                {
                    title: "pricing",
                    href: ""
                },
                {
                    title: "blog",
                    href: ""
                }
            ],
        }
    }
}
</script>

<template>
    <div class="ms_wrapper">
        <img src="../assets/images/hero-image-bg.png" alt="banner background" class="ms_wrapper-bg" />

        <section class="ms_banner">

            <div class="ms_header-banner d-flex align-items-center">
                <div class="ms_container">
                    <div class="row">
                        <div class="col-4 d-flex flex-row align-items-center">
                            <i class="fa-solid fa-clock"></i>
                            <span>Open Hours: Mon-Sat - 9:00-18:00</span>
                        </div>
                        <div class="col-8 d-flex justify-content-end align-items-center">
                            <i class="fa-solid fa-phone"></i>
                            <span><a href="">+1 (305) 1234-5678</a></span>
                            <i class="fa-solid fa-envelope ps-3"></i>
                            <span><a href="">hello@example.com</a></span>
                            <a href=""><i class="fa-brands fa-facebook-f ps-3"></i></a>
                            <a href=""><i class="fa-brands fa-twitter px-4"></i></a>
                            <a href=""><i class="fa-brands fa-linkedin-in"></i></a>
                        </div>
                    </div>
                </div>
            </div>

            <div class="ms_container">
                <div class="row  d-flex align-items-center">
                    <div class="col-2">
                        <div class="ms_logo">
                            <a href=""><img src="../assets/images/logo-main.png" alt=""></a>
                        </div>
                    </div>
                    <div class="col-10 d-flex justify-content-end">
                        <nav class="d-flex py-3">
                            <div class="ms_main-menu d-flex">
                                <ul class="d-flex flex-row align-items-center">
                                    <li v-for="(link,index) in links" :key="index">
                                        <a href=""> {{link.title}}</a>
                                    </li>
                                </ul>
                                <div class="ms_button">
                                    <button class="ms_btn ms_main-btn">get in touch</button>
                                </div>
                            </div>
                        </nav>
                    </div>
                </div>
            </div>

            <div class="ms_banner-cta d-flex flex-column justify-content-center align-items-center">
                <h1>Lead - Customer</h1>
                <p class="py-3">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Dignissimos cupiditate consequatur consectetur. Doloribus possimus temporibus dolor saepe molestias!</p>
                <div class="ms_button">
                    <button class="ms_btn ms_main-btn mx-3">get in touch</button>
                    <button class="ms_btn ms_outline-btn mx-3">read more</button>
                </div>
            </div>
        </section>

    </div>
</template>

<style lang="scss" scoped>
@use "../styles/partials/variables" as *;
.ms_wrapper {
    background-color: black;
    height: 800px;
    
    img.ms_wrapper-bg {
        width: 100%;
        height: inherit;
        opacity: 0.3;
        position: absolute;
        left: 0;
        top: 0;
    }
    .ms_banner {
        width: 100%;
        position: relative;

        .ms_header-banner {
            width: 100%;
            height: 50px;
            background-color: #21333e;
            color: $text-dark-bg;
            span {
                font-size: 14px;
                font-weight: 300;
                padding: 0 10px;
            }
            a {
                color: $text-dark-bg;
            }
        }
        .ms_logo {
            img {
                height: 50px;
            }
        }

        nav {
            .ms_main-menu {
                ul {
                    line-height: 50px;
                    margin-bottom: 0;
                }
                a {
                    text-transform: uppercase;
                    color: white;
                    padding: 0 15px;
                }
            }
        }

        .ms_banner-cta {
            width: 50%;
            height: 600px;
            margin: 0 auto;
            color: white;
            text-align: center;
            h1 {
                font-size: 60px;
                font-weight: 900;
            }
            p {
                color: #c0c3d0;
            }
        }
    }

}
</style>
