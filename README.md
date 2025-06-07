# Kanen.com
Kolkata
<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Простой сайт с буквами</title>
  <style>
    body {
      font-family: 'Arial', sans-serif;
      background: #f5f5f5;
      margin: 0;
      padding: 20px;
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 15px;
    }
    .letter {
      width: 80px;
      height: 80px;
      background: white;
      border-radius: 10px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 48px;
      cursor: default;
      user-select: none;
      transition: transform 0.2s ease;
    }
    .letter:hover {
      transform: scale(1.2);
      box-shadow: 0 4px 12px rgba(0,0,0,0.2);
    }
  </style>
</head>
<body>
  <div class="letter">А</div>
  <div class="letter">Б</div>
  <div class="letter">В</div>
  <div class="letter">Г</div>
  <div class="letter">Д</div>
  <div class="letter">Е</div>
  <div class="letter">Ё</div>
  <div class="letter">Ж</div>
  <div class="letter">З</div>
  <div class="letter">И</div>
  <div class="letter">Й</div>
  <div class="letter">К</div>
  <div class="letter">Л</div>
  <div class="letter">М</div>
  <div class="letter">Н</div>
  <div class="letter">О</div>
  <div class="letter">П</div>
  <div class="letter">Р</div>
  <div class="letter">С</div>
  <div class="letter">Т</div>
  <div class="letter">У</div>
  <div class="letter">Ф</div>
  <div class="letter">Х</div>
  <div class="letter">Ц</div>
  <div class="letter">Ч</div>
  <div class="letter">Ш</div>
  <div class="letter">Щ</div>
  <div class="letter">Ъ</div>
  <div class="letter">Ы</div>
  <div class="letter">Ь</div>
  <div class="letter">Э</div>
  <div class="letter">Ю</div>
  <div class="letter">Я</div>
</body>
</html>
