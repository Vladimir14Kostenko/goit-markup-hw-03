# goit-markup-hw-01
<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Web Studio</title>
    <link href="https://fonts.googleapis.com/css2?family=Raleway:wght@700&family=Roboto:wght@400;500;700;900&display=swap"
        rel="stylesheet"/>
    <link rel="stylesheet" href="<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/modern-normalize/1.1.0/modern-normalize.min.css"
    integrity="sha512-wpPYUAdjBVSE4KJnH1VR1HeZfpl1ub8YT/NKx4PuQ5NmX2tKuGu6U/JRp5y+Y8XG2tV+wKQpNHVUX03MfMFn9Q=="
      crossorigin="anonymous"
      referrerpolicy="no-referrer"/>

    <link rel="stylesheet" href="./css/styles.css"/>
</head>
<body>
    <header class="header">
        <div class="container main-nav">
        <a class="logo link" href=""><span class="log-icon">Web</span>Studio</a>
        <!--навигация-->
        <nav class="nav">
        <ul class="site-nav list">
                <li><a class="link current" href="./index.html">Студия</a></li>
                <li><a class="link" href="./portfolio.html">Портфолио</a></li>
                <li><a class="link" href=""">Контакты</a></li>
            </ul>
        </nav>
        <!--контакты-->
        <ul class="contacts list">
            <li><a class="link" href="mailto:info@devstudio.com">info@devstudio.com</a></li>
            <li><a class="link" href="tel:380961111111">+38-096-111-11-11</a></li>
        </ul>
        </div>
    </header>
    
    <main>
        <!--герой-->
        <section class="hero">
            <h1 class="hero-title">Эффективные решения <br />для вашего бизнеса</h1>
            <button class="hero-button" type="button">Заказать услугу</button>
        </section>

        <!--приоритеты-->
        <section class="section-feature section">
            <div class="container">
                <h2 hidden>приоритеты</h2>

            <ul class="feature-list list">
                <li class="feature-item">
                    <h3 class="feature">Внимание к деталям</h3>
                    <p class="feature-text">
                        Идейные соображения, а также начало повседневной работиы по формированию позиции.</p>
                    </li>
                <li class="feature-item">
                    <h3 class="feature">Пунктуальность</h3>
                    <p class="feature-text">
                        Задача организации, в особенности же рамки и место обучения кадров влечет за собой.</p>

                </li>
                <li class="feature-item">
                    <h3 class="feature">Планирование</h3>
                    <p class="feature-text">
                        Равным образом консультация с широким активом в значительной степени обуславливает</p>
                </li>
                <li class="feature-item">
                    <h3 class="feature">Современные технологии</h3>
                    <p class="feature-text">
                        Значимость этих проблем настолько очевидна,что реализация плановых заданий</p>
                </li>
            </ul>
            </div>
        </section>

        
    <!--чем мы занимаемся-->
        <section class="section work">
            <div class="container">
            <h2 class="section-title">Чем мы занимаемся</h2>
            <ul class="box-item list">
            
                <li class="box"><img src="./images/img.jpg" alt="верстка кода" width="370" height="294"></li>
                <li class="box"><img src="./images/img2.jpg" alt="телефон в руках" width="370" height="294"></li>
                <li class="box"><img src="./images/img3.jpg" alt="планшет в руках" width="370" height="294"></li>
            </ul>
            </div>
        </section>
        <!--команда-->
        <section class="section comand">
            <div class="container">
            <h2 class="section-title">Наша команда</h2>
            <ul class="icon list">
                <li class="icon-item"><img src="./images/igor.jpg" alt="Igor photo" width="270" height="260"/>
                
                    <h3 class="section-avatar">Игорь Демьяненко</h3>
                    <p class="icon-text">Product Designer</p>

                </li>

                <li class="icon-item"><img src="./images/olga.jpg" alt="Olga photo" width="270" height="260"/>
                
                    <h3 class="section-avatar">Ольга Репина</h3>
                    <p class="icon-text">Frontend Developer</p>
                </li>

                <li class="icon-item"><img src="./images/nikolay.jpg" alt="Nikolay photo" width="270" height="260"/>
                
                    <h3 class="section-avatar">Николай Тарасов</h3>
                    <p class="icon-text">Marketing</p>
                </li>

                <li class="icon-item"><img src="./images/michail.jpg" alt="Michail photo" width="270" height="260"/>
                
                    <h3 class="section-avatar">Михаил Ермаков</h3>
                    <p class="icon-text">UI Designer</p>
                </li>
            </ul>
            </div>
        </section>
    </main>
    <!--футер-->
    <footer class="footer">
        <div class="container">
        <a class="logo-footer link" href=""><span class="footer-icon">Web</span>Studio</a>
        
        <address>
            <ul class="footer-list list">
                <li class="footer-items"><a class="footer-address link" href="https://www.google.ru/maps/place/Киев, пр-т Леси Украинки,26">Киев, пр-т Леси Украинки,26</a></li>
                <li class="footer-items">
                    <a class="footer-contacts link" href="tel:+380991111111">+38-099-111-11-11</a></li>
                <li><a class="footer-contacts link" href="mailto:info@example.com">info@example.com</a></li>
            </ul>
            
        </address>
        </div>
        
    </footer>

    
</body>
</html>



css mine

:root {
  --primary-text-color: #757575;
  --title-text-color: #212121;
  --accent-color: #2196f3;
  --white-color: #ffffff;
  --section-color: #2f303a;
}


body {
   background-color: var(--white-color);
   color: var(--primary-text-color);
   font-family: Roboto, sans-serif;
 }

 /*для скрытия маркеров*/
 .list {
   list-style: none;
   padding: 0;
   margin: 0;
 }
/*для скрытия подчеркивания*/
.link {
  text-decoration: none;
}

/*для центровки контента */
.cotainer {
  width: 1200px;
  margin: 0 auto;
  padding-left: 15px;
  padding-right: 15px;
}

/*верхний и нижний отступ */
 .section {
   padding: 94px 0;
 }

/*логотип*/
.logo {
  margin-right: 93px; 
  color: #000000;
   font-family: Raleway;
   font-size: 26px;
   line-height: 1.19;
   letter-spacing: 0.03em;
 }

 .logo-icon {
  color: var(--accent-color);
}
/*навигация*/
.main-nav {
  display: flex;
  align-items: center;
  padding-top: 24px;
  padding-bottom: 25px;
}
.site-nav {
  display: flex;
}
.site-nav > li:not(:last-child) {
  margin-right: 50px;
}
.site-nav a {
  color: var(--title-text-color);
  font-weight: 500;
  font-size: 14px;
  line-height: 1.14;
  letter-spacing: 0.02em;
}
.site-nav a:hover,
.site-nav a:focus {
  color: var(--accent-color);
}
.site-nav .link.current {
  color: var(--accent-color);
}
/*контакты*/
.contacts {
  display: : flex;
  margin-left: auto;
}

.contacts > li:not(:last-child)  {
  margin-right: 50px;
}

.contacts a {
  color: var(--primary-text-color);
  font-weight: 500;
  font-size: 14px;
  line-height: 1.4;
  letter-spacing: 0.02em;
}
.contacts a:hover,
.contacts a:focus {
  color: var(--accent-color);
}
/*рамка которая под хедером */
.header {
  border: 1px solid #ececec;
}

/*index.html*/
/*hero*/
.hero {
  text-align: center;
  max-width: 0 auto;
  background-color: : var(--section-color);
}

.hero-title {
  margin-top: 0;
  margin-bottom: 30px;
  padding-top: 200px;

  color: var(--white-color);
  font-weight: 900;
  font-size: 44px;
  line-height: 1.36;
  letter-spacing: 0.06em;
  text-transform: uppercase;
}


.hero-button {
  margin-bottom: 200px;
  align-items: center;
  text-align: center;
  letter-spacing: 0.06em;

  padding: 10px 32px;
  min-width: 200px;
  min-height: 50px;
  box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.15);
  border-radius: 4px;

   background-color: var(--accent-color);
   color: var(--white-color);
   cursor: pointer;
   font-weight: 700;
   font-size: 16px;
   line-height: 1.88;
}
.hero-button:hover,
.hero-button:focus {
  background-color:  #188ce8;
}

  
  
 /*приоритеты*/
 .section-feature {
   margin-top: 0;
   margin-bottom: 0;
 } 

 .feature-list {
   display: : flex;
   flex-wrap: wrap;
 }

 .feature-item {
   width: 270px;
   margin-right: 30px;
 }

 .feature-item:last-child {
   margin-right: 0;
 }

 .feature {
   color: var(--title-text-color);
   font-weight: 700;
   font-size: 14px;
   line-height: 1.14;
   letter-spacing: 0.03em;
   text-transform: uppercase;
   margin-top: 0;
   margin-bottom: 10px;
 }

 .feature-text {
   font-size: 14px;
   line-height: 1.71;
   letter-spacing: 0.03em;
   margin-top: 0;
   margin-bottom: 0;
 }

 /*чем мы занимаемся & наша команда*/
 .work {
   padding: 0;
 }
 .section-title {
   margin-top: 0;
   margin-bottom: 50px;
 
   color: var(--title-text-color);
   font-weight: 700;
   font-size: 36px;
   line-height: 1.16;
   letter-spacing: 0.03em;
   text-align: center;
 }

 .box-item {
   display: flex;
   flex-wrap: wrap;
 }
.box {
  padding-bottom: 94px;
  margin-bottom: 30px;
}
.box:last-child {
  margin-right: 0;
}

/*наша команда*/
.comand {
  background-color: #f5f4fa;
  margin-top: 0;
  margin-bottom: 0;
}

.icon {
  display: flex;
  flex-wrap: wrap;
}
.icon-items {
  margin-right: 30px;
  background-color: #ffffff;
  box-shadow: 0px 1px 3px rgba(0, 0, 0, 0.12), 0px 1px 1px rgba(0, 0, 0, 0.14),
    0px 2px 1px rgba(0, 0, 0, 0.2);
  border-radius: 0px 0px 4px 4px;
}

.icon-items:last-child {
  margin-right: 0;
}

.section-avatar {
  margin-top: 30px;
  margin-bottom: 0;

   color: var(--title-text-color);
   font-weight: 500;
   font-size: 16px;
   line-height: 1.19;
   letter-spacing: 0.03em;

   text-align: center;

 }

 .icon-text {
  margin-top: 10px;
  margin-bottom: 0;
  padding-bottom: 30px;


   font-size: 16px;
   line-height: 1.19;
   letter-spacing: 0.03em;

   text-align: center;
}

/*footer*/
.footer {
  display: flex;
  margin: 0 auto;
  padding: 60px 0;
  background-color: var(--section-color);
}
.logo-footer {
  margin-bottom: 20px;
   color: var(--white-color);
   font-family: Raleway;
   font-size: 26px;
   line-height: 1.19;
   letter-spacing: 0.03em;
 }

 .footer-icon {
   color: var(--accent-color);
 }
 
 .footer-list { 
     margin-top: 20px;
 }

 .footer-items {
  /*   топ будет 20 */
  margin-bottom: 9px;
}

 .footer-address {
   font-style: normal;
   color: var(--white-color);
   background-color: var(--section-color);
   font-size: 14px;
   line-height: 1.71;
   letter-spacing: 0.03em;
 }

 .footer-contacts {
   margin-bottom: 9px;
   font-style: normal;
   color: rgba(255, 255, 255, 0.6); 
   background-color: (--section-color); 
   font-size: 14px;
   line-height: 1.71;
   letter-spacing: 0.03em;
 }

.footer-contacts:hover,
.footer-contacts:focus {
  color: var(--accent-color);
}


/*Portfolio*/
/*buttons*/

.portfolio {
  text-align: center;
  padding-top: 0;
}

.btn-list {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
}

.btn-items {
  margin-right: 8px;
}

.btn-items:last-child {
  margin-right: 0;
}

.btn {
  margin-top: 84px;
  margin-bottom: 50px;
  padding: 6px 22px;
  border-radius: 4px;

  background-color: #f5f4fa;
  color: var(--title-text-color);
  cursor: pointer;
  font-family: inherit;
  font-weight: 500;
  font-size: 16px;
  line-height: 1.62;
  letter-spacing: 0.03em;

  text-align: center;
}

.btn:hover,
.btn:focus {
  background-color: var(--accent-color);
  color: var(--white-color);
}

.photo-list {
  display: flex;
  flex-wrap: wrap;
}

.photo {
  margin-right: 30px;
  margin-bottom: 30px;
}

.image {
  display: block;
}

.photo > .link {
  margin-bottom: 0;
}

.photo:nth-child(3n) {
  margin-right: 0;
}

/*галлерея фото*/
.portfolio-items {
  margin: 0px 24px 4px 24px;
  padding-top: 20px;
  color: var(--title-text-color);
  font-weight: 700;
  font-size: 18px;
  line-height: 2;

  letter-spacing: 0.06em;
}

.portfolio-text {
  margin: 0 24px 20px 24px;
  font-size: 16px;
  line-height: 1.87;
  letter-spacing: 0.03em;
  color: var(--primary-text-color);
}

.border {
  text-align: left;
  margin-top: 0;
  border-left: 1px solid #eeeeee;
  border-right: 1px solid #eeeeee;
  border-bottom: 1px solid #eeeeee;
}
портфолио мое html
<!DOCTYPE html>
<html lang="ru">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio</title>
    <link href="https://fonts.googleapis.com/css2?family=Raleway:wght@700&family=Roboto:wght@400;500;700;900&display=swap"
        rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/modern-normalize/1.1.0/modern-normalize.min.css"
        integrity="sha512-wpPYUAdjBVSE4KJnH1VR1HeZfpl1ub8YT/NKx4PuQ5NmX2tKuGu6U/JRp5y+Y8XG2tV+wKQpNHVUX03MfMFn9Q=="
        crossorigin="anonymous" referrerpolicy="no-referrer" />
    <link rel="stylesheet" href="./css/styles.css" />
</head>

<body>
    <header class="header">
        <div class="container main-nav">
        <a class="logo link" href=""><span class="logo-icon">Web</span>Studio</a>

        <nav class="nav">
            <ul class="site-nav list">
                <li><a class="link" href="./index.html">Студия</a></li>
                <li><a class="link current" href="">Портфолио</a></li>
                <li><a class="link" href="">Контакты</a></li>
            </ul>
        </nav>
        <ul class="contacts list">
            <li><a class="link" href="mailto:info@devstudio.com">
                    info@devstudio.com</a></li>
            <li><a class="link" href="tel:+380961111111">+38 096 111 11 11</a></li>
        </ul>
        </div>
    </header>
    <main>
        <section class="portfolio section">
            <div class="container">
            <h1 hidden>Portfolio</h1>
            <ul class="btn-list list">
                <li class="btn-items">
                    <button class="btn" type="button">Все</button></li>
                <li class="btn-items">
                    <button class="btn" type="button">Веб-сайты</button></li>
                <li class="btn-items">
                    <button class="btn" type="button">Приложения</button></li>
                <li class="btn-items">
                    <button class="btn" type="button">Дизайн</button></li>
                <li class="btn-items">
                    <button class="btn" type="button">Маркетинг</button></li>
            </ul>

            <!--фото-->
            <ul class="photo-list list">
                <li class="photo">
                    <a class="link" href="">
                    <img class="image" src="./images/notebook.jpg" alt="technokryak" width="370" height="300" />
                    
                    <div class="border">
                    <h2 class="portfolio-items">Технокряк</h2>
                    <p class="portfolio-text">Веб-сайт</p>
                    </div>
                    </a>            
                </li>

                <li class="photo">
                    <a class="link" href="">
                    <img src="./images/basketball.jpg" alt="poster-new-orlean-vs-srat" width="370" height="300">
                    
                    <div class="border">
                    <h2 class="portfolio-items">Постер New Orlean vs Golden Star</h2>
                    <p class="portfolio-text">Дизайн</p>
                    </div>
                    </a>
                </li>
                
                <li class="photo">
                    <a class="link" href="">
                    <img src="./images/restaurant.jpg" alt="seafood" width="370" height="300" />
                    
                    <div class="border">
                    <h2 class="portfolio-items">Ресторан Seafood</h2>
                    <p class="portfolio-text">Приложение</p>
                    </div>
                    </a>
                
                </li>
                
                <li class="photo">
                    <a class="link" href="">
                    <img src="./images/headphones.jpg" alt="project-prime" width="370" height="300" />
                    
                    <div class="border">
                    <h2 class="portfolio-items">Проект Prime</h2>
                    <p class="portfolio-text">Маркетинг</p>
                    </div>
                    </a>
                
                </li>


                <li class="photo">
                    <a class="link" href="">
                    <img src="./images/boxes.jpg" alt="project-boxes" width="370" height="300" />
                    
                    <div class="border">
                    <h2 class="portfolio-items">Проект Boxes</h2>
                    <p class="portfolio-text">Приложение</p>
                    </div>
                    </a>
                
                </li>


                <li class="photo">
                    <a class="link" href="">
                    <img src="./images/monitor.jpg" alt="isipiration-has-no-border" width="370" height="300" />
                    
                    <div class="border">
                    <h2 class="portfolio-items">Inspiration has no Borders</h2>
                    <p class="portfolio-text">Веб-сайт</p>
                    </div>
                    </a>
                
                </li>

                <li class="photo">
                    <a class="link" href="">
                    <img src="./images/book.jpg" alt="limited-edition" width="370" height="300" />
                    
                    <div class="border">
                    <h2 class="portfolio-items">Издание Limited Edition</h2>
                    <p class="portfolio-text">Дизайн</p>
                    </div>
                    </a>
                
                </li>

                <li class="photo">
                    <a class="link" href="">
                    <img src="./images/labeltag.jpg" alt="project-lab" width="370" height="300" />
                    
                    <div class="border">
                    <h2 class="portfolio-items">Проект LAB</h2>
                    <p class="portfolio-text">Маркетинг</p>
                    </div>
                    </a>
                
                </li>

                <li class="photo">
                    <a class="link" href="">
                    <img src="./images/growingbusiness.jpg" alt="growing-business" width="370" height="300" />
                    
                    <div class="border">
                    <h2 class="portfolio-items">Growing Business</h2>
                    <p class="portfolio-text">Приложение</p>
                    </div>
                    </a>
                
                </li>
            </ul>
            </div>
        </section>
    </main>

    <footer class="footer">
        <div class="container">
        <a class="logo-footer link" href=""><span class="footer-icon">Web</span>Studio</a>

        <address>
            <ul class="footer-list list">
                <li class="footer-items">
                    <a class="footer-address link" href="https://goo.gl/maps/AxwCZDzG8Fguy3GU9">г. Киев, пр-т Леси
                        Украинки,
                        26</a></li>
                <li class="footer-items">
                    <a class="footer-contacts link" href="info@example.com">info@example.com</a></li>
                
                    <li><a class="footer-contacts link" href="+380991111111">+38 099 111 11 11</a></li>
            </ul>
        </address>
        </div>
    </footer>
</body>

</html>