# portfolio
## HTML CODE:
```html
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <link rel="stylesheet" href="styles.css">
        <link href='https://cdn.jsdelivr.net/npm/boxicons@2.0.5/css/boxicons.min.css' rel='stylesheet'>

        <title>Complete Responsive Portfolio Website</title>
    </head>
    <body>
         <header class="l-header">
            <nav class="nav bd-grid">
                <div>
                    <a href="#" class="nav__logo">Portfolio</a>
                </div>

                <div class="nav__menu" id="nav-menu">
                    <ul class="nav__list">
                        <li class="nav__item"><a href="home.html" class="nav__link active">Home</a></li>
                        <li class="nav__item"><a href="#about" class="nav__link">About</a></li>
                        <li class="nav__item"><a href="#skills" class="nav__link">Skills</a></li>
                        <li class="nav__item"><a href="#work" class="nav__link">Work</a></li>
                        <li class="nav__item"><a href="#contact" class="nav__link">Contact</a></li>
                    </ul>
                </div>

                <div class="nav__toggle" id="nav-toggle">
                    <i class='bx bx-menu'></i>
                </div>
            </nav>
        </header>

        <main class="l-main">
            <section class="home bd-grid" id="home">
                <div class="home__data">
                    <h1 class="home__title">Hi,<br>I'am <span class="home__title-color">Karthikeyan</span><br> Web Developer</h1>
                    <h2>Welcome to see my portfolio.</h2>
                    <a href="#contact" class="button">Contact</a>
                </div>

                <div class="home__social">
                    <a href="" class="home__social-icon"><i class='bx bxl-linkedin'></i></a>
                    <a href="" class="home__social-icon"><i class='bx bxl-behance' ></i></a>
                    <a href="" class="home__social-icon"><i class='bx bxl-github' ></i></a>
                </div>

                <div class="home__img">    
                    <img src="img/profile.png" alt="">
                </div>
            </section>
            <section class="about section " id="about">
                <h2 class="section-title">About</h2>

                <div class="about__container bd-grid">
                    <div class="about__img">
                        <img src="img/about.png" alt="">
                    </div>
                    
                    <div>
                        <h2 class="about__subtitle">I'am Karthikeyan</h2>
                        <p class="about__text">Practice on web development and done some work on web development,Also working on data science technology.</p>           
                    </div>                                   
                </div>
            </section>
            <section class="skills section" id="skills">
                <h2 class="section-title">Skills</h2>

                <div class="skills__container bd-grid">          
                    <div>
                        <h2 class="skills__subtitle">Profesional Skills</h2>
                        <p class="skills__text">these are my skill set and its level based on my knowledge</p>
                        <div class="skills__data">
                            <div class="skills__names">
                                <i class='bx bxl-html5 skills__icon'></i>
                                <span class="skills__name">HTML5</span>
                            </div>
                            <div class="skills__bar skills__html">

                            </div>
                            <div>
                                <span class="skills__percentage">95%</span>
                            </div>
                        </div>
                        <div class="skills__data">
                            <div class="skills__names">
                                <i class='bx bxl-css3 skills__icon'></i>
                                <span class="skills__name">CSS3</span>
                            </div>
                            <div class="skills__bar skills__css">
                                
                            </div>
                            <div>
                                <span class="skills__percentage">80%</span>
                            </div>
                        </div>
                        <div class="skills__data">
                            <div class="skills__names">
                                <i class='bx bxl-javascript skills__icon' ></i>
                                <span class="skills__name">JAVASCRIPT</span>
                            </div>
                            <div class="skills__bar skills__js">
                                
                            </div>
                            <div>
                                <span class="skills__percentage">60%</span>
                            </div>
                        </div>
                        <div class="skills__data">
                            <div class="skills__names">
                                <i class='bx bxs-paint skills__icon'></i>
                                <span class="skills__name">PYTHON</span>
                            </div>
                            <div class="skills__bar skills__ux">
                                
                            </div>
                            <div>
                                <span class="skills__percentage">75%</span>
                            </div>
                        </div>
                    </div>
                    
                    <div>              
                        <img src="img/skills.png" alt="" class="skills__img">
                    </div>
                </div>
            </section>

            <!--===== WORK =====-->
            <section class="work section" id="work">
                <h2 class="section-title">Work</h2>

                <div class="work__container bd-grid">
                    <div class="work__img">
                        <img src="img/1.jpg" alt="">
                    </div>
                    <div class="work__img">
                        <img src="img/2.jpg" alt="">
                    </div>
                    <div class="work__img">
                        <img src="img/3.jpg" alt="">
                    </div>
                    <div class="work__img">
                        <img src="img/4.jpg" alt="">
                    </div>
                    <div class="work__img">
                        <img src="img/5.jpg" alt="">
                    </div>
                    <div class="work__img">
                        <img src="img/6.jpg" alt="">
                    </div>
                </div>
            </section>

            <!--===== CONTACT =====-->
            <section class="contact section" id="contact">
                <h2 class="section-title">Contact</h2>

                <div class="contact__container bd-grid">
                    <p>Email:<a href="mailto:karthi06062004@gmail.com">karthi06062004@gmail.com</a></br></p>
                    <p>Call:<a href="callto:8825683856">8825683856</a></p>
                </div>
            </section>
        </main>

        <!--===== FOOTER =====-->
        <footer class="footer">
            <div class="footer__social">
                <a href="#" class="footer__icon"><i class='bx bxl-facebook' ></i></a>
                <a href="#" class="footer__icon"><i class='bx bxl-instagram' ></i></a>
                <a href="#" class="footer__icon"><i class='bx bxl-twitter' ></i></a>
            </div>
            <p>&#169; 2021 copyright all right reserved</p>
        </footer>
    </body>
</html>
```
