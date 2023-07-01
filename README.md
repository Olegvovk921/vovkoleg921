<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
  </head>
  <body>
    <table>
      <caption>
        Розклад уроків
      </caption>
      <tr>
        <th>День</th>
        <th>Час</th>
        <th>Предмет</th>
      </tr>
      <tr>
        <td>Понеділок</td>
        <td>9:00 - 10:30</td>
        <td>Математика</td>
      </tr>
      <tr>
        <td>Понеділок</td>
        <td>10:45 - 12:15</td>
        <td>Англійська мова</td>
      </tr>
      <tr>
        <td>Вівторок</td>
        <td>8:30 - 10:00</td>
        <td>Фізика</td>
      </tr>
      <tr>
        <td>Вівторок</td>
        <td>10:15 - 11:45</td>
        <td>Хімія</td>
      </tr>
      <tr>
        <td>Середа</td>
        <td>9:30 - 11:00</td>
        <td>Історія</td>
      </tr>
    </table>
    <form>
      <p>
        <label for="name">Ім'я:</label>
        <input type="text" id="name" name="name" required />
      </p>

      <p>
        <label for="surname">Прізвище:</label>
        <input type="text" id="surname" name="surname" required />
      </p>

      <p>
        <label for="email">Пошта:</label>
        <input type="email" id="email" name="email" required />
      </p>

      <p>
        <label for="phone">Телефон:</label>
        <input type="tel" id="phone" name="phone" required />
      </p>

      <p>
        <label for="comment">Коментар:</label>
        <textarea id="comment" name="comment" rows="4" required></textarea></p>
      

        <input type="submit" value="Надіслати">
      </p>
    </form>
  </body>
</html>
