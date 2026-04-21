# myhomeworkinfo <!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <title>Виды спорта</title>

    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            background: #f4f4f4;
        }

        header {
            background: #2c3e50;
            color: white;
            padding: 20px;
            text-align: center;
            font-size: 28px;
        }

        .container {
            padding: 20px;
        }

        .sport {
            background: white;
            margin-bottom: 20px;
            padding: 15px;
            border-radius: 10px;
        }

        .sport h2 {
            color: #2c3e50;
        }

        .images {
            display: flex;
            gap: 10px;
            margin-top: 10px;
        }

        .images img {
            width: 48%;
            border-radius: 8px;
        }

        .footer {
            background: #ddd;
            padding: 20px;
            text-align: center;
        }

        .screenshots img {
            width: 45%;
            margin: 10px;
            border: 2px solid #333;
        }
    </style>
</head>

<body>

<header>
    Виды спорта
</header>

<div class="container">

    <!-- Футбол -->
    <div class="sport">
        <h2>Футбол</h2>
        <p>Футбол — командный вид спорта, цель которого забить мяч в ворота соперника. Это самый популярный спорт в мире.</p>

        <div class="images">
            <img src="Футбол 1.webp" alt="Футбол 1">
            <img src="Футбол 2.jpg" alt="Футбол 2">
        </div>
    </div>

    <!-- Баскетбол -->
    <div class="sport">
        <h2>Баскетбол</h2>
        <p>Баскетбол — игра, в которой команды стараются забросить мяч в кольцо соперника. Отличается динамикой и скоростью.</p>

        <div class="images">
            <img src="баскет 1.jpg" alt="Баскетбол 1">
            <img src="баскет 2.jpg" alt="Баскетбол 2">
        </div>
    </div>

    <!-- Плавание -->
    <div class="sport">
        <h2>Плавание</h2>
        <p>Плавание — вид спорта, который развивает все группы мышц и улучшает выносливость.</p>

        <div class="images">
            <img src="басик 1.jpg" alt="Плавание 1">
            <img src="басик 2.jpg" alt="Плавание 2">
        </div>
    </div>

</div>

<!-- Задание 2: скриншоты -->
<div class="footer">
    <h3>Скриншоты страницы</h3>
    <p>Ниже вставьте два скриншота:</p>

    <div class="screenshots">
        <p>📌 Первоначальный вид:</p>
        <img src="screenshot_before.png" alt="До">

        <p>📌 Текущий вид:</p>
        <img src="screenshot_after.png" alt="После">
    </div>
</div>

</body>
</html>
