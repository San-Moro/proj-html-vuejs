<script>
export default {
    name: "AppFooter",
    data() {
        return {
            navAbout: [
                {
                    title: "The Company",
                    href: ""
                },
                {
                    title: "Institutional",
                    href: ""
                },
                {
                    title: "Social & Events",
                    href: ""
                },
                {
                    title: "Innovation",
                    href: ""
                },
                {
                    title: "Environment",
                    href: ""
                },
                {
                    title: "Technology",
                    href: ""
                }
            ],
            navServices: [
                {
                    title: "Audit & assurance",
                    href: ""
                },
                {
                    title: "Finalcial Advisor",
                    href: ""
                },
                {
                    title: "Analytics",
                    href: ""
                },
                {
                    title: "Middle Marketing",
                    href: ""
                },
                {
                    title: "Legal Consulting",
                    href: ""
                },
                {
                    title: "Regulatory Risk",
                    href: ""
                }
            ],
            navSupport: [
                {
                    title: "Responsibility",
                    href: ""
                },
                {
                    title: "Term of Use",
                    href: ""
                },
                {
                    title: "About Cookies",
                    href: ""
                },
                {
                    title: "Privacy Policy",
                    href: ""
                },
                {
                    title: "Accesibility",
                    href: ""
                },
                {
                    title: "Information",
                    href: ""
                }
            ]
        }
    }
}
</script>

<template>
    <section class="ms_footer">
        <div class="ms_footer-top py-5">
            <div class="ms_container py-5">
                <div class="row row-cols-4">

                    <div class="col">
                        <div class="ms_contacts-footer">
                            <img src="../assets/images/logo-main.png" alt="">
                            <p class="pb-2">Lorem ipsum, dolor sit amet consectetur adipisicing elit.</p>
                            <div class="ms_icons-contacts">
                                <div class="row pb-2">
                                    <div class="col-2 d-flex flex-column">
                                        <i class="fa-solid fa-phone my-2"></i>
                                        <i class="fa-solid fa-envelope my-2"></i>
                                        <i class="fa-solid fa-location-dot my-2"></i>
                                    </div>
                                    <div class="col-10 d-flex flex-column justify-content-around">
                                        <span>+ 1 (350) 1234-5678</span>
                                        <span>hello@example.com</span>
                                        <span>Main Avenue,987</span>
                                    </div>
                                </div>
                            </div>
                            <button class="ms_btn ms_outline-btn mt-3">get in touch</button>
                        </div>
                    </div>

                    <div class="col">
                        <nav class="py-5 ps-5 pe-2">
                            <ul> About
                                <li v-for="(linkAbout,index) in navAbout" :key="index">
                                    <span><i class="fa-solid fa-chevron-right"></i></span><a href="">{{linkAbout.title}}</a>
                                </li>
                            </ul>
                        </nav>
                    </div>
                    <div class="col">
                        <nav class="py-5 ps-5 pe-2">
                            <ul> Services
                                <li v-for="(linkServices,index) in navServices" :key="index">
                                    <span><i class="fa-solid fa-chevron-right"></i></span><a href="">{{linkServices.title}}</a>
                                </li>
                            </ul>
                        </nav>
                    </div>
                    <div class="col">
                        <nav class="py-5 ps-5 pe-2">
                            <ul> Support
                                <li v-for="(linkSupport,index) in navSupport" :key="index">
                                    <span><i class="fa-solid fa-chevron-right"></i></span><a href="">{{linkSupport.title}}</a>
                                </li>
                            </ul>
                        </nav>
                    </div>
                </div>
            </div>
        </div>
        <div class="ms_footer-bottom d-flex">
            <div class="ms_container d-flex justify-content-between align-items-center">
                <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit.</p>
                <p><i class="fa-regular fa-copyright"></i>2020 NEXGEN is Lorem Ipsum by</p>
            </div>
            <div class="ms_icon-go-back-up d-flex justify-content-end align-items-center">
                <i class="fa-solid fa-arrow-up p-2 me-3"></i>
            </div>
        </div>
    </section>
</template>

<style lang="scss" scoped>
@use "../styles/partials/variables" as *;
.ms_footer {
    width: 100%;
    min-height: 400px;
    .ms_footer-top {
        background-color: $dark-bg;
        .ms_contacts-footer {
            font-size: 14px;
            color: $text-dark-bg;

            img {
                width: 150px;
                padding-bottom: 15px;
            }
            button {
                font-size: 15px;
            }
            .ms_icons-contacts {
                .col-10 {
                    padding-left: 0;
                }
            }
        }
        nav {
            background-color: #19191f;
            border-radius: 8px;
            ul {
                font-size: 20px;
                font-weight: 600;
                color: white;
                padding-left: 0;
                li {
                    a {
                        font-size: 14px;
                        font-weight: 400;
                        color: $text-dark-bg;
                    }
                    i {
                        font-size: 14px;
                        padding-right: 10px;
                    }
                }
            }
        }
    }
    .ms_footer-bottom {
        background-color: #0d0d11;
        height: 80px;
        font-size: 12px;
        color: $text-dark-bg;
        p {
            margin-bottom: 0;
        }
        .ms_icon-go-back-up {
            i {
                font-size: 20px;
                color: #0d0d11;
                background-color: rgba($color: $secondary-text, $alpha: 0.3);
                border-radius: 50%;
            }
        }
    }
}
</style>