<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="utf-8">
    <title>HTML Academy: Барбершоп</title>
</head>
<body>
  <header class="main-header">
    <div class="container">
      <div class="logo">
        <img src="http://placehold.it/150x100" alt="Barbershop"> 
      </div>
        <nav class="main-navigator">
          <ul>
            <li>
             <a href="#">Информация</a>
            </li>
            <li>
             <a href="#">Новости</a>
            </li>
            <li>
             <a href="#">Прайс-лист</a>
            </li>
            <li>
             <a href="#">Магазин</a>
            </li>
            <li>
              <a href="#">контакты</a>
            </li>
          </ul>
        </nav>                      
        <div class="user-block">
          <a class="login" href="#">Вход</a>
        </div>
    </div>
  </header>                    
<main class="catalog">
  <section class="breadcrumbs">
    <h1>Средства для ухода</h1>
      <ul>
        <li>
        <a href="#">главная</a>
        </li>
        <li> 
        <a href="#"> Магазин</a>
        </li>
        <li>
        <a href="#">средства для ухода</a>
        </li>
      </ul>
  </section>
  <form>
    <div class="manufacturer">
      <h2> производители:</h2>
        <label> <input type="checkbox" name="baxter" checked>baxter of california</label>
        <label> <input type="checkbox" name="natty">MR NATTY</label> 
        <label><input type="checkbox" name="suavecito" checked>suavecito</label>
        <label><input type="checkbox" name="malin">malin+goetz</label>
        <label><input type="checkbox" name="murray">murray`s</label>
        <label><input type="checkbox" name="crew" checked>american crew</label>
    </div>
      <div class="group">
        <h2>группы товаров:</h2>
      </div>
      <div class="show">
        <button>Показать</button>
      </div>
  </form>
  <div class="catalog-item">
    <article class="catalog-items">
      <div class="image">
        <a href="#"><img src="http://placehold.it/150x100"></a>
      </div>
      <div class="title"><a href="#">Набор для путешествий "BAXTER OF CALIFORNIA"</a></div>
      <div class="price"><span>2 900 руб. </span> <a class="buy-btn" href="#">Купить</a></div>
    </article>
    <article class="catalog-items">
      <div class="image">
        <a href="#"><img src="http://placehold.it/150x100"></a>  </div>
      <div class="title"><a href="#">Увлажняющий кондиционер "BAXTER OF CALIFORNIA"</a></div>
      <div class="price"><span>750 руб.</span>
        <a class="buy-btn" href="#">Купить</a></div>
    </article>
    <article class="catalog-items">
      <div class="image">
        <a href="#"><img src="http://placehold.it/150x100"></a></div>
      <div class="title"><a href="#">Гель для волос "SUAVECITO"</a></div>
      <div class="price"><span>290 руб.</span>
        <a class="buy-btn" href="#">Купить</a></div>
    </article>
    <article class="catalog-items">
      <div class="image">
        <a href="#"><img src="http://placehold.it/150x100"></a></div>
      <div class="title"><a href="#">Глина для укладки волос "AMERICAN CREW"</a></div>
      <div class="price"><span>500 руб.</span>
        <a class="buy-btn" href="#">купить</a></div>
    </article>
    <article class="catalog-items">
      <div class="image">
        <a href="#"><img src="http://placehold.it/150x100"></a></div>
      <div class="title"><a href="#">Гель для волос"AMERICAN CREW"</a></div>
      <div class="price"><span>300 руб.</span>
        <a class="buy-btn" href="#">купить</a></div>
    </article>
    <article class="catalog-items">
      <div class="image">
        <a href="#"><img src="http://placehold.it/150x100"></a>  </div>
      <div class="title"><a href="#">Набор для бритья "BAXTER OF CALIFORNIA"</a></div>
      <div class="price"><span>3900 руб.</span>
        <a class="buy-btn" href="#">купить</a></div>
    </article>
  </div>
    <div class="page">
      <a href="#1">1</a>
      <a href="#2">2</a>
      <a href="#3">3</a>
      <a href="#4">4</a>
    </div>
  </main>  
  <footer class="main-footer">
    <div class="container">
      <section class="footer-contacts">
          Барбершоп «Бородинский»<br>
          Адрес: г. Санкт-Петербург, Б. Конюшенная, д. 19/8<br>
          <a href="#">Как нас найти?</a><br>
          Телефон: +7 (812) 666-02-66
      </section>
      <section class="footer-social">
          <p>Давайте дружить!</p>
          <a class="social-btn social-btn-vk" href="#">Вконтакте</a>
          <a class="social-btn social-btn-fb" href="#">Фейсбук</a>
          <a class="social-btn social-btn-inst" href="#">Инстаграм</a>
      </section>
      <section class="footer-copyright">
          <p>Разработано:</p>
          <a class="btn" href="https://htmlacademy.ru">HTML Academy</a>
      </section>
    </div>
  </footer>
</body>
</html>
