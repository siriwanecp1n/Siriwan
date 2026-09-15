<!DOCTYPE html>
<html lang="th">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Siriwan | Shin-chan Portfolio 🖍️</title>
    <link href="https://fonts.googleapis.com/css2?family=Mitr:wght@400;600&family=Prompt:wght@300;400;600&display=swap" rel="stylesheet">
    <style>
        * {
            box-sizing: border-box;
        }
        body {
            font-family: 'Prompt', 'Mitr', sans-serif;
            background-color: #fef08a; /* สีเหลืองชินจัง */
            background-image: radial-gradient(#fde047 15%, transparent 16%);
            background-size: 30px 30px;
            color: #1f2937;
            margin: 0;
            padding: 40px 20px;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
        }
        .card {
            background-color: #ffffff;
            border: 4px solid #ef4444; /* สีแดงเสื้อชินจัง */
            border-radius: 24px;
            padding: 35px;
            max-width: 650px;
            box-shadow: 8px 8px 0px #000000;
            position: relative;
            overflow: hidden;
        }
        .card::before {
            content: "🖍️ 🐘";
            position: absolute;
            top: 15px;
            right: 20px;
            font-size: 28px;
        }
        h1 {
            color: #ef4444;
            font-family: 'Mitr', sans-serif;
            font-size: 2.2em;
            margin-top: 0;
            margin-bottom: 5px;
            display: flex;
            align-items: center;
            gap: 10px;
        }
        .tagline {
            color: #2563eb; /* สีน้ำเงินกางเกงชินจัง */
            font-weight: 600;
            font-size: 1.1em;
            margin-bottom: 20px;
            background: #dbeafe;
            padding: 8px 16px;
            border-radius: 12px;
            display: inline-block;
            border: 2px solid #2563eb;
        }
        p {
            line-height: 1.7;
            color: #374151;
            font-size: 1.05em;
        }
        h3 {
            color: #16a34a;
            margin-top: 25px;
            margin-bottom: 12px;
            font-size: 1.2em;
        }
        .skills {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
        }
        .skills span {
            background-color: #facc15;
            color: #000;
            padding: 8px 16px;
            border-radius: 20px;
            font-weight: 600;
            font-size: 0.9em;
            border: 2px solid #000;
            box-shadow: 2px 2px 0px #000;
        }
        .footer-note {
            margin-top: 30px;
            text-align: right;
            font-size: 0.9em;
            color: #9ca3af;
            font-weight: bold;
        }
    </style>
</head>
<body>
    <div class="card">
        <h1>Siriwan <span>🎒</span></h1>
        <div class="tagline">Computer Engineering Student | Embedded Systems & IoT Developer</div>
        <p>👋 สวัสดีครับ/ค่ะ! นักศึกษาวิศวกรรมคอมพิวเตอร์ มุ่งเน้นการเรียนรู้ระบบฝังตัว (Embedded Systems) การพัฒนาดิจิทัลฮาร์ดแวร์ และการพัฒนาเว็บแอปพลิเคชันเพื่อเชื่อมต่ออุปกรณ์ IoT</p>
        
        <h3>Current Learning 📚</h3>
        <div class="skills">
            <span>💻 C/C++ Programming</span>
            <span>🌐 Web Development</span>
            <span>🔌 Computer Networking</span>
        </div>

        <div class="footer-note">ECP1N / ECP2R 🚀</div>
    </div>
</body>
</html>
