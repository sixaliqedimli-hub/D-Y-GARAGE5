<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <title>D-Y GARAGE</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, sans-serif;
            background: #0f0f0f;
            color: white;
        }

        header {
            background: linear-gradient(rgba(0,0,0,0.7), rgba(0,0,0,0.7)),
            url('https://images.unsplash.com/photo-1503376780353-7e6692767b70');
            background-size: cover;
            background-position: center;
            height: 100vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
        }

        h1 {
            font-size: 60px;
            color: #ff3c00;
        }

        header p {
            margin-top: 15px;
            font-size: 20px;
            color: #ccc;
        }

        .btn {
            margin-top: 20px;
            padding: 14px 30px;
            background: #25D366;
            color: white;
            text-decoration: none;
            border-radius: 8px;
            font-weight: bold;
            display: inline-block;
            transition: 0.3s;
        }

        .btn:hover {
            transform: scale(1.1);
        }

        section {
            padding: 60px 20px;
            text-align: center;
        }

        .services {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
            margin-top: 30px;
        }

        .card {
            background: #1a1a1a;
            padding: 25px;
            width: 280px;
            border-radius: 12px;
            transition: 0.3s;
        }

        .card:hover {
            transform: translateY(-10px);
            background: #222;
        }

        footer {
            background: black;
            padding: 20px;
            text-align: center;
            color: #777;
        }

        @media (max-width: 768px) {
            h1 {
                font-size: 40px;
            }

            header {
                height: 80vh;
            }
        }
    </style>
</head>
<body>

<header>
    <h1>D-Y GARAGE</h1>
    <p>Профессиональный автосервис и тюнинг</p>

    <a href="https://wa.me/994993998272?text=Здравствуйте,%20хочу%20купить"
       target="_blank"
       class="btn">
       Купить
    </a>
</header>

<section>
    <h2>Наши услуги</h2>
    <div class="services">
        <div class="card">
            <h3>Диагностика</h3>
            <p>Компьютерная проверка автомобиля</p>
        </div>

        <div class="card">
            <h3>Тюнинг</h3>
            <p>Улучшение мощности и внешнего вида</p>
        </div>

        <div class="card">
            <h3>Ремонт</h3>
            <p>Качественный ремонт любых авто</p>
        </div>
    </div>
</section>

<footer>
    © 2026 D-Y GARAGE | Все права защищены
</footer>

</body>
</html>
