<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>الهندي لمواد البناء</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            color: #333;
            line-height: 1.6;
        }
        header {
            background-color: #4CAF50;
            color: #fff;
            padding: 10px 0;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #333;
        }
        nav a {
            color: #fff;
            padding: 10px 20px;
            text-decoration: none;
            transition: background 0.3s;
        }
        nav a:hover {
            background-color: #4CAF50;
        }
        .container {
            max-width: 1000px;
            margin: auto;
            overflow: hidden;
            padding: 0 20px;
        }
        .products {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            margin-top: 20px;
        }
        .product {
            background: #fff;
            padding: 20px;
            border: 1px solid #ccc;
            flex-basis: calc(33.333% - 20px);
            box-sizing: border-box;
            transition: box-shadow 0.3s;
        }
        .product:hover {
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }
        .product img {
            max-width: 100%;
            height: auto;
        }
        .product h3 {
            font-size: 1.2em;
        }
        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px 0;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>الهندي لمواد البناء</h1>
        <p>كل ما تحتاجه للبناء في مكان واحد</p>
    </header>

    <nav>
        <a href="#home">الرئيسية</a>
        <a href="#products">المنتجات</a>
        <a href="#about">معلومات عنا</a>
        <a href="#contact">اتصل بنا</a>
    </nav>

    <div class="container">
        <section id="products">
            <h2>منتجاتنا</h2>
            <div class="products">
                <div class="product">
                    <img src="cement.jpg" alt="أسمنت">
                    <h3>أسمنت</h3>
                    <p>أفضل أنواع الأسمنت لجميع احتياجات البناء.</p>
                </div>
                <div class="product">
                    <img src="bricks.jpg" alt="طوب">
                    <h3>طوب</h3>
                    <p>طوب عالي الجودة لضمان متانة البناء.</p>
                </div>
                <div class="product">
                    <img src="sand.jpg" alt="رمل">
                    <h3>رمل</h3>
                    <p>رمل نقي لاستخدامات متنوعة في أعمال البناء.</p>
                </div>
            </div>
        </section>

        <section id="about">
            <h2>معلومات عنا</h2>
            <p>نحن نقدم مواد بناء عالية الجودة بأسعار منافسة. هدفنا هو توفير كافة المواد اللازمة لإنشاء مشاريعك بسلاسة وكفاءة.</p>
        </section>

        <section id="contact">
            <h2>اتصل بنا</h2>
            <p>للاستفسار عن المنتجات أو الطلبات، يمكنكم التواصل معنا عبر الهاتف أو البريد الإلكتروني.</p>
            <p>الهاتف: 123-456-7890</p>
            <p>البريد الإلكتروني: info@buildingmaterials.com</p>
        </section>
    </div>

    <footer>
        <p>جميع الحقوق محفوظة &copy; 2024 الهندي لمواد البناء</p>
    </footer>
</body>
</html>
