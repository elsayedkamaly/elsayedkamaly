## Hi there 👋

<!--
**elsayedkamaly/elsayedkamaly** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>أبو علي للتسويق العقاري</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            color: #333;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #007BFF;
            color: white;
            padding: 20px;
            text-align: center;
        }
        nav {
            background-color: #333;
            padding: 10px;
            text-align: center;
        }
        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
        }
        section {
            padding: 20px;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
        .chatbot {
            position: fixed;
            bottom: 20px;
            right: 20px;
            background-color: #007BFF;
            color: white;
            padding: 10px;
            border-radius: 50%;
            cursor: pointer;
        }
    </style>
</head>
<body>

    <!-- Header -->
    <header>
        <h1>أبو علي للتسويق العقاري</h1>
        <p>الحلول الذكية لعقاراتك</p>
    </header>

    <!-- Navigation -->
    <nav>
        <a href="#about">من نحن</a>
        <a href="#services">خدماتنا</a>
        <a href="#properties">العقارات المتاحة</a>
        <a href="#contact">اتصل بنا</a>
    </nav>

    <!-- About Us Section -->
    <section id="about">
        <h2>من نحن</h2>
        <p>أبو علي للتسويق العقاري شركة رائدة في مجال التسويق العقاري، نستخدم أحدث تقنيات الذكاء الاصطناعي لتوفير حلول مبتكرة لعملائنا.</p>
    </section>

    <!-- Services Section -->
    <section id="services">
        <h2>خدماتنا</h2>
        <ul>
            <li>بيع العقارات</li>
            <li>شراء العقارات</li>
            <li>إدارة العقارات</li>
            <li>استشارات عقارية</li>
        </ul>
    </section>

    <!-- Properties Section -->
    <section id="properties">
        <h2>العقارات المتاحة</h2>
        <p>استخدم الذكاء الاصطناعي للعثور على العقار المثالي.</p>
        <!-- يمكن إضافة قائمة عقارات هنا -->
    </section>

    <!-- Contact Section -->
    <section id="contact">
        <h2>اتصل بنا</h2>
        <p>هاتف: 90921773</p>
        <p>البريد الإلكتروني: info@abuali-realestate.com</p>
        <form>
            <label for="name">الاسم:</label>
            <input type="text" id="name" name="name" required>
            <label for="email">البريد الإلكتروني:</label>
            <input type="email" id="email" name="email" required>
            <label for="message">الرسالة:</label>
            <textarea id="message" name="message" required></textarea>
            <button type="submit">إرسال</button>
        </form>
    </section>

    <!-- Footer -->
    <footer>
        <p>© 2023 أبو علي للتسويق العقاري. جميع الحقوق محفوظة.</p>
    </footer>

    <!-- Chatbot -->
    <div class="chatbot" onclick="openChat()">💬</div>

    <script>
        function openChat() {
            alert("مرحبًا! كيف يمكنني مساعدتك اليوم؟");
        }
    </script>

</body>
</html>
