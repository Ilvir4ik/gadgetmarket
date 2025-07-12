<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>GadgetStore — Продажа гаджетов онлайн</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0; padding: 0;
      background: #f4f4f4;
      color: #333;
    }
    header {
      background-color: #007acc;
      color: white;
      padding: 20px;
      text-align: center;
    }
    main {
      max-width: 900px;
      margin: 30px auto;
      background: white;
      padding: 20px;
      border-radius: 8px;
    }
    h1, h2 {
      color: #007acc;
    }
    .product {
      display: flex;
      gap: 20px;
      margin-top: 20px;
    }
    .product img {
      max-width: 300px;
      border-radius: 8px;
    }
    .product-info {
      flex: 1;
    }
    button {
      background-color: #007acc;
      color: white;
      border: none;
      padding: 15px 25px;
      font-size: 18px;
      border-radius: 5px;
      cursor: pointer;
    }
    button:hover {
      background-color: #005fa3;
    }
    footer {
      text-align: center;
      padding: 15px;
      background: #ddd;
      margin-top: 40px;
      font-size: 14px;
    }
  </style>
</head>
<body>

<header>
  <h1>GadgetStore</h1>
  <p>Лучшие гаджеты по выгодным ценам</p>
</header>

<main>
  <h2>Наш главный продукт</h2>
  <div class="product">
    <img src="https://via.placeholder.com/300x300.png?text=Гаджет+X" alt="Гаджет X" />
    <div class="product-info">
      <h3>Гаджет X</h3>
      <p>Современный и мощный гаджет с последними технологиями.</p>
      <ul>
        <li>Экран: 6.5 дюймов</li>
        <li>Процессор: Octa-Core 3.0 GHz</li>
        <li>Память: 8GB RAM, 128GB Storage</li>
        <li>Камера: 48 MP</li>
      </ul>
      <p><strong>Цена: 15 000 руб.</strong></p>
      <button onclick="alert('Спасибо за интерес! Мы свяжемся с вами.')">Купить сейчас</button>
    </div>
  </div>

  <section style="margin-top: 40px;">
    <h2>Контакты</h2>
    <p>Телефон: +7 (999) 123-45-67</p>
    <p>Email: info@smartgadgetstore.com</p>
  </section>
</main>

<footer>
  &copy; 2025 GadgetStore — Все права защищены
</footer>

</body>
</html>
