
<head>
    <meta charset="UTF-8">
    <title>Gecko Store</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
        }

        .container {
            width: 100%;
            height: 100vh;
            position: relative;
            padding: 40px;
            box-sizing: border-box;
        }

        .image-left {
            position: absolute;
            left: 40px;
            top: 80px;
            width: 300px;
        }

        .image-right {
            position: absolute;
            right: 40px;
            top: 80px;
            width: 300px;
        }

        .image-bottom {
            position: absolute;
            left: 50%;
            bottom: 120px;
            transform: translateX(-50%);
            width: 320px;
        }

        a img {
            width: 100%;
            border-radius: 12px;
            box-shadow: 0 4px 10px rgba(0,0,0,0.2);
            cursor: pointer;
            transition: transform 0.3s;
        }

        a img:hover {
            transform: scale(1.05);
        }

        .order-button {
            position: absolute;
            bottom: 40px;
            left: 50%;
            transform: translateX(-50%);
            padding: 15px 30px;
            background-color: #25D366;
            color: white;
            text-decoration: none;
            font-size: 18px;
            font-weight: bold;
            border-radius: 30px;
        }

        .order-button:hover {
            background-color: #1ebe5d;
        }
    </style>
</head>
<body>

<div class="container">

    <div class="image-left">
        <a href="https://wa.me/6285655002016?text=saya%20mau%20order%20min" target="_blank">
            <img src="blizz..jpeg" alt="Gecko Kiri">
        </a>
    </div>

    <div class="image-right">
        <a href="https://wa.me/6285655002016?text=saya%20mau%20order%20min" target="_blank">
            <img src="mack.jpeg" alt="Gecko Kanan">
        </a>
    </div>

    <div class="image-bottom">
        <a href="https://wa.me/6285655002016?text=saya%20mau%20order%20min" target="_blank">
            <img src="tremper.jpeg" alt="Gecko Bawah">
        </a>
    </div>

    <a 
        class="order-button" 
        href="https://wa.me/6285655002016?text=saya%20mau%20order%20min"
        target="_blank">
        Order via WhatsApp
    </a>

</div>

</body>

