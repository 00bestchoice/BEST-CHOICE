# BEST-CHOICE
<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>بيست تشويس | الصفحة الرئيسية</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <img src="logo.png" alt="Best Choice Logo" class="logo">
        <nav>
            <ul>
                <li><a href="index.html">الرئيسية</a></li>
                <li><a href="shop.html">المتجر</a></li>
                <li><a href="contact.html">تواصل معنا</a></li>
                <li><a href="#" onclick="toggleLanguage()">EN</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section class="hero">
            <h1>مرحباً بك في بيست تشويس!</h1>
            <p>منتجات عناية بجودة تستحقها.</p>
        </section>

        <section class="featured">
            <h2>منتجاتنا المميزة</h2>
            <div class="product-grid">
                <div class="product-card">كريم النهار</div>
                <div class="product-card">كريم الليل</div>
                <div class="product-card">سيروم الوجه</div>
            </div>
        </section>
    </main>

    <footer>
        <p>© 2025 Best Choice - جميع الحقوق محفوظة</p>
    </footer>

    <script>
        function toggleLanguage() {
            window.location.href = 'en/index.html';
        }
    </script>
</body>
</html>
