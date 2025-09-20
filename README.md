<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Siberian-Welness | Landing page for my business</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f8f8f8;
      margin: 0;
      padding: 20px;
      color: #333;
      font-size: 18px;
      line-height: 1.5;
    }
    header, footer {
      text-align: center;
      margin-bottom: 30px;
    }
    .container {
      max-width: 900px;
      margin: 0 auto;
    }
    .product {
      background-color: #fff;
      border: 1px solid #ddd;
      border-radius: 8px;
      padding: 20px;
      margin-bottom: 25px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
    }
    .image-container {
      text-align: center;
      margin-bottom: 10px;
    }
    .image-container img {
      max-width: 250px;
      width: 100%;
      height: auto;
      border-radius: 6px;
      object-fit: contain;
    }
    .caption {
      font-size: 14px;
      color: #777;
      margin-top: 5px;
    }
    ul {
      padding-left: 20px;
      margin: 10px 0;
      font-size: 16px;
    }
    p {
      font-size: 16px;
      margin: 10px 0;
    }
    .btn {
      display: inline-block;
      margin-top: 15px;
      padding: 12px 24px;
      background-color: #27ae60;
      color: #fff;
      text-decoration: none;
      border-radius: 5px;
      font-weight: bold;
      font-size: 16px;
      transition: background-color 0.3s ease;
    }
    .btn:hover {
      background-color: #1e8449;
    }
    .price {
      font-weight: bold;
      font-size: 18px;
      margin-top: 10px;
      color: #27ae60;
    }

    /* Адаптивность для мобильных */
    @media (max-width: 600px) {
      body {
        padding: 10px;
        font-size: 18px; /* чуть больше для удобства чтения */
      }
      .container {
        padding: 0 10px;
      }
      .product {
        padding: 15px;
      }
      .image-container img {
        max-width: 100%;
      }
      .btn {
        width: 100%;
        padding: 14px 0;
        font-size: 18px;
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>Продукты Siberian Wellness</h1>
    <p>Ваш консультант: Эльвира</p>
  </header>

  <div class="container">

    <!-- Продукт 1 -->
    <div class="product">
      <h2>Хелат железа Siberian Wellness</h2>
      <p>Хелат железа для улучшения кровообращения и повышения уровня гемоглобина.</p>
      <div class="image-container">
        <img src="https://static.siberianhealth.com/public/projects/shopen/images/50/_resize/501290_1e04a14d_fit_300_300.jpg" alt="Хелат железа Siberian Wellness" />
        <div class="caption">Баночка с хелатом железа (60 капсул)</div>
      </div>
      <ul>
        <li>Железо в форме хелата — 18 мг</li>
        <li>Улучшает кровообращение</li>
        <li>Поддерживает уровень гемоглобина</li>
      </ul>
      <p><strong>Как принимать:</strong> по 2 капсулы в день во время еды на протяжении месяца.</p>
      <div class="price">Цена: 1200 сом</div>
      <a href="https://wa.me/996771927032?text=Здравствуйте,%20хочу%20заказать%20хелат%20железа" target="_blank" class="btn">Заказать</a>
    </div>

    <!-- Продукт 2 -->
    <div class="product">
      <h2>Essential Minerals: Магний</h2>
      <p>Магний в органической форме для поддержки нервной системы и снятия усталости.</p>
      <div class="image-container">
        <img src="https://static.siberianhealth.com/public/projects/shopen/images/50/_resize/500629_b968dfed_fit_300_300.png" alt="Essential Minerals: Магний" />
        <div class="caption">Магний в капсулах (60 капсул)</div>
      </div>
      <ul>
        <li>Органическая форма магния — 150 мг</li>
        <li>Поддержка нервной системы</li>
        <li>Снижение утомляемости и стресса</li>
      </ul>
      <p><strong>Как принимать:</strong> по 3 капсулы в день во время еды в течение месяца.</p>
      <div class="price">Цена: 1300 сом</div>
      <a href="https://wa.me/996771927032?text=Здравствуйте,%20хочу%20заказать%20магний" target="_blank" class="btn">Заказать</a>
    </div>

    <!-- Продукт 3 -->
    <div class="product">
      <h2>Фиточай Siberian Wellness</h2>
      <p>Травяной чай для поддержки здоровья и улучшения самочувствия.</p>
      <div class="image-container">
        <img src="https://static.siberianhealth.com/public/projects/shopen/images/50/_resize/500586_sq_4f8e913a_fit_300_300.png" alt="Фиточай Siberian Wellness" />
        <div class="caption">Фиточай с сибирскими травами и ягодами</div>
      </div>
      <ul>
        <li>Натуральные травы и ягоды</li>
        <li>Способствует расслаблению</li>
        <li>Улучшает обмен веществ</li>
      </ul>
      <p><strong>Рекомендации:</strong> во время любого приема пищи.</p>
      <div class="price">Цена: 900 сом</div>
      <a href="https://wa.me/996771927032" target="_blank" class="btn">Заказать</a>
    </div>

    <!-- Продукт 4 -->
    <div class="product">
      <h2>Essential Minerals: Кальций</h2>
      <p>Кальций для укрепления костей, зубов и поддержки работы сердца и мышц.</p>
      <div class="image-container">
        <img src="https://static.siberianhealth.com/public/projects/shopen/images/50/_resize/500628_ae4723fd_fit_300_300.png" alt="Кальций" />
        <div class="caption">Кальций в капсулах (60 капсул)</div>
      </div>
      <ul>
        <li>Кальций в органической форме — 200 мг</li>
        <li>Укрепляет кости и зубы</li>
        <li>Поддерживает работу сердца и мышц</li>
      </ul>
      <p><strong>Как принимать:</strong> по 1 капсуле 3 раза в день во время еды.</p>
      <div class="price">Цена: 1250 сом</div>
      <a href="https://wa.me/996771927032?text=Здравствуйте,%20хочу%20заказать%20кальций" target="_blank" class="btn">Заказать</a>
    </div>

    <!-- Добавь остальные продукты аналогично -->

  </div>

  <footer>
    <p>© 2025 Консультант Siberian Wellness — Эльвира</p>
    <p>Данный сайт не является официальным!</p>
  </footer>

</body>
</html>
