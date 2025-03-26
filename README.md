<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>BMW M5 E39 – Всё о легенде</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background: url('https://www.teahub.io/photos/full/17-178175_carbon-fiber-wallpaper-hd.jpg') no-repeat center center fixed;
            background-size: cover;
            color: white;
            transition: background-color 0.5s ease, color 0.5s ease;
        }
        header {
            background: rgba(0, 0, 0, 0.8);
            padding: 20px;
            text-align: center;
            font-size: 36px;
            text-transform: uppercase;
        }
        nav {
            position: fixed;
            top: 0;
            width: 100%;
            background: rgba(0, 115, 230, 0.9);
            padding: 15px;
            z-index: 1000;
            transition: background 0.3s ease;
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
        }
        nav a {
            color: white;
            text-decoration: none;
            padding: 10px 15px;
            margin: 5px;
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
            padding: 100px 20px 20px;
        }
        .content {
            background: rgba(0, 0, 0, 0.8);
            padding: 20px;
            border-radius: 10px;
            margin-bottom: 20px;
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
        .dark-mode {
            background-color: #121212;
            color: white;
        }
        .light-mode {
            background-color: white;
            color: black;
        }
        .gallery {
            display: flex;
            overflow-x: auto;
            padding: 20px;
            background: rgba(0, 0, 0, 0.8);
            border-radius: 10px;
            margin: 20px auto;
            max-width: 800px;
        }
        .gallery img {
            height: 200px;
            margin-right: 10px;
            border-radius: 10px;
            transition: transform 0.3s;
        }
        .gallery img:hover {
            transform: scale(1.1);
        }
    </style>
</head>
<body>
    <div class="mode-toggle" onclick="toggleMode()">🌙</div>
    <header>
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
        <div class="gallery">
            <img src="https://upload.wikimedia.org/wikipedia/commons/5/5c/BMW_M5_E39_001.jpg" alt="BMW M5 E39">
            <img src="https://upload.wikimedia.org/wikipedia/commons/8/8b/BMW_E39_M5.jpg" alt="BMW M5 E39 вид сбоку">
            <img src="https://upload.wikimedia.org/wikipedia/commons/d/df/BMW_M5_E39_Interior.jpg" alt="Салон BMW M5 E39">
        </div>
    </div>
    <footer>
        © 2025 BMW M5 E39 Fan Club
    </footer>
    <script>
        function toggleMode() {
            let body = document.body;
            let modeToggle = document.querySelector('.mode-toggle');
            let isDarkMode = body.classList.contains('dark-mode');
            
            if (isDarkMode) {
                body.classList.remove('dark-mode');
                body.classList.add('light-mode');
                modeToggle.innerText = '🌙';
                localStorage.setItem('theme', 'light');
            } else {
                body.classList.remove('light-mode');
                body.classList.add('dark-mode');
                modeToggle.innerText = '☀️';
                localStorage.setItem('theme', 'dark');
            }
        }

        window.onload = function () {
            let savedTheme = localStorage.getItem('theme');
            let body = document.body;
            let modeToggle = document.querySelector('.mode-toggle');
            
            if (savedTheme === 'dark') {
                body.classList.add('dark-mode');
                modeToggle.innerText = '☀️';
            } else {
                body.classList.add('light-mode');
                modeToggle.innerText = '🌙';
            }
        }
    </script>
</body>
</html>

