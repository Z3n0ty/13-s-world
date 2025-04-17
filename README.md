# 13-s-world 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>3D E-commerce Store</title>
    <style>
        body {
            margin: 0;
            background-color: #121212;
            font-family: Arial, sans-serif;
            color: #fff;
            overflow: hidden;
        }
        .hero {
            position: relative;
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            background-color: #1d1d1d;
        }
        .hero .shop-btn {
            position: absolute;
            bottom: 20px;
            left: 50%;
            transform: translateX(-50%);
            padding: 15px 30px;
            background-color: #ff0066;
            color: white;
            font-size: 18px;
            border-radius: 5px;
            cursor: pointer;
            border: none;
        }
        .product-container {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin-top: 50px;
        }
        .product {
            width: 200px;
            height: 300px;
            background-color: #333;
            border-radius: 10px;
            cursor: pointer;
            transition: all 0.3s ease;
            overflow: hidden;
        }
        .product img {
            width: 100%;
            height: 100%;
            border-radius: 10px;
            
