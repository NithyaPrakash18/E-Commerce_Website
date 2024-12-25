<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Resto Ordering Website</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f8f8f8;
        }
        .header {
            background-color: #fff;
            padding: 20px;
            text-align: center;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }
        .header h1 {
            margin: 0;
            color: #333;
        }
        .nav {
            display: flex;
            justify-content: center;
            margin-top: 10px;
        }
        .nav a {
            margin: 0 15px;
            text-decoration: none;
            color: #333;
        }
        .container {
            padding: 20px;
            text-align: center;
        }
        .dish {
            margin: 20px 0;
        }
        .dish img {
            width: 300px;
            height: auto;
            border-radius: 10px;
        }
        .dish h2 {
            color: #333;
        }
        .dish p {
            color: #777;
        }
        .order-button {
            background-color: #007bff;
            color: #fff;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            text-decoration: none;
        }
    </style>
</head>
<body>
    <div class="header">
        <h1>Resto</h1>
        <div class="nav">
            <a href="#">Home</a>
            <a href="#">Menu</a>
            <a href="#">Contact</a>
            <a href="#">Cart</a>
        </div>
    </div>
    <div class="container">
        <div class="dish">
            <img src="fc.jpg" alt="Fried Chicken">
            <h2>Fried Chicken</h2>
            <p>Lorem Ipsum Dolor Sit Amet Consectetur Adipisicing Elit. Sit Natus Dolor Cumque?</p>
            <a href="#" class="order-button">Order Now</a>
        </div>
        <div class="dish">
            <img src="Tc.jp.jpg" alt="Grilled Chicken">
            <h2>Grilled Chicken</h2>
            <p>Lorem Ipsum Dolor Sit Amet Consectetur Adipisicing Elit. Sit Natus Dolor Cumque?</p>
            <a href="#" class="order-button">Order Now</a>
        </div>
        <div class="dish">
            <img src="bb.jpg" alt="BBQ Chicken">
            <h2>BBQ Chicken</h2>
            <p>Lorem Ipsum Dolor Sit Amet Consectetur Adipisicing Elit. Sit Natus Dolor Cumque?</p>
            <a href="#" class="order-button">Order Now</a>
        </div>
    </div>
</body>
</html>
