<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>الرئيسية - S2</title>
    <style>
        /* Reset */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Tajawal', sans-serif;
            line-height: 1.6;
            background-color: #1a1a1a;
            color: #fff;
            direction: rtl;
        }

        .container {
            width: 90%;
            max-width: 1200px;
            margin: auto;
            overflow: hidden;
        }

        header {
            background: linear-gradient(135deg, #ffcc00, #ff9900);
            color: #1a1a1a;
            padding: 15px 0;
            position: sticky;
            top: 0;
            z-index: 1000;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.3);
        }

        header h1 {
            font-size: 24px;
            text-transform: uppercase;
            letter-spacing: 1px;
            display: flex;
            align-items: center;
        }

        header h1 span {
            margin-left: 10px;
        }

        nav ul {
            list-style: none;
            display: flex;
            gap: 15px;
        }

        nav ul li a {
            color: #1a1a1a;
            text-decoration: none;
            font-weight: bold;
            padding: 10px 20px;
            transition: background 0.3s ease;
        }

        nav ul li a:hover {
            background: rgba(255, 255, 255, 0.2);
            border-radius: 5px;
        }

        main {
            padding: 40px 0;
        }

        footer {
            background: #ffcc00;
            color: #1a1a1a;
            text-align: center;
            padding: 20px 0;
        }

        footer p {
            font-size: 14px;
        }

        /* Hero Section */
        .hero {
            background: url('https://via.placeholder.com/1920x600') no-repeat center center/cover;
            height: 500px;
            position: relative;
            color: #fff;
            text-align: center;
            display: flex;
            justify-content: center;
            align-items: center;
        }

        .hero::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background: rgba(0, 0, 0, 0.5);
        }

        .hero h2 {
            font-size: 48px;
            margin-bottom: 10px;
        }

        .btn {
            display: inline-block;
            padding: 10px 20px;
            background: #ff9900;
            color: #1a1a1a;
            text-decoration: none;
            border-radius: 5px;
            font-weight: bold;
            transition: transform 0.3s ease, background 0.3s ease;
        }

        .btn:hover {
            background: #e68a00;
            transform: scale(1.05);
        }
    </style>
</head>
<body>
    <!-- Header -->
    <header>
        <div class="container">
            <nav>
                <h1>
                    <span class="fox-logo"></span>
                    <span>S2</span>
                </h1>
                <ul>
                    <li><a href="index.html">الرئيسية</a></li>
                    <li><a href="products.html">المنتجات</a></li>
                    <li><a href="spare-parts.html">قطع الغيار</a></li>
                    <li><a href="rental.html">تأجير المعدات</a></li>
                    <li><a href="login.html">تسجيل الدخول</a></li>
                    <li><a href="register.html">التسجيل</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="hero">
        <div class="hero-content">
            <h2>مرحبًا بك في S2</h2>
            <p>نقدم أفضل المعدات الثقيلة وقطع الغيار للبيع والشراء بأسعار تنافسية.</p>
            <a href="products.html" class="btn">تصفح المعدات</a>
            <a href="rental.html" class="btn">استئجار معدات</a>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <div class="container">
            <p>&copy; 2023 S2. جميع الحقوق محفوظة.</p>
        </div>
    </footer>
</body>
</html>
