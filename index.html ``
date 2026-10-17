<!DOCTYPE html>
<html lang="ru">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Мой День Рождения 🎉</title>
<style>
  * { margin: 0; padding: 0; box-sizing: border-box; }
  body {
    font-family: 'Georgia', serif;
    background: linear-gradient(135deg, #ff9a9e 0%, #fad0c4 50%, #fbc2eb 100%);
    min-height: 100vh;
    padding: 40px 20px;
    color: #3a2a3a;
  }
  .card {
    max-width: 600px;
    margin: 0 auto;
    background: rgba(255, 255, 255, 0.95);
    border-radius: 20px;
    padding: 40px;
    box-shadow: 0 20px 60px rgba(0,0,0,0.15);
  }
  h1 {
    text-align: center;
    font-size: 2.5em;
    margin-bottom: 10px;
    color: #c2185b;
  }
  .date {
    text-align: center;
    font-size: 1.2em;
    color: #880e4f;
    margin-bottom: 30px;
  }
  .details {
    background: #fff0f5;
    padding: 20px;
    border-radius: 12px;
    margin-bottom: 30px;
    line-height: 1.7;
  }
  h2 {
    color: #c2185b;
    margin-bottom: 20px;
    border-bottom: 2px solid #fbc2eb;
    padding-bottom: 8px;
  }
  label {
    display: block;
    margin-top: 18px;
    font-weight: bold;
    color: #4a2a3a;
  }
  input[type="text"], textarea, select {
    width: 100%;
    padding: 12px;
    margin-top: 6px;
    border: 1px solid #e4a5c0;
    border-radius: 8px;
    font-size: 1em;
    font-family: inherit;
  }
  .radio-group, .check-group {
    margin-top: 8px;
  }
  .radio-group label, .check-group label {
    display: inline-block;
    margin-right: 15px;
    font-weight: normal;
    margin-top: 6px;
  }
  button {
    margin-top: 25px;
    width: 100%;
    padding: 14px;
    background: #c2185b;
    color: white;
    border: none;
    border-radius: 10px;
    font-size: 1.1em;
    cursor: pointer;
    transition: 0.2s;
  }
  button:hover { background: #880e4f; }
</style>
</head>
<body>
<div class="card">
  <h1>🎂 Приглашаю на мой День Рождения!</h1>
  <p class="date">Суббота, 15 ноября · 19:00</p>

  <div class="details">
    <strong>📍 Где:</strong> ул. Примерная, 10, кв. 25<br>
    <strong>👗 Дресс-код:</strong> свободный, но нарядно<br>
    <strong>🎁 Подарки:</strong> твоё присутствие — лучший подарок<br>
    <strong>📞 Связь:</strong> +375 XX XXX-XX-XX
  </div>

  <h2>Опрос для гостей</h2>
  <!-- Замени YOUR_FORM_ID на свой с formspree.io -->
  <form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">

    <label>Как тебя зовут?
      <input type="text" name="name" required>
    </label>

    <label>Придёшь ли ты?</label>
    <div class="radio-group">
      <label><input type="radio" name="attendance" value="Да" required> Да, конечно!</label>
      <label><input type="radio" name="attendance" value="Нет"> К сожалению, нет</label>
      <label><input type="radio" name="attendance" value="Пока не знаю"> Пока не знаю</label>
    </div>

    <label>Будешь ли пить алкоголь?</label>
    <div class="radio-group">
      <label><input type="radio" name="drinks" value="Да"> Да</label>
      <label><input type="radio" name="drinks" value="Нет"> Нет</label>
      <label><input type="radio" name="drinks" value="Чуть-чуть"> Чуть-чуть</label>
    </div>

    <label>Что предпочитаешь пить? (можно несколько)</label>
    <div class="check-group">
      <label><input type="checkbox" name="drink_type" value="Вино"> Вино</label>
      <label><input type="checkbox" name="drink_type" value="Пиво"> Пиво</label>
      <label><input type="checkbox" name="drink_type" value="Крепкий алкоголь"> Крепкий</label>
      <label><input type="checkbox" name="drink_type" value="Коктейли"> Коктейли</label>
      <label><input type="checkbox" name="drink_type" value="Соки/вода"> Соки/вода</label>
      <label><input type="checkbox" name="drink_type" value="Чай/кофе"> Чай/кофе</label>
    </div>

    <label>Есть ли пищевые ограничения или аллергии?
      <textarea name="food_restrictions" rows="2" placeholder="Вегетарианство, аллергии, непереносимость..."></textarea>
    </label>

    <label>Приведёшь ли кого-то с собой?
      <select name="plus_one">
        <option value="Нет">Нет, приду один/одна</option>
        <option value="+1">Да, +1 человек</option>
        <option value="+2">Да, +2 человека</option>
      </select>
    </label>

    <label>Пожелания или комментарии
      <textarea name="comments" rows="3" placeholder="Любимый трек на плейлист, идеи, пожелания..."></textarea>
    </label>

    <button type="submit">Отправить ответ 💌</button>
  </form>
</div>
</body>
</html>
