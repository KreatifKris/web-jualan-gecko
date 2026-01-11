

<head>
    <meta charset="UTF-8">
    <title>Gecko Store</title>

    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
        }

        h1 {
            text-align: center;
            margin: 30px 0;
        }

        .container {
            display: flex;
            justify-content: center;
            gap: 30px;
            flex-wrap: wrap;
            padding: 20px;
        }

        .product-card {
            background: white;
            width: 300px;
            border-radius: 14px;
            box-shadow: 0 4px 10px rgba(0,0,0,0.15);
            overflow: hidden;
            text-align: center;
        }

        .product-card img {
            width: 100%;
            display: block;
        }

        .product-info {
            padding: 15px;
        }

        .product-info h2 {
            margin: 10px 0 5px;
        }

        .price {
            color: #e67e22;
            font-size: 18px;
            font-weight: bold;
            margin-bottom: 15px;
        }

        .buy-button {
            display: inline-block;
            padding: 12px 25px;
            background-color: #25D366;
            color: white;
            text-decoration: none;
            border-radius: 25px;
            font-weight: bold;
        }

        .buy-button:hover {
            background-color: #1ebe5d;
        }
    </style>
</head>

<body>

<h1>Gecko Store</h1>

<div class="container">

    <!-- PRODUCT 1 -->
    <div class="product-card">
        <img src="blizz.jpeg" alt="Gecko Blizzard">
        <div class="product-info">
            <h2>Gecko Blizzard</h2>
            <div class="price">Rp 1.500.000</div>
            <a class="buy-button"
               href="https://wa.me/6285655002016?text=Saya%20mau%20beli%20Gecko%20Blizzard"
               target="_blank">
                Buy via WhatsApp
            </a>
        </div>
    </div>

    <!-- PRODUCT 2 -->
    <div class="product-card">
        <img src="mack.jpeg" alt="Gecko Mack Snow">
        <div class="product-info">
            <h2>Gecko Mack Snow</h2>
            <div class="price">Rp 1.200.000</div>
            <a class="buy-button"
               href="https://wa.me/6285655002016?text=Saya%20mau%20beli%20Gecko%20Mack%20Snow"
               target="_blank">
                Buy via WhatsApp
            </a>
        </div>
    </div>

    <!-- PRODUCT 3 -->
    <div class="product-card">
        <img src="tremper.jpeg" alt="Gecko Tremper Albino">
        <div class="product-info">
            <h2>Gecko Tremper Albino</h2>
            <div class="price">Rp 1.800.000</div>
            <a class="buy-button"
               href="https://wa.me/6285655002016?text=Saya%20mau%20beli%20Gecko%20Tremper%20Albino"
               target="_blank">
                Buy via WhatsApp
            </a>
        </div>
    </div>

</div>

</body>

