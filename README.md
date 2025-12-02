<!DOCTYPE html>
<html lang="fa" dir="rtl">
<head>
    <meta charset="UTF-8">
    <title>مهدی الکتریسیته</title>
    <style>
        body {
            font-family: sans-serif;
            background: #f2f2f2;
            margin: 0;
        }
        header {
            background: #1a73e8;
            padding: 20px;
            color: white;
            text-align: center;
            font-size: 26px;
            font-weight: bold;
        }
        .creator {
            text-align: center;
            margin-top: -10px;
            color: #e0e0e0;
        }
        .products {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
            gap: 20px;
            padding: 20px;
        }
        .card {
            background: white;
            padding: 15px;
            border-radius: 12px;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
            text-align: center;
        }
        .card img {
            width: 100%;
            height: 150px;
            object-fit: contain;
        }
        .buy-btn {
            background: #1a73e8;
            color: white;
            padding: 10px 15px;
            border: none;
            border-radius: 8px;
            margin-top: 10px;
            cursor: pointer;
        }
        footer {
            background: #222;
            color: white;
            padding: 15px;
            text-align: center;
            margin-top: 20px;
        }
    </style>
</head>

<body>

<header>مهدی الکتریسیته</header>
<div class="creator">سازنده: مهدی حاجی</div>

<section class="products">

    <div class="card">
        <img src="https://upload.wikimedia.org/wikipedia/commons/3/3f/Resistor.jpg" alt="مقاومت">
        <h3>مقاومت 10kΩ</h3>
        <p>قیمت: 2000 تومان</p>
        <button class="buy-btn">خرید</button>
    </div>

    <div class="card">
        <img src="https://upload.wikimedia.org/wikipedia/commons/5/5e/LED%2C_5mm%2C_red.jpg" alt="LED">
        <h3>ال ای دی ۵ میلی‌متری</h3>
        <p>قیمت: 1500 تومان</p>
        <button class="buy-btn">خرید</button>
    </div>

    <div class="card">
        <img src="https://upload.wikimedia.org/wikipedia/commons/0/0e/Arduino_Uno_-_R3.jpg" alt="Arduino">
        <h3>برد آردوینو UNO</h3>
        <p>قیمت: 320000 تومان</p>
        <button class="buy-btn">خرید</button>
    </div>

</section>

<footer>
    تمام حقوق برای «مهدی الکتریسیته» محفوظ است.
</footer>

</body>
</html>
