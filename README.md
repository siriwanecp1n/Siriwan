<!DOCTYPE html>
<html lang="th">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Siriwan | Computer Engineering Portfolio 🖍️</title>

    <link href="https://fonts.googleapis.com/css2?family=Mitr:wght@400;600&family=Prompt:wght@300;400;600&display=swap" rel="stylesheet">

    <style>
        * {
            box-sizing: border-box;
        }

        body {
            font-family: 'Prompt', 'Mitr', sans-serif;
            background-color: #fef08a;
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
            border: 4px solid #ef4444;
            border-radius: 24px;
            padding: 35px;
            max-width: 700px;
            width: 100%;
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
            font-size: 2.3em;
            margin-top: 0;
            margin-bottom: 8px;
            display: flex;
            align-items: center;
            gap: 10px;
        }

        .role {
            color: #6b7280;
            font-size: 1em;
            margin-bottom: 15px;
        }

        .tagline {
            color: #2563eb;
            font-weight: 600;
            font-size: 1.1em;
            margin-bottom: 20px;
            background: #dbeafe;
            padding: 10px 16px;
            border-radius: 12px;
            display: inline-block;
            border: 2px solid #2563eb;
        }

        p {
            line-height: 1.8;
            color: #374151;
            font-size: 1.05em;
        }

        h3 {
            color: #16a34a;
            margin-top: 28px;
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

        .github {
            display: inline-block;
            margin-top: 25px;
            padding: 11px 20px;
            background: #111827;
            color: white;
            text-decoration: none;
            border-radius: 12px;
            font-weight: 600;
            border: 2px solid #000;
            box-shadow: 3px 3px 0px #000;
        }

        .github:hover {
            background: #374151;
            transform: translateY(-2px);
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

        <h1>
            Siriwan 🎒
        </h1>

        <div class="role">
            Computer Engineering Student
        </div>

        <div class="tagline">
            Embedded Systems & IoT Developer 🔌
        </div>

        <p>
            👋 สวัสดีครับ/ค่ะ! ผม/ฉันเป็นนักศึกษาวิศวกรรมคอมพิวเตอร์
            สนใจการพัฒนาระบบฝังตัว (Embedded Systems)
            และเทคโนโลยี Internet of Things (IoT)
        </p>

        <p>
            💡 กำลังพัฒนาทักษะด้านการเขียนโปรแกรม
            การเชื่อมต่ออุปกรณ์ และการพัฒนาเว็บ
            เพื่อสร้างระบบที่สามารถทำงานร่วมกันระหว่างซอฟต์แวร์และฮาร์ดแวร์
        </p>

        <h3>
            Current Learning 📚
        </h3>

        <div class="skills">
            <span>💻 C/C++ Programming</span>
            <span>🌐 Web Development</span>
            <span>🔌 Computer Networking</span>
        </div>

        <h3>
            Interests ❤️
        </h3>

        <div class="skills">
            <span>🤖 Embedded Systems</span>
            <span>📡 IoT</span>
            <span>⚙️ Hardware</span>
        </div>

        <a
            class="github"
            href="https://github.com/siriwanecp1n"
            target="_blank"
            rel="noopener noreferrer"
        >
            🐙 GitHub: siriwanecp1n
        </a>

        <div class="footer-note">
            ECP1N  🚀
        </div>

    </div>

</body>
</html>
