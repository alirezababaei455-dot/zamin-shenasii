# zamin-shenasii
<!DOCTYPE html>
<html lang="fa">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>سایت شخصی من</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>به سایت من خوش آمدید</h1>
        <nav>
            <ul>
                <li><a href="#about">درباره من</a></li>
                <li><a href="#gallery">گالری</a></li>
                <li><a href="#files">فایل‌ها</a></li>
                <li><a href="#contact">تماس</a></li>
            </ul>
        </nav>
    </header>

    <section id="about">
        <h2>درباره من</h2>
        <p>اینجا می‌توانید درباره خودتان بنویسید.</p>
    </section>

    <section id="gallery">
        <h2>گالری تصاویر</h2>
        <div class="images">
            <img src="images/sample1.jpg" alt="نمونه 1">
            <img src="images/sample2.jpg" alt="نمونه 2">
        </div>
    </section>

    <section id="files">
        <h2>فایل‌ها</h2>
        <ul>
            <li><a href="files/sample.pdf" target="_blank">دانلود PDF نمونه</a></li>
        </ul>
    </section>

    <section id="contact">
        <h2>تماس با من</h2>
        <p>ایمیل: example@example.com</p>
    </section>

    <footer>
        <p>© 2025 تمام حقوق محفوظ است</p>
    </footer>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    margin: 0;
    padding: 0;
    background-color: #f5f5f5;
    color: #333;
}

header {
    background-color: #4CAF50;
    color: white;
    padding: 20px 0;
    text-align: center;
}

nav ul {
    list-style: none;
    padding: 0;
    margin: 10px 0 0 0;
    display: flex;
    justify-content: center;
}

nav ul li {
    margin: 0 15px;
}

nav ul li a {
    color: white;
    text-decoration: none;
    font-weight: bold;
}

section {
    padding: 40px 20px;
    text-align: center;
    background-color: white;
    margin: 20px;
    border-radius: 10px;
    box-shadow: 0 0 10px rgba(0,0,0,0.1);
}

.images img {
    width: 200px;
    margin: 10px;
    border-radius: 10px;
}

footer {
    text-align: center;
    padding: 20px;
    background-color: #333;
    color: white;
}
<section id="about">
    <h2>درباره من</h2>
    <p>اینجا می‌توانید درباره خودتان بنویسید.</p>
</section>

<section id="gallery">
    <h2>گالری تصاویر</h2>
    <div class="images">
        <img src="images/sample1.jpg" alt="نمونه 1">
        <img src="images/sample2.jpg" alt="نمونه 2">
    </div>
</section>

<section id="files">
    <h2>فایل‌ها</h2>
    <ul>
        <li><a href="files/sample.pdf" target="_blank">دانلود PDF نمونه</a></li>
    </ul>
</section>

<section id="contact">
    <h2>تماس با من</h2>
    <p>ایمیل: example@example.com</p>
</section>

<footer>
    <p>© 2025 تمام حقوق محفوظ است</p>
</footer>
