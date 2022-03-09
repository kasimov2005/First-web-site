
#html 
<!DOCTYPE html>
<html>
    <head>
        <title>Portfolio</title>
        <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.2/css/all.min.css" integrity="sha512-HK5fgLBL+xu6dm/Ii3z4xhlSUyZgTT9tuc/hSrtw6uzJOvgRr2a9jyxxT1ely+B+xFAmJKVSTbpM/CuL7qxO8w==" crossorigin="anonymous" />
        <link rel="stylesheet" href="./css/main.css">
    </head>
    <body>
        <!-- Header section -->
        <header class="main-header">
            <div class="container">
                <div class="main-header__brand">
                    <a href="index.html">
                        <img src="./images/logo.png" alt="Logo">
                    </a>
                </div>
                <nav class="main-navigation">
                    <ul class="main-navigation__items">
                        <li class="main-navigation__item active">
                            <a href="#">Asosiy</a>
                        </li>
                        <li class="main-navigation__item">
                            <a href="#">Men haqimda</a>
                        </li>
                        <li class="main-navigation__item">
                            <a href="#">Xizmatlar</a>
                        </li>
                        <li class="main-navigation__item">
                            <a href="#">Mijozlar</a>
                        </li>
                        <li class="main-navigation__item">
                            <a href="#">Portfolio</a>
                        </li>
                        <li class="main-navigation__item">
                            <a href="#">Blog</a>
                        </li>
                        <li class="main-navigation__item">
                            <a href="#">Sheriklar</a>
                        </li>
                    </ul>
                </nav>
            </div>
        </header>
        <!-- /Header section -->

        <!-- Main section -->
        <div class="main-banner">
            <div class="container">
                <section id="main-section" class="main-section">
                    <div class="main-section__info">
                        <h4 class="main-section__welcome to-uppercase">Salom hammaga!</h4>
                        <h1 class="main-section__introduction to-uppercase">I am Sardorbek</h1>
                        <h3 class="main-section__position to-uppercase">Junior (kichik) dasturchi & Vlogger</h3>
                        <div class="main-section__social-networks">
                            <a href="https://t.me/sardorbek_kasimov01">
                                <i class="fab fa-telegram"></i>
                            </a>
                            <a href="https://www.youtube.com/channel/UC1wuFkzE7FZ7CsbdatrdGBw">
                                <i class="fab fa-youtube"></i>
                            </a>
                            <a href="https://instagram.com/oken.musilman">
                                <i class="fab fa-instagram"></i>
                            </a>
                        </div>
                        <button type="button" class="button main-section__action to-uppercase">
                            Ishlarim ko'ring
                        </button>
                    </div>
                    <div class="main-section__image">
                        <img src="./images/me.png" alt="My image">
                    </div>
                </section>
                <div class="clearfix"></div>
            </div>
        </div>
        <!-- /Main section -->

        <!-- Statistics -->
        <div class="container">
            <section id="statistics" class="statistics">
                <div class="statistics__item">
                    <h3 class="statistics__number">
                        0
                    </h3>
                    <p class="statistics__title">
                        Hursand mijozlar
                    </p>
                </div>
                <div class="statistics__item">
                    <h3 class="statistics__number">
                        10
                    </h3>
                    <p class="statistics__title">
                        Yordam
                    </p>
                </div>
                <div class="statistics__item">
                    <h3 class="statistics__number">
                       0
                    </h3>
                    <p class="statistics__title">
                        O'rtacha reyting
                    </p>
                </div>
            </section>
        </div>

        <!-- About me section -->
        <div class="container">
            <section id="about-me" class="about-me">
                <div class="about-me__image">
                    <img src="./images/about-me.png" alt="About me image">
                </div>
                <div class="about-me__info">
                    <h5 class="section-subtitle">
                        Men haqimda
                        <span class="blur-line"></span>
                    </h5>
                    <h3 class="section-title">
                        Junior (Kichik) dasturchi
                    </h3>
                    <p class="about-me__description">
Mening ismim Sarodorbek. Men 2005- yil qashqadaryo viloyati kitob tumanida tug'ulganman. Hozirgi kunda shun tumandagi 2-IDumida o'qiyman va men junior dasturchiman.                     </p>
                    <button type="button" class="button to-uppercase about-me__action">
                        CV ko'chirib olish
                    </button>
                </div>
            </section>
            <div class="clearfix"></div>
        </div>
        <!-- /About me section -->

        <!-- Services section -->
       <div class="container">
            <section id="services" class="services">
                <h5 class="section-subtitle">
                    Mening xizmatlarim
                    <span class="blur-line"></span>
                </h5>
                <h2 class="section-title">
                    Men taklif <br>
                    qiladigan xizmatlar
                </h2>
                <div class="services__cards">
                    <div class="service-card">
                        <img class="service-card__icon" src="./images/service-1.png" alt="Service 1">
                        <h5 class="service-card__title">Veb dasturlash</h5>
                        <p class="service-card__description">
                            Savollaringizga to'liq javoblar va birinchi veb saytingizni yaratish uchun kerak bo'ladigan barcha resurslar
                        </p>
                        <a href="#" class="service-card__link">
                            Ko'proq
                        </a>
                    </div>

                    <div class="service-card">
                        <img class="service-card__icon" src="./images/service-2.png" alt="Service 1">
                        <h5 class="service-card__title">Veb dasturlash</h5>
                        <p class="service-card__description">
                            Savollaringizga to'liq javoblar va birinchi veb saytingizni yaratish uchun kerak bo'ladigan barcha resurslar
                        </p>
                        <a href="#" class="service-card__link">
                            Ko'proq
                        </a>
                    </div>

                    <div class="service-card">
                        <img class="service-card__icon" src="./images/service-3.png" alt="Service 1">
                        <h5 class="service-card__title">Veb dasturlash</h5>
                        <p class="service-card__description">
                            Savollaringizga to'liq javoblar va birinchi veb saytingizni yaratish uchun kerak bo'ladigan barcha resurslar
                        </p>
                        <a href="#" class="service-card__link">
                            Ko'proq
                        </a>
                    </div>
                </div>
            </section>
       </div>
        <!-- /Services section -->

        <!-- Clients section -->
        <div class="container">
            <section id="clients" class="clients">
                <h5 class="section-subtitle">
                    Mening mijozlarim
                    <span class="blur-line"></span>
                </h5>
                <h2 class="section-title">
                    Hurmatli mijozlarim <br>
                    men haqimda
                </h2>
                <div class="client-items">
                    <div class="client-item">
                        <div class="client-item__image">
                            <img src="./images/about-me.png" alt="Client image">
                        </div>
                        <div class="client-item__info">
                            <h3 class="client-item__name">
                                Alisher Sultonov
                            </h3>
                            <p class="client-item__position">
                                Senior (katta) dasturchi
                            </p>
                            <p class="client-item__review">
                                Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. 
                            </p>
                            <div class="client-item__rate">
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                            </div>
                        </div>
                    </div>
                </div>
            </section>
            <div class="clearfix"></div>
        </div>
        <!-- /Clients section -->

        <!-- Portfolio section -->
        <div class="container">
            <section id="portfolio" class="portfolio">
                <div class="section-subtitle">
                    Mening ishlarim
                    <span class="blur-line"></span>
                </div>
                <div class="section-title">
                    Mening oxirgi <br>
                    ishlarimni ko'ring
                </div>
                <ul class="portfolio-filters">
                    <li class="active">
                        Hammasi
                    </li>
                    <li>
                        Mashhurlari
                    </li>
                    <li>
                        Oxirgilari
                    </li>
                </ul>
                <div class="portfolio-items">
                    <div class="portfolio-item portfolio-item-1">
                        <img src="./images/portfolio-1.jpg" alt="Portfolio image 1" class="portfolio-item__image">
                        <div class="portfolio-item__overlay"></div>
                        <div class="portfolio-item__info">
                            <h4>
                                <a href="#">Portolio item 1</a>
                            </h4>
                            <p>
                                Ishim haqida
                            </p>
                        </div>
                    </div>
                    <div class="portfolio-item portfolio-item-2">
                        <img src="./images/portfolio-2.jpg" alt="Portfolio image 2" class="portfolio-item__image">
                        <div class="portfolio-item__overlay"></div>
                        <div class="portfolio-item__info">
                            <h4>
                                <a href="#">Portolio item 2</a>
                            </h4>
                            <p>
                                Ishim haqida
                            </p>
                        </div>
                    </div>
                    <div class="portfolio-item portfolio-item-3">
                        <img src="./images/portfolio-3.jpg" alt="Portfolio image 3" class="portfolio-item__image">
                        <div class="portfolio-item__overlay"></div>
                        <div class="portfolio-item__info">
                            <h4>
                                <a href="#">Portolio item 3</a>
                            </h4>
                            <p>
                                Ishim haqida
                            </p>
                        </div>
                    </div>
                </div>
            </section>
        </div>
        <!-- /Portfolio section -->

        <!-- Blog section -->
        <div class="container">
            <section id="blog" class="blog">
                <div class="section-subtitle">
                    Mening blogim
                    <span class="blur-line"></span>
                </div>
                <div class="section-title">
                    Oxirgi maqolalarim
                </div>
                <div class="blog-items">
                    <div class="blog-item">
                        <div class="blog-item__image">
                            <img src="./images/blog-1.jpg" alt="Blog 1 image">
                        </div>
                        <div class="blog-item__info">
                            <div class="blog-item__main-info">
                                <span class="blog-item__author">
                                    <i class="fa fa-user"></i>
                                    Admin post
                                </span>
                                <span class="blog-item__date">
                                    <i class="fa fa-calendar"></i>
                                    Feb 5, 2021
                                </span>
                            </div>
                            <h5 class="blog-item__title">
                                Mening maqolam...
                            </h5>
                            <p class="blog-item__description">
                                Have whose a two night earth she set you creeping replenish place whales move Forth first him seed green.
                            </p>
                            <a class="blog-item__learn-more">
                                Ko'proq o'qish
                            </a>
                        </div>
                    </div>
                    <div class="blog-item">
                        <div class="blog-item__image">
                            <img src="./images/blog-2.jpg" alt="Blog 1 image">
                        </div>
                        <div class="blog-item__info">
                            <div class="blog-item__main-info">
                                <span class="blog-item__author">
                                    <i class="fa fa-user"></i>
                                    Admin post
                                </span>
                                <span class="blog-item__date">
                                    <i class="fa fa-calendar"></i>
                                    Feb 5, 2021
                                </span>
                            </div>
                            <h5 class="blog-item__title">
                                Mening maqolam...
                            </h5>
                            <p class="blog-item__description">
                                Have whose a two night earth she set you creeping replenish place whales move Forth first him seed green.
                            </p>
                            <a class="blog-item__learn-more">
                                Ko'proq o'qish
                            </a>
                        </div>
                    </div>
                    <div class="blog-item">
                        <div class="blog-item__image">
                            <img src="./images/blog-3.jpg" alt="Blog 1 image">
                        </div>
                        <div class="blog-item__info">
                            <div class="blog-item__main-info">
                                <span class="blog-item__author">
                                    <i class="fa fa-user"></i>
                                    Admin post
                                </span>
                                <span class="blog-item__date">
                                    <i class="fa fa-calendar"></i>
                                    Feb 5, 2021
                                </span>
                            </div>
                            <h5 class="blog-item__title">
                                Mening maqolam...
                            </h5>
                            <p class="blog-item__description">
                                Have whose a two night earth she set you creeping replenish place whales move Forth first him seed green.
                            </p>
                            <a class="blog-item__learn-more">
                                Ko'proq o'qish
                            </a>
                        </div>
                    </div>
                </div>
            </section>
        </div>
        <!-- /Blog section -->

        <!-- Partners section -->
        <div class="container">
            <section id="partners" class="partners">
                <div class="partner">
                    <img src="./images/partner-1.png">
                </div>
                <div class="partner">
                    <img src="./images/partner-2.png">
                </div>
                <div class="partner">
                    <img src="./images/partner-3.png">
                </div>
                <div class="partner">
                    <img src="./images/partner-4.png">
                </div>
                <div class="partner">
                    <img src="./images/partner-5.png">
                </div>
            </section>
        </div>
        <!-- /Partners section -->

        <!-- Footer section -->
        <footer>
            <nav>
                <ul>
                    <li>
                        <a href="#">Asosiy</a>
                    </li>
                    <li>
                        <a href="#">Men haqimda</a>
                    </li>
                    <li>
                        <a href="#">Xizmatlar</a>
                    </li>
                    <li>
                        <a href="#">Mijozlar</a>
                    </li>
                    <li>
                        <a href="#">Portfolio</a>
                    </li>
                    <li>
                        <a href="#">Blog</a>
                    </li>
                    <li>
                        <a href="#">Sheriklar</a>
                    </li>
                </ul>
            </nav>
        </footer>
        <!-- /Footer section -->
    </body>
</html>
