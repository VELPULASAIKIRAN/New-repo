<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Chic Theme Card</title>
<style>
    body {
        font-family: Arial, sans-serif;
        background-color: #f5f5f5;
        display: flex;
        justify-content: center;
        padding: 40px;
    }
    .theme-card {
        background: white;
        border-radius: 10px;
        overflow: hidden;
        width: 400px;
        box-shadow: 0 4px 12px rgba(0,0,0,0.1);
    }
    .banner {
        position: relative;
    }
    .banner img {
        width: 100%;
        display: block;
    }
    .banner-text {
        position: absolute;
        top: 20px;
        left: 20px;
        color: black;
        font-size: 28px;
        font-weight: bold;
    }
    .banner-sub {
        position: absolute;
        top: 60px;
        left: 20px;
        font-size: 18px;
        color: black;
    }
    .shop-btn {
        position: absolute;
        top: 100px;
        left: 20px;
        background-color: black;
        color: white;
        padding: 8px 14px;
        border: none;
        font-size: 14px;
        cursor: pointer;
    }
    .nav-bar {
        background-color: black;
        color: white;
        padding: 8px;
        display: flex;
        justify-content: center;
        gap: 20px;
        font-size: 14px;
    }
    .product-row {
        display: flex;
        justify-content: space-between;
        padding: 10px;
        gap: 5px;
    }
    .product-row img {
        width: 24%;
        border-radius: 4px;
    }
    .card-content {
        padding: 20px;
        text-align: center;
    }
    .card-content h2 {
        margin: 0;
        font-size: 22px;
    }
    .apply-btn {
        margin-top: 20px;
        border: 2px solid #007bff;
        background: none;
        color: #007bff;
        padding: 8px 20px;
        font-size: 14px;
        border-radius: 6px;
        cursor: pointer;
    }
</style>
</head>
<body>

<div class="theme-card">
    <!-- Banner -->
    <div class="banner">
        <img src="https://images.unsplash.com/photo-1602810318383-4a4e13a3b7c5" alt="Banner">
        <div class="banner-text">Chic.</div>
        <div class="banner-sub">Summer Collection</div>
        <button class="shop-btn">SHOP MENS</button>
    </div>

    <!-- Nav Bar -->
    <div class="nav-bar">
        <div>Women</div>
        <div>Men</div>
        <div>Promotions</div>
        <div>Sale</div>
        <div>Test</div>
    </div>

    <!-- Product Row -->
    <div class="product-row">
        <img src="https://images.unsplash.com/photo-1517841905240-472988babdf9" alt="Model 1">
        <img src="https://images.unsplash.com/photo-1524504388940-b1c1722653e1" alt="Model 2">
        <img src="https://images.unsplash.com/photo-1520975869010-3f83d6804e1f" alt="Model 3">
        <img src="https://images.unsplash.com/photo-1503342217505-b0a15ec3261c" alt="Model 4">
    </div>

    <!-- Content -->
    <div class="card-content">
        <h2>Chic theme</h2>
        <button class="apply-btn">Apply</button>
    </div>
</div>

</body>
</html>
