<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>موقع الجمال الذكي - الصفحة الرئيسية</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <!-- 1. رأس الصفحة واللوجو وقائمة التنقل -->
    <header>
        <div class="logo">
            <!-- اللوجو الخاص بالموقع -->
            <img src="images/logo.png" alt="شعار موقع المكياج والسكن كير" width="120">
        </div>
        <nav>
            <ul>
                <li><a href="index.html" class="active">الرئيسية</a></li>
                <li><a href="about.html">عن الموقع والأهداف</a></li>
                <li><a href="features.html">خدمات الذكاء الاصطناعي</a></li>
                <li><a href="products.html">المنتجات والتسوق</a></li>
                <li><a href="contact.html">تواصل معنا</a></li>
            </ul>
        </nav>
    </header>

    <!-- 2. القسم الرئيسي (Hero Section مع صورة) -->
    <section class="hero">
        <div class="hero-content">
            <h1>اكتشفي جمالكِ مع روتين العناية المخصص بالذكاء الاصطناعي</h1>
            <p>موقعنا يدمج بين أحدث تقنيات الجمال والعناية بالبشرة لتقديم تجربة تسوق فريدة ومخصصة لكِ وحدكِ.</p>
            <a href="features.html" class="cta-btn">جربي الروتين الآن</a>
        </div>
        <div class="hero-image">
            <img src="images/skincare-hero.jpg" alt="منتجات مكياج وعناية بالبشرة">
        </div>
    </section>

    <!-- 3. قسم الفيديو الترويجي -->
    <section class="video-section">
        <h2>تعرفي على تجربتنا التفاعلية</h2>
        <video controls width="600">
            <source src="videos/promo.mp4" type="video/mp4">
            متصفحك لا يدعم عرض الفيديو.
        </video>
    </section>

    <!-- 4. قسم الصوت (موسيقى هادئة) -->
    <section class="audio-section">
        <h2>استمتعي بتجربة استرخاء أثناء تصفحك</h2>
        <audio controls>
            <source src="audio/relaxing-bg.mp3" type="audio/mpeg">
            متصفحك لا يدعم تشغيل الملف الصوتي.
        </audio>
    </section>

    <!-- تذييل الصفحة -->
    <footer>
        <p>جميع الحقوق محفوظة - مشروع مقرر تطوير واجهات الويب &copy; 2026</p>
    </footer>

</body>
</html>
