<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>مشروع عالم الألعاب - GAME World</title>
    <link href="https://googleapis.com" rel="stylesheet">
    <style>
        :root {
            --primary-color: #6c5ce7;
            --secondary-color: #a29bfe;
            --bg-dark: #0f0c29;
            --text-light: #ffffff;
            --danger-color: #ff7675;
        }

        body {
            font-family: 'Cairo', sans-serif;
            background-color: var(--bg-dark);
            color: var(--text-light);
            margin: 0;
            padding: 0;
            scroll-behavior: smooth;
        }

        section {
            min-height: 100vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            padding: 40px;
            text-align: center;
            border-bottom: 1px solid #333;
        }

        h1, h2 {
            color: var(--secondary-color);
            margin-bottom: 20px;
        }

        .container {
            max-width: 900px;
            background: rgba(255, 255, 255, 0.05);
            padding: 30px;
            border-radius: 20px;
            backdrop-filter: blur(10px);
            box-shadow: 0 10px 30px rgba(0,0,0,0.5);
        }

        .img-placeholder {
            width: 100%;
            height: 350px;
            background: #2d3436;
            margin-bottom: 20px;
            border-radius: 15px;
            display: flex;
            align-items: center;
            justify-content: center;
            color: #636e72;
            overflow: hidden;
            position: relative;
        }

        /* لتبديل المساحات بصور حقيقية، استبدل الـ <img> بالروابط التي تريدها */
        .img-placeholder img {
            width: 100%;
            height: 100%;
            object-fit: cover;
        }

        .damage-list {
            text-align: right;
            list-style: none;
            padding: 0;
        }

        .damage-list li {
            background: rgba(255, 118, 117, 0.1);
            margin: 10px 0;
            padding: 15px;
            border-right: 5px solid var(--danger-color);
            border-radius: 5px;
        }

        .btn {
            background: var(--primary-color);
            color: white;
            padding: 12px 30px;
            text-decoration: none;
            border-radius: 25px;
            transition: 0.3s;
            margin-top: 20px;
            display: inline-block;
        }

        .btn:hover {
            transform: scale(1.05);
            background: var(--secondary-color);
        }

        footer {
            padding: 20px;
            text-align: center;
            font-size: 0.9em;
            color: #aaa;
        }
    </style>
</head>
<body>

    <!-- المشهد الأول: الافتتاحية -->
    <section id="home">
        <div class="container">
            <h1>🎮 عالم الألعاب: متعة بلا حدود</h1>
            <div class="img-placeholder">
                <!-- يمكنك وضع رابط صورة هنا -->
                <img src="https://unsplash.com" alt="Gaming Setup">
            </div>
            <p>أهلاً بكم في عالم لا يعرف المستحيل! الألعاب اليوم ليست مجرد تسلية، بل هي صناعة ترفيهية ضخمة تدمج بين الفن والتكنولوجيا.</p>
            <a href="#benefits" class="btn">اكتشف المزيد</a>
        </div>
    </section>

    <!-- المشهد الثاني: الفوائد -->
    <section id="benefits">
        <div class="container">
            <h2>لماذا نحب الألعاب؟ ✨</h2>
            <div class="img-placeholder">
                <img src="https://unsplash.com" alt="Friends Playing">
            </div>
            <p>السر يكمن في "الدوبامين"! الألعاب تعطينا شعوراً بالإنجاز عند تجاوز كل مرحلة، وتحسن مهارات التفكير السريع والتعاون مع الأصدقاء رقمياً.</p>
            <a href="#damages" class="btn">احذر من الإفراط!</a>
        </div>
    </section>

    <!-- المشهد الثالث: الأضرار -->
    <section id="damages">
        <div class="container">
            <h2 style="color: var(--danger-color);">أضرار اللعب الطويل ⚠️</h2>
            <div class="img-placeholder">
                <img src="https://unsplash.com" alt="Dark Room Gaming">
            </div>
            <ul class="damage-list">
                <li><strong>الأضرار الجسدية:</strong> آلام الظهر والرقبة، ضعف النظر، وجفاف العين نتيجة التحديق المستمر.</li>
                <li><strong>الأضرار النفسية:</strong> العزلة عن الواقع، اضطرابات النوم (الأرق)، وضعف التركيز الدراسي.</li>
                <li><strong>الإدمان الرقمي:</strong> فقدان السيطرة على الوقت مما يؤثر على جودة الحياة اليومية.</li>
            </ul>
            <a href="#tips" class="btn">كيف نلعب بذكاء؟</a>
        </div>
    </section>

    <!-- المشهد الرابع: النصيحة والختام -->
    <section id="tips">
        <div class="container">
            <h2>الاستمتاع بذكاء ✅</h2>
            <div class="img-placeholder">
                <img src="https://unsplash.com" alt="Balance Life">
            </div>
            <p>الحل ليس في المنع، بل في التوازن. ضع جدولاً زمنياً، خذ استراحة 5 دقائق كل ساعة، ولا تنسَ نشاطك البدني.</p>
            <p><strong>تذكر دائماً: أنت من يتحكم في اللعبة، فلا تجعل اللعبة تتحكم في حياتك!</strong></p>
            <a href="#home" class="btn">العودة للبداية</a>
        </div>
    </section>

    <footer>
        جميع الحقوق محفوظة - مشروع GAME الترفيهي &copy; 2024
    </footer>

</body>
</html>
