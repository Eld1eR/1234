<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>BMW M5 E39 – Всё о легенде</title>
    <style>
        /* Основные стили */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background: url('https://www.teahub.io/photos/full/17-178175_carbon-fiber-wallpaper-hd.jpg') no-repeat center center fixed;
            background-size: cover;
            color: white;
            transition: background-color 0.5s ease;
        }
        header {
            background: rgba(0, 0, 0, 0.8);
            padding: 20px;
            text-align: center;
            font-size: 36px;
            text-transform: uppercase;
            animation: fadeIn 2s ease-out;
        }
        nav {
            position: fixed;
            top: 0;
            width: 100%;
            background: rgba(0, 115, 230, 0.9);
            padding: 15px;
            z-index: 1000;
            transition: background 0.3s ease;
        }
        nav a {
            color: white;
            text-decoration: none;
            padding: 10px 15px;
            margin: 5px;
            display: inline-block;
            border-radius: 5px;
            transition: background 0.3s ease, transform 0.3s ease;
        }
        nav a:hover {
            background: white;
            color: black;
            transform: scale(1.1);
        }
        .container {
            max-width: 1000px;
            margin: auto;
            padding: 80px 20px 20px;
        }
        .content {
            background: rgba(0, 0, 0, 0.8);
            padding: 20px;
            border-radius: 10px;
            margin-bottom: 20px;
            opacity: 0;
            animation: fadeIn 2s forwards;
        }
        table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 20px;
            opacity: 0;
            animation: fadeIn 2s forwards;
        }
        table, th, td {
            border: 1px solid white;
            text-align: center;
            color: white;
        }
        th {
            background: rgba(0, 115, 230, 0.8);
        }
        footer {
            text-align: center;
            padding: 10px;
            background: rgba(0, 0, 0, 0.8);
            position: absolute;
            width: 100%;
            bottom: 0;
        }

        /* Анимации */
        @keyframes fadeIn {
            0% {
                opacity: 0;
            }
            100% {
                opacity: 1;
            }
        }

        /* Темная/светлая тема */
        .dark-mode {
            background-color: #121212;
            color: white;
        }
        .light-mode {
            background-color: white;
            color: black;
        }
        .mode-toggle {
            position: fixed;
            top: 20px;
            right: 20px;
            background: rgba(0, 0, 0, 0.6);
            color: white;
            padding: 10px;
            cursor: pointer;
            border-radius: 50%;
        }
        /* Эффект параллакса для заголовков */
        .parallax {
            background-image: url('https://upload.wikimedia.org/wikipedia/commons/5/5c/BMW_M5_E39_001.jpg');
            background-attachment: fixed;
            background-size: cover;
            height: 300px;
            position: relative;
            display: flex;
            justify-content: center;
            align-items: center;
            text-align: center;
            color: white;
            font-size: 50px;
            font-weight: bold;
        }
    </style>
</head>
<body>

<!-- Темная/светлая тема переключатель -->
<div class="mode-toggle" onclick="toggleMode()">🌙</div>

<header class="parallax">
    BMW M5 E39 – Всё о легенде
</header>

<nav>
    <a href="#history">История</a>
    <a href="#specs">Характеристики</a>
    <a href="#features">Особенности</a>
    <a href="#problems">Проблемы</a>
    <a href="#tuning">Тюнинг</a>
    <a href="#comparison">Сравнение</a>
</nav>
<div class="container">

    <!-- История -->
    <div class="content" id="history">
        <h2>История BMW M5 E39</h2>
        <p>BMW M5 E39 был первым M5 с V8 двигателем. В 1998 году он установил новые стандарты для спортивных седанов, сочетая мощность и комфорт.</p>
        <p>Двигатель S62 был выдающимся на момент выхода, с мощностью 400 л.с. и крутящим моментом 500 Нм. Автомобиль мог разгоняться до 100 км/ч за 4.8 секунды, что делало его одним из самых быстрых седанов того времени.</p>
        <p>В 2003 году выпуск был завершён, и на тот момент автомобиль стал культовым среди поклонников BMW.</p>
    </div>

    <!-- Характеристики -->
    <div class="content" id="specs">
        <h2>Технические характеристики</h2>
        <table>
            <tr>
                <th>Характеристика</th><th>Значение</th>
            </tr>
            <tr>
                <td>Двигатель</td><td>4.9L V8 (S62)</td>
            </tr>
            <tr>
                <td>Мощность</td><td>400 л.с.</td>
            </tr>
            <tr>
                <td>Крутящий момент</td><td>500 Нм</td>
            </tr>
            <tr>
                <td>Разгон 0-100 км/ч</td><td>4.8 сек</td>
            </tr>
            <tr>
                <td>Максимальная скорость</td><td>250 км/ч</td>
            </tr>
            <tr>
                <td>Коробка передач</td><td>6-ступенчатая механика</td>
            </tr>
            <tr>
                <td>Привод</td><td>Задний</td>
            </tr>
        </table>
    </div>

    <!-- Особенности -->
    <div class="content" id="features">
        <h2>Особенности BMW M5 E39</h2>
        <ul>
            <li>Первый M5 с 4.9-литровым V8 двигателем (S62), который установил новые стандарты производительности.</li>
            <li>Роскошный интерьер с кожаным салоном, системой климат-контроля и регулируемыми сиденьями.</li>
            <li>Отличная управляемость, даже при таких мощных характеристиках, благодаря улучшенной подвеске и усиленному кузову.</li>
            <li>Идеальная сбалансированность между спортивной динамикой и комфортом для повседневных поездок.</li>
        </ul>
    </div>

    <!-- Проблемы -->
    <div class="content" id="problems">
        <h2>Проблемы BMW M5 E39</h2>
        <ul>
            <li>Двигатель S62 подвержен проблемам с цепью ГРМ, что может привести к дорогостоящим ремонтам.</li>
            <li>Высокие затраты на обслуживание из-за дорогих запчастей и сложности конструкции.</li>
            <li>Перегрев трансмиссии в старых моделях, что также может вызвать поломки коробки передач.</li>
            <li>Может возникать коррозия кузова, особенно в местах, где была произведена некачественная покраска.</li>
        </ul>
    </div>

    <!-- Тюнинг -->
    <div class="content" id="tuning">
        <h2>Тюнинг BMW M5 E39</h2>
        <p>BMW M5 E39 является популярным автомобилем для тюнинга, и есть множество улучшений, которые владельцы могут внести:</p>
        <ul>
            <li>Установка более производительного турбонаддува для увеличения мощности.</li>
            <li>Замена подвески на более спортивную для улучшения управляемости.</li>
            <li>Модификация выхлопной системы для улучшения звука и производительности.</li>
            <li>Установка карбоновых деталей для снижения веса автомобиля и улучшения аэродинамики.</li>
        </ul>
    </div>

    <!-- Сравнение -->
    <div class="content" id="comparison">
        <h2>Сравнение с конкурентами</h2>
        <table>
            <tr>
                <th>Модель</th><th>Мощность</th><th>Разгон 0-100 км/ч</th><th>Макс. скорость</th>
            </tr>
            <tr>
                <td><strong>BMW M5 E39</strong></td><td>400 л.с.</td><td>4.8 сек</td><td>250 км/ч</td>
            </tr>
            <tr>
                <td>Mercedes-Benz E55 AMG (W210)</td><td>354 л.с.</td><td>5.4 сек</td><td>250 км/ч</td>
            </tr>
            <tr>
                <td>Audi S6 (C5)</td><td>340 л.с.</td><td>5.7 сек</td><td>250 км/ч</td>
            </tr>
        </table>
    </div>

    <div class="gallery">
    <img src="https://assets.avtocod.ru/storage/images/bmw-e39-10-min.jpg" alt="BMW M5 E39">
    <img src="https://st3.depositphotos.com/27209332/36552/i/450/depositphotos_365527008-stock-photo-quezon-city-june-bmw-528.jpg" alt="BMW M5 E39 вид сбоку">
    <img src="https://content.onliner.by/news/1100x5616/f1bbbc74a24b566b860b85dd8e102cc1.jpeg" alt="Салон BMW M5 E39">
</div>

<style>
    .gallery {
        display: flex;
        justify-content: center;
        gap: 10px;
        margin: 20px auto;
        max-width: 900px;
    }
    .gallery img {
        width: 30%;
        border-radius: 10px;
        transition: transform 0.3s;
    }
    .gallery img:hover {
        transform: scale(1.1);
    }
</style>


</div>

</body>
</html>
