<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Shop</title>
    <style>
        body { font-family: Arial, sans-serif; text-align: center; }
        .product { display: inline-block; margin: 20px; padding: 10px; border: 1px solid #ddd; }
        .product img { width: 150px; height: 150px; }
        .product button { background: green; color: white; border: none; padding: 8px; cursor: pointer; }
    </style>
</head>
<body>
    <h1>Welcome to My Shop</h1>
    <div class="product">
        <img src="https://via.placeholder.com/150" alt="Product 1">
        <h2>Product 1</h2>
        <p>$10.00</p>
        <button onclick="addToCart('Product 1', 10)">Add to Cart</button>
    </div>

    <div class="product">
        <img src="https://via.placeholder.com/150" alt="Product 2">
        <h2>Product 2</h2>
        <p>$20.00</p>
        <button onclick="addToCart('Product 2', 20)">Add to Cart</button>
    </div>

    <h2>🛒 Shopping Cart</h2>
    <ul id="cart"></ul>

    <script>
        function addToCart(name, price) {
            const cart = document.getElementById("cart");
            const item = document.createElement("li");
            item.textContent = `${name} - $${price}`;
            cart.appendChild(item);
        }
    </script>
</body>
</html>- 👋 Hi, I’m @slvncrzngl
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
slvncrzngl/slvncrzngl is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
