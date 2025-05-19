<!DOCTYPE html>
<html lang="uk">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Нічник MoonGlow</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background: #fefefe;
      color: #333;
    }
    header {
      background: #222;
      color: white;
      padding: 30px;
      text-align: center;
    }
    section {
      padding: 40px 20px;
      max-width: 960px;
      margin: auto;
    }
    .product {
      display: flex;
      flex-wrap: wrap;
      align-items: center;
      justify-content: center;
    }
    .product img {
      max-width: 320px;
      margin: 20px;
      border-radius: 15px;
    }
    .buy-button {
      display: inline-block;
      padding: 12px 30px;
      background: #ff9800;
      color: white;
      font-size: 18px;
      text-decoration: none;
      border-radius: 10px;
      margin-top: 20px;
    }
    .block {
      background: #fff;
      margin-top: 30px;
      padding: 25px;
      border-radius: 12px;
      box-shadow: 0 0 10px rgba(0,0,0,0.05);
    }
    form {
      display: flex;
      flex-direction: column;
      gap: 15px;
    }
    input, textarea {
      padding: 12px;
      font-size: 16px;
      border: 1px solid #ccc;
      border-radius: 8px;
    }
    button {
      padding: 14px;
      background: #28a745;
      color: white;
      font-size: 18px;
      border: none;
      border-radius: 10px;
      cursor: pointer;
    }
    button:hover {
      background: #218838;
    }
    footer {
      text-align: center;
      padding: 25px;
      background: #222;
      color: white;
      margin-top: 50px;
    }
  </style>
</head>
<body>

<header>
  <h1>Нічник MoonGlow</h1>
  <p>Заспокійливе світло для затишку та сну. Доставка по всій Україні!</p>
</header>

<section class="product">
  <img src="https://via.placeholder.com/320x320?text=MoonGlow+Lamp" alt="Нічник MoonGlow" />
  <div>
    <h2>Світильник MoonGlow — магія ночі у вашій кімнаті</h2>
    <p>Стильний нічник з теплим підсвічуванням. Ідеально підходить для дітей та дорослих. Три режими яскравості, сенсорне керування, акумулятор на 12 годин.</p>
    <h3>Ціна: 599 грн</h3>
    <a href="#order" class="buy-button">Замовити зараз</a>
  </div>
</section>

<section class="block">
  <h2>Відгуки покупців</h2>
  <p><strong>Олена:</strong> Дуже атмосферна лампа, дитина засинає спокійно!</p>
  <p><strong>Сергій:</strong> Виглядає супер! Доставка була за 2 дні, дякую!</p>
</section>

<section class="block">
  <h2>Про нас</h2>
  <p>Ми — український магазин затишних речей для дому. Пропонуємо стильні товари за доступними цінами. Працюємо напряму з виробниками, тому гарантуємо якість і сервіс.</p>
</section>

<section class="block" id="order">
  <h2>Оформлення замовлення</h2>
  <form action="https://formspree.io/f/your-form-id" method="POST">
    <input type="text" name="Ім'я" placeholder="Ваше ім'я" required />
    <input type="tel" name="Телефон" placeholder="Ваш номер телефону" required />
    <textarea name="Адреса" rows="3" placeholder="Місто / Нова Пошта (відділення)"></textarea>
    <button type="submit">Надіслати замовлення</button>
  </form>
</section>

<section class="block">
  <h2>Контакти</h2>
  <p>Email: support@moonglow.com.ua</p>
  <p>Телефон: +38 (093) 123-45-67</p>
  <p>Instagram: @moonglow.ua</p>
</section>

<footer>
  © 2025 MoonGlow Україна. Всі права захищені.
</footer>

</body>
</html>
