<!DOCTYPE html>
<html lang="en">
    <!-- 1:14:05 -->
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    
    <title>scroll</title>

    <script src="gsap.min.js" defer></script>
    <script src="ScrollTrigger.min.js" defer></script>
    <script src="ScrollSmoother.min.js" defer></script>

    <link rel="stylesheet" href="KarMa-style.css">
    <script src="app.js" defer></script>

</head>
<body>
    <div class="wrapper">
        <div class="content">
            <header class="hero-section">
                <!-- Для движения картинка с отставанием (лагом) <img data-lag=".5" data-speed=".6" class="hero" src="img/hero.png" alt="Hero"> -->
                <!-- <img data-speed=".6" class="hero" src="img/hero.png" alt="Hero"> -->
                <img data-speed=".6" class="hero" src="hero_2_KarMa (2).png" alt="Hero">
                <div class="conteiner">
                    <div data-speed=".7" class="main-header">
                        <h1 class="main-title">Karim <p align="center">&</p> Malika</h1>
                    </div>
                </div>
            </header>
        
            <div class="portfolio">
                <div class="container">
                    <main class="gallery">
                        <div data-speed=".9" class="gallery__left">
                            
                            <img class="gallery__item" src="House_Karim.jpg" alt="...">
                            <img class="gallery__item" src="Robot_Karim.jpg" alt="...">
                                                        
                            <div class="text-block gallery__item">
                                <h2 class="text-block__h">Что такое: no enter - no escape?</h2>
                                <p class="text-block__p">Сломанная клавиатура!</p>
                            </div>
                            
                            <img class="gallery__item" src="Shark_Karim.jpg" alt="...">
        
                        </div>
                        <div data-speed="1.1" class="gallery__right">
                            
                            <div class="text-block gallery__item">
                                <h2 class="text-block__h">СРОЧНО ПРОДАМ!!!</h2>
                                <p class="text-block__p">"мышь" в отличном состоянии, со всеми наворотами, пробег-5000 км!</p>
                            </div>
                            <img class="gallery__item" src="Robot_Malika.jpg" alt="...">
                            <img class="gallery__item" src="House_Malika.jpg" alt="...">
                            <img class="gallery__item" src="Shark_2_Karim.jpg" alt="...">
        
                        </div>
                    </main>
                </div>
            </div>
        </div>
    </div>
    

    <!-- <audio controls loop>
        <source src="img/repchik-m-4.mp3" type="audio/mpeg">
    </audio> -->

</body>
</html>
