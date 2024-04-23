<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>متجر الأزياء</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="container">
        <h1>مرحبًا بك في متجر الأزياء!</h1>
        <div class="products">
            <div class="product">
                <img src="dress1.jpg" alt="فستان 1">
                <h2>فستان أنيق</h2>
                <p>سعر: $50</p>
                <button class="button">اشتري الآن</button>
            </div>
            <div class="product">
                <img src="shirt1.jpg" alt="قميص 1">
                <h2>قميص أنيق</h2>
                <p>سعر: $30</p>
                <button class="button">اشتري الآن</button>
            </div>
            <!-- يمكنك إضافة المزيد من المنتجات هنا -->
        </div>
    </div>
</body>
</html>
:root {
    --primary-color: #3498db; /* لون أزرق */
    --secondary-color: #2ecc71; /* لون أخضر */
    --text-color: #333; /* لون النص */
    --background-color: #ffffff; /* الخلفية باللون الأبيض */
}

body {
    background-color: var(--background-color);
    color: var(--text-color);
    font-family: Arial, sans-serif;
}

.container {
    max-width: 800px;
    margin: 0 auto;
    padding: 20px;
    text-align: center;
}

.products {
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    gap: 20px;
}

.product {
    width: 200px;
    border: 1px solid var(--secondary-color);
    border-radius: 5px;
    padding: 10px;
}

.product img {
    max-width: 100%;
    border-radius: 5px;
}

.button {
    background-color: var(--primary-color);
    color: #fff;
    border: none;
    padding: 5px 10px;
    border-radius: 5px;
    cursor: pointer;
}

.button:hover {
    background-color: #2980b9;
}
