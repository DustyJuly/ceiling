<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <title>Ceiling</title>
  <link rel="shortcut icon" href="images/fav.png" type="image/png">
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;500;700&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="css/normalize.css">
  <link rel="stylesheet" href="css/slick.css">
  <link rel="stylesheet" href="css/style.css">
  <link rel="stylesheet" href="css/media.css">
</head>
<body>
  <header class="header">
    <div class="container">
      <div class="header__logo">
        <a href="index.html">
          <img src="images/logo.svg" alt="Logo">
        </a>
      </div>
      <nav class="menu">
        <ul class="menu__list" id="menu">
          <li><a href="#price" class="btn-scroll">Цены</a></li>
          <li><a href="#calculator" class="btn-scroll">Калькулятор</a></li>
          <li><a href="#projects" class="btn-scroll">Проекты</a></li>
          <li><a href="#contacts" class="btn-scroll">Контакты</a></li>
        </ul>
      </nav>
      <div class="header__contact">
        <div class="header__contact-number">
          <a href="tel:89504445543">8(950)444 55 43</a>
          <p>Работаем с 8:00 до 19:00 без выходных</p>
        </div>
        <div class="header__contact-button">
          <button class="button--call" id="callBtn" type="submit">Консультация</button>
          
        </div>
      </div>
      <div class="menu__btn">
        <a class="js-toggle-menu hamburger-menu">
          <span></span>
          <span></span>
          <span></span>
        </a>
      </div>
    </div>
  </header>
  <!-- /.header -->
  <div class="mobile__menu" id="mobile__menu">
    <div class="container">
      <a href="#price">Цены</a>
      <a href="#calculator">Калькулятор</a>
      <a href="#projects">Проекты</a>
      <a href="#contacts">Контакты</a>
    </div>
  </div>
  <div id="callModal" class="modal">
    <div class="modal__content">
      <img class="close" src="images/close.svg" alt="Close">
      <h2 class="call__title">Заказать звонок</h2>
      <form id="call__form" action="call.php" method="POST">
        <input class="call__input call__input-name" id="call_name" type="text" name="name" placeholder="Ваше имя" required>
        <input class="call__input call__input-phone" id="call_tel" type="tel" name="tel" title="Please enter only digits" placeholder="Телефон" required>
        <button class="call__button" name="submit">Отправить</button>
      </form>
    </div>
  </div>
  <section class="banner">
    <div class="container">
      <div class="banner__content">
        <h1>Натяжные потолки <br/>от 159 <span>руб/м²</span></h1>
        <button class="button--call" id="callBtn1" type="submit">Заказать замер бесплатно</button>
        <div class="pros">
          <p class="pros__text"><span>20</span> лет на рынке</p>
          <p class="pros__text"><span>10</span> лет гарантии</p>
        </div>
      </div>
    </div>
  </section>
  <!-- /.banner -->
  <section class="advantages">
    <div class="container">
      <h3 class="section__title">Преимущества натяжных потолков</h3>
      <div class="advantages__items">
        <div class="advantages__item">
          <img src="images/advantage-1.svg" alt="advantage">
          <h5>Идеальный горизонт</h5>
          <p>Скрывает неровности основного потолка</p>
        </div>
        <div class="advantages__item">
          <img src="images/advantage-2.svg" alt="advantage">
          <h5>Скрытие комуникации </h5>
          <p>Закрывает коммуникации различных уровней</p>
        </div>
        <div class="advantages__item">
          <img src="images/advantage-3.svg" alt="advantage">
          <h5>Чистота и практичность</h5>
          <p>Не накапливается пыль и легко моется при необходимости</p>
        </div>
      </div>
    </div>
  </section>
  <!-- /.advantages -->
  <section class="price" id="price">
    <div class="container">
      <h3 class="section__title">Варианты натяжных потолков</h3>
      <div class="price__items">
        <div class="price__item">
          <h4 class="price__item-title">Матовые</h4>
          <p class="price__item-subtitle">для кухни, ванной, коридора спальни или детской</p>
          <table class="price__item-table">
            <tr>
              <td>Полотно + установка (м²)</td>
              <td>124 р</td>
            </tr>
            <tr>
              <td>Обработка 4 угла</td>
              <td>80 р</td>
            </tr>
            <tr>
              <td>Монтаж светильника</td>
              <td>20 р</td>
            </tr>
            <tr>
              <td>Обход 1 трубы</td>
              <td>30 р</td>
            </tr>
          </table>
          <p class="price__item-total">570р/м²</p>
        </div>
        <div class="price__item">
          <h4 class="price__item-title">Глянцевые</h4>
          <p class="price__item-subtitle">для кухни, ванной, коридора спальни или детской</p>
          <table class="price__item-table">
            <tr>
              <td>Полотно + установка (м²)</td>
              <td>124 р</td>
            </tr>
            <tr>
              <td>Обработка 4 угла</td>
              <td>80 р</td>
            </tr>
            <tr>
              <td>Монтаж светильника</td>
              <td>20 р</td>
            </tr>
            <tr>
              <td>Обход 1 трубы</td>
              <td>30 р</td>
            </tr>
          </table>
          <p class="price__item-total">460р/м²</p>
        </div>
        <div class="price__item">
          <h4 class="price__item-title">Тканевые</h4>
          <p class="price__item-subtitle">для кухни, ванной, коридора спальни или детской</p>
          <table class="price__item-table">
            <tr>
              <td>Полотно + установка (м²)</td>
              <td>124 р</td>
            </tr>
            <tr>
              <td>Обработка 4 угла</td>
              <td>80 р</td>
            </tr>
            <tr>
              <td>Монтаж светильника</td>
              <td>20 р</td>
            </tr>
            <tr>
              <td>Обход 1 трубы</td>
              <td>30 р</td>
            </tr>
          </table>
          <p class="price__item-total">330р/м²</p>
        </div>
        <div class="price__item">
          <h4 class="price__item-title">Фактурные</h4>
          <p class="price__item-subtitle">для кухни, ванной, коридора спальни или детской</p>
          <table class="price__item-table">
            <tr>
              <td>Полотно + установка (м²)</td>
              <td>124 р</td>
            </tr>
            <tr>
              <td>Обработка 4 угла</td>
              <td>80 р</td>
            </tr>
            <tr>
              <td>Монтаж светильника</td>
              <td>20 р</td>
            </tr>
            <tr>
              <td>Обход 1 трубы</td>
              <td>30 р</td>
            </tr>
          </table>
          <p class="price__item-total">670р/м²</p>
        </div>
        <div class="price__item">
          <h4 class="price__item-title">Сатиновые</h4>
          <p class="price__item-subtitle">для кухни, ванной, коридора спальни или детской</p>
          <table class="price__item-table">
            <tr>
              <td>Полотно + установка (м²)</td>
              <td>124 р</td>
            </tr>
            <tr>
              <td>Обработка 4 угла</td>
              <td>80 р</td>
            </tr>
            <tr>
              <td>Монтаж светильника</td>
              <td>20 р</td>
            </tr>
            <tr>
              <td>Обход 1 трубы</td>
              <td>30 р</td>
            </tr>
          </table>
          <p class="price__item-total">390р/м²</p>
        </div>
        <div class="price__item">
          <h4 class="price__item-title">Фотопечать</h4>
          <p class="price__item-subtitle">для кухни, ванной, коридора спальни или детской</p>
          <table class="price__item-table">
            <tr>
              <td>Полотно + установка (м²)</td>
              <td>124 р</td>
            </tr>
            <tr>
              <td>Обработка 4 угла</td>
              <td>80 р</td>
            </tr>
            <tr>
              <td>Монтаж светильника</td>
              <td>20 р</td>
            </tr>
            <tr>
              <td>Обход 1 трубы</td>
              <td>30 р</td>
            </tr>
          </table>
          <p class="price__item-total">270р/м²</p>
        </div>
      </div>
    </div>
  </section>
  <!-- /.price -->
  <section class="calculator" id="calculator">
    <div class="container">
      <h3 class="section__title">Калькулятор стоимости потолка</h3>
      <div class="calculator__items">
        <div class="calculator__item">
          <h5 class="calculator__item-title">Помещение</h5>
          <div class="calculator__item-row">
            <p>Длина</p>
            <div class="cart">
              <div class="cart__add-item">
                <button class="cart-button cart-button--less">-</button>
                <div class="cart-quantity">15</div>
                <button class="cart-button cart-button--more">+</button>
              </div>
            </div>
          </div>
          <div class="calculator__item-row">
            <p>Ширина</p>
            <div class="cart">
              <div class="cart__add-item">
                <button class="cart-button cart-button--less">-</button>
                <div class="cart-quantity">5</div>
                <button class="cart-button cart-button--more">+</button>
              </div>
            </div>
          </div>
        </div>
        <div class="calculator__item">
          <h5 class="calculator__item-title">Элементы, шт</h5>
          <div class="calculator__item-row">
            <p>Углы</p>
            <div class="cart">
              <div class="cart__add-item">
                <button class="cart-button cart-button--less">-</button>
                <div class="cart-quantity">4</div>
                <button class="cart-button cart-button--more">+</button>
              </div>
            </div>
          </div>
          <div class="calculator__item-row">
            <p>Лампы</p>
            <div class="cart">
              <div class="cart__add-item">
                <button class="cart-button cart-button--less">-</button>
                <div class="cart-quantity">6</div>
                <button class="cart-button cart-button--more">+</button>
              </div>
            </div>
          </div>
          <div class="calculator__item-row">
            <p>Трубы</p>
            <div class="cart">
              <div class="cart__add-item">
                <button class="cart-button cart-button--less">-</button>
                <div class="cart-quantity">1</div>
                <button class="cart-button cart-button--more">+</button>
              </div>
            </div>
          </div>
        </div>
        <div class="calculator__item">
          <h5 class="calculator__item-title">Материалы и цвет</h5>
          <div class="calculator__item-content">
            <div class="content-item">
              <form class="calculator__item-row">
                <label class="label label--margin">ПВХ
                  <input type="radio" checked="checked" name="radio">
                  <span class="checkmark"></span>
                </label>
                <label class="label">Ткань
                  <input type="radio" name="radio">
                  <span class="checkmark"></span>
                </label>
              </form>
            </div>
            <div class="content-item">
              <form class="calculator__item-row">
                <label class="label">Белый
                  <input type="radio" checked="checked" name="radio">
                  <span class="checkmark"></span>
                </label>
                <label class="label">Цветной
                  <input type="radio" name="radio">
                  <span class="checkmark"></span>
                </label>
              </form>
            </div>
            <div class="content-item">
              <form action="#">
                <select name="type">
                  <option value="value1" selected>Глянцевый</option>
                  <option value="value2">Матовый</option>
                  <option value="value3">Тканевый</option>
                  <option value="value4">Фактурный</option>
                  <option value="value5">Сатиновый</option>
                  <option value="value6">Фотопечать</option>
                </select>
              </form>
            </div>
          </div>
        </div>
      </div>
      <h4 class="calculator__total">Стоимость: <span>13 900 р</span></h4>
      <button class="button--call" id="callBtn2" type="submit">вызвать специалиста</button>
    </div>
  </section>
  <!-- /.calculator -->
  <section class="projects" id="projects">
    <div class="container">
      <h3 class="section__title">Выполненные работы</h3>
      <div class="sliders__inner">
        <div class="projects__slider">
          <div class="projects__slider-item"><img src="images/projects-1.jpg" alt="project"></div>
          <div class="projects__slider-item"><img src="images/projects-2.jpg" alt="project"></div>
          <div class="projects__slider-item"><img src="images/projects-3.jpg" alt="project"></div>
          <div class="projects__slider-item"><img src="images/projects-1.jpg" alt="project"></div>
          <div class="projects__slider-item"><img src="images/projects-2.jpg" alt="project"></div>
          <div class="projects__slider-item"><img src="images/projects-3.jpg" alt="project"></div>
          <div class="projects__slider-item"><img src="images/projects-1.jpg" alt="project"></div>
          <div class="projects__slider-item"><img src="images/projects-2.jpg" alt="project"></div>
          <div class="projects__slider-item"><img src="images/projects-3.jpg" alt="project"></div>
          <div class="projects__slider-item"><img src="images/projects-1.jpg" alt="project"></div>
        </div>
        <div class="project__slider">
          <div class="project__slider-item"><img src="images/project-1.jpg" alt="project"></div>
          <div class="project__slider-item"><img src="images/project-2.jpg" alt="project"></div>
          <div class="project__slider-item"><img src="images/project-3.jpg" alt="project"></div>
          <div class="project__slider-item"><img src="images/project-1.jpg" alt="project"></div>
          <div class="project__slider-item"><img src="images/project-2.jpg" alt="project"></div>
          <div class="project__slider-item"><img src="images/project-3.jpg" alt="project"></div>
          <div class="project__slider-item"><img src="images/project-1.jpg" alt="project"></div>
          <div class="project__slider-item"><img src="images/project-2.jpg" alt="project"></div>
          <div class="project__slider-item"><img src="images/project-3.jpg" alt="project"></div>
          <div class="project__slider-item"><img src="images/project-1.jpg" alt="project"></div>
        </div>
      </div>
    </div>
  </section>
  <!-- /.projects -->
  <section class="contacts" id="contacts">
    <div class="container">
      <h3 class="section__title">Остались вопросы?</h3>
      <div class="contacts__form-block">
        <form action="send.php" method="POST" class="contacts__form">
          <input type="text" class="contacts__form-input" placeholder="Имя" id="name" name="name" required>
          <input type="tel" class="contacts__form-input form__input-phone" placeholder="Телефон" id="tel" name="tel" required>
          <textarea class="contacts__form-input" rows="5" placeholder="Ваш вопрос" id="request" name="request"></textarea>
          <input class="button--mail" type="submit" name="submit" value="Отправить">
        </form>
        <div class="contacts__content">
          <a href="mailto:potolki.vaa@gmail.com" class="contacts__content-link" target="_blank">potolki.vaa@gmail.com</a>
          <a href="instagram/" class="contacts__content-link" target="_blank">Potolki.insta.com</a>
          <a href="https://wa.me/89504445543" class="contacts__content-link" target="_blank">8(950)444 55 43</a>
        </div>
      </div>
    </div>
  </section>
  <!-- /.contacts -->
  <footer class="footer">
    <div class="container">  
      <p class="footer__text">&copy; Created by MerryBand</p>
    </div>
  </footer>
  <!-- /.footer -->
  
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.4.1/jquery.min.js"></script>
  <script src="js/slick.min.js"></script>
  <script src="js/main.js"></script>
</body>
</html>
