<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>مملكة أريڤانيا | ARIVANIA</title>
    <!-- استدعاء خط عربي أصيل وقوي من جوجل (Amiri / Reem Kufi) -->
    <link href="https://fonts.googleapis.com/css2?family=Amiri:wght@700&family=Reem+Kufi:wght@700&display=swap" rel="stylesheet">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            background-color: #0b0713;
            color: #ffffff;
            min-height: 100vh;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            overflow: hidden;
            position: relative;
        }
        /* إطار أحمر ملكي فاخر يحيط بالشاشة */
        body::before {
            content: '';
            position: absolute;
            top: 15px;
            left: 15px;
            right: 15px;
            bottom: 15px;
            border: 2px solid #ff2a2a;
            box-shadow: 0 0 15px rgba(255, 42, 42, 0.4);
            pointer-events: none;
            z-index: 10;
        }
        .container {
            position: relative;
            z-index: 2;
            text-align: center;
            padding: 20px;
            max-width: 600px;
            display: flex;
            flex-direction: column;
            align-items: center;
        }
        .kingdom-title {
            font-family: 'Reem Kufi', 'Amiri', serif;
            font-size: 3.2rem;
            color: #d4af37;
            margin-bottom: 35px;
            font-weight: bold;
            text-shadow: 0 0 25px rgba(212, 175, 55, 0.4);
            letter-spacing: 2px;
        }
        .verse-box {
            margin-bottom: 45px;
            padding: 15px 25px;
            border-top: 1px solid rgba(212, 175, 55, 0.3);
            border-bottom: 1px solid rgba(212, 175, 55, 0.3);
            width: 100%;
        }
        .verse {
            font-family: 'Amiri', serif;
            font-size: 1.4rem;
            color: #ffffff;
            margin-bottom: 10px;
            font-weight: 700;
            letter-spacing: 1px;
        }
        .verse-source {
            font-size: 0.95rem;
            color: #b1a9c2;
            font-family: 'Segoe UI', Tahoma, sans-serif;
        }
        .btn {
            display: inline-block;
            background: linear-gradient(135deg, #4a154b, #2b0b30);
            color: #ffffff;
            border: 1px solid #d4af37;
            padding: 14px 55px;
            border-radius: 35px;
            text-decoration: none;
            font-size: 1.15rem;
            font-weight: bold;
            box-shadow: 0 4px 20px rgba(212, 175, 55, 0.2);
            transition: all 0.3s ease;
            font-family: 'Segoe UI', Tahoma, sans-serif;
        }
        .btn:hover {
            background: linear-gradient(135deg, #5c1b5e, #3a0e41);
            box-shadow: 0 6px 25px rgba(212, 175, 55, 0.4);
            transform: translateY(-2px);
        }
    </style>
</head>
<body>

    <div class="container">
        <!-- اسم المملكة بخط عربي أصيل وقوي -->
        <h1 class="kingdom-title">مملكة أريڤانيا</h1>
        
        <!-- الآية الكريمة بخط أنيق بدون أي نصوص إضافية -->
        <div class="verse-box">
            <div class="verse">وَتَعَاوَنُوا عَلَى الْبِرِّ وَالتَّقْوَىٰ</div>
            <div class="verse-source">سورة المائدة - 2</div>
        </div>

        <!-- زر دخول المملكة -->
        <a href="#" class="btn" onclick="alert('قريباً سيتم افتتاح أبواب قاعات المملكة!')">دخول المملكة</a>
    </div>

</body>
</html>
