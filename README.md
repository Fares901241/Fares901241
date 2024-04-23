<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>متجر الأزياء</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="container">
            <h1>متجر الأزياء</h1>
            <nav>
                <ul>
                    <li><a href="#">الرئيسية</a></li>
                    <li><a href="#">المنتجات</a></li>
                    <li><a href="#">حولنا</a></li>
                    <li><a href="#">اتصل بنا</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <main>
        <section class="products">
            <div class="container">
                <h2>أحدث المنتجات</h2>
                <div class="product">
                    <img src="dress.jpg" alt="فستان رائع">
                    <h3>فستان رائع</h3>
                    <p>السعر: $50</p>
                    <button>اشتري الآن</button>
                </div>
                <div class="product">
                    <img src="shirt.jpg" alt="قميص أنيق">
                    <h3>قميص أنيق</h3>
                    <p>السعر: $30</p>
                    <button>اشتري الآن</button>
                </div>
                <!-- يمكنك إضافة المزيد من المنتجات هنا -->
            </div>
        </section>
    </main>

    <footer>
        <div class="container">
            <p>جميع الحقوق محفوظة &copy; 2024 متجر الأزياء</p>
        </div>
    </footer>
</body>
</html>
/* إعدادات عامة */
body {
    margin: 0;
    font-family: Arial, sans-serif;
    background-color: #f3f3f3; /* لون الخلفية */
}

.container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 0 20px;
}

/* تصميم الهيدر */
header {
    background-color: #333; /* لون الهيدر */
    color: #fff; /* لون النص */
    padding: 20px 0;
}

header h1 {
    margin: 0;
}

nav ul {
    list-style-type: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin-right: 20px;
}

nav ul li a {
    color: #fff; /* لون الروابط */
    text-decoration: none;
}

/* تصميم المنتجات */
.products {
    padding: 50px 0;
}

.products h2 {
    text-align: center;
    color: #333; /* لون النص */
}

.product {
    border: 1px solid #ccc;
    border-radius: 5px;
    padding: 20px;
    margin-bottom: 20px;
}

.product img {
    max-width: 100%;
    display: block;
    margin: 0 auto 10px;
}

.product h3 {
    text-align: center;
    color: #333; /* لون النص */
}

.product p {
    text-align: center;
    color: #777; /* لون النص */
}

.product button {
    display: block;
    margin: 0 auto;
    background-color: #3498db; /* لون الزر */
    color: #fff; /* لون النص */
    border: none;
    padding: 10px 20px;
    border-radius: 5px;
    cursor: pointer;
}

.product button:hover {
    background-color: #2980b9; /* لون الزر عند التحويم */
}

/* تصميم الفوتر */
footer {
    background-color: #333; /* لون الفوتر */
    color: #fff; /* لون النص */
    padding: 20px 0;
    text-align: center;
}
