!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>بنر متجر الأزياء</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="banner">
        <h1>اكتشف مجموعتنا الجديدة!</h1>
        <p>تسوق الآن واحصل على خصم 20% على كل المنتجات الجديدة</p>
        <button class="button">تسوق الآن</button>
    </div>
</body>
</html>
    background-image: url('fashion-banner.jpg'); /* تغيير الصورة الخلفية */
    background-size: cover;
    background-position: center;
    text-align: center;
    color: #fff;
    padding: 100px 0;
}

.banner-content {
    max-width: 600px;
    margin: 0 auto;
}

.banner h1 {
    font-size: 36px;
    margin-bottom: 20px;
}

.banner p {
    font-size: 18px;
    margin-bottom: 30px;
}

.button {
    background-color: #3498db;
    color: #fff;
    border: none;
    padding: 10px 20px;
    font-size: 16px;
    cursor: pointer;
    border-radius: 5px;
}

.button:hover {
    background-color: #2980b9;
}
