
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

.product {
    position: absolute;
    width: 300px;
}

.left { left: 40px; top: 80px; }
.right { right: 40px; top: 80px; }
.bottom { left: 50%; bottom: 120px; transform: translateX(-50%); }

.product img {
    width: 100%;
    border-radius: 12px;
    box-shadow: 0 4px 10px rgba(0,0,0,0.2);
    cursor: pointer;
    transition: transform 0.3s;
}

.product img:hover {
    transform: scale(1.05);
}
</style>

<script>
function orderProduct(productName, imageUrl) {
    const phone = "6285655002016";
    const message =
        `Saya mau beli produk: ${productName}%0A` +
        `Gambar produk:%0A${imageUrl}`;

    const waUrl = `https://wa.me/${phone}?text=${message}`;
    window.open(waUrl, "_blank");
}
</script>
</head>

<body>

<div class="container">

    <div class="product left">
        <img src="blizz.jpeg"
             onclick="orderProduct('Blizzard Gecko', 'https://yourdomain.com/blizz.jpeg')">
    </div>

    <div class="product right">
        <img src="mack.jpeg"
             onclick="orderProduct('Mack Snow Gecko', 'https://yourdomain.com/mack.jpeg')">
    </div>

    <div class="product bottom">
        <img src="tremper.jpeg"
             onclick="orderProduct('Tremper Albino Gecko', 'https://yourdomain.com/tremper.jpeg')">
    </div>

</div>

</body>
