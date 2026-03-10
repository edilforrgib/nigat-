
<html lang="am">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ንጋት የዜማ መሳሪያዎች | Nigat Melody</title>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;600&display=swap" rel="stylesheet">
    <style>
        :root {
            --primary-gold: #d4af37;
            --glass-bg: rgba(255, 255, 255, 0.05);
            --text-light: #f4f4f4;
            --accent-orange: #ff4d00;
        }

        body {
            margin: 0;
            font-family: 'Inter', sans-serif;
            background: linear-gradient(135deg, #0f0f0f 0%, #262626 100%);
            color: var(--text-light);
            overflow-x: hidden;
        }

        /* Hero Section */
        header {
            height: 60vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            background: url('https://images.unsplash.com/photo-1511671782779-c97d3d27a1d4?auto=format&fit=crop&q=80') center/cover;
            position: relative;
        }

        header::before {
            content: '';
            position: absolute;
            inset: 0;
            background: rgba(0, 0, 0, 0.7);
        }

        .hero-content {
            position: relative;
            z-index: 1;
        }

        h1 { font-size: 3.5rem; margin-bottom: 0.5rem; color: var(--primary-gold); }
        .tagline { font-size: 1.2rem; opacity: 0.8; letter-spacing: 2px; }

        /* Modern Grid */
        .container {
            max-width: 1100px;
            margin: -50px auto 50px;
            padding: 20px;
            position: relative;
            z-index: 2;
        }

        .glass-card {
            background: var(--glass-bg);
            backdrop-filter: blur(15px);
            border: 1px solid rgba(255, 255, 255, 0.1);
            border-radius: 24px;
            padding: 40px;
            box-shadow: 0 8px 32px 0 rgba(0, 0, 0, 0.8);
        }

        .quality-badge {
            display: inline-block;
            background: linear-gradient(90deg, var(--primary-gold), #f9d976);
            color: black;
            padding: 5px 15px;
            border-radius: 50px;
            font-weight: bold;
            margin-bottom: 20px;
            font-size: 0.9rem;
        }

        .instrument-list {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(120px, 1fr));
            gap: 20px;
            margin: 30px 0;
        }

        .item {
            background: rgba(255, 255, 255, 0.03);
            padding: 20px;
            border-radius: 15px;
            text-align: center;
            transition: transform 0.3s ease;
            border: 1px solid rgba(212, 175, 55, 0.2);
        }

        .item:hover {
            transform: translateY(-10px);
            background: rgba(212, 175, 55, 0.1);
        }

        .item span { font-size: 2rem; display: block; margin-bottom: 10px; }

        /* Contact Section */
        .cta-section {
            display: flex;
            flex-wrap: wrap;
            gap: 30px;
            margin-top: 40px;
            border-top: 1px solid rgba(255,255,255,0.1);
            padding-top: 30px;
        }

        .contact-info { flex: 1; min-width: 280px; }
        .delivery-box { 
            flex: 1; 
            min-width: 280px; 
            background: rgba(255, 77, 0, 0.1); 
            padding: 20px; 
            border-radius: 15px;
            border-left: 5px solid var(--accent-orange);
        }

        .btn {
            display: inline-block;
            background: var(--accent-orange);
            color: white;
            text-decoration: none;
            padding: 15px 35px;
            border-radius: 12px;
            font-weight: bold;
            margin-top: 20px;
            transition: 0.3s;
            text-transform: uppercase;
        }

        .btn:hover { filter: brightness(1.2); transform: scale(1.05); }

        @media (max-width: 600px) {
            h1 { font-size: 2.2rem; }
        }
    </style>
</head>
<body>

    <header>
        <div class="hero-content">
            <h1>ንጋት የዜማ መሳሪያዎች</h1>
            <div class="tagline">NIGAT MELODY INSTRUMENTS</div>
        </div>
    </header>

    <div class="container">
        <div class="glass-card">
            <div class="quality-badge">በከፍተኛ ጥራት የተመረቱ ✨</div>
            <p style="font-size: 1.2rem; line-height: 1.6;">
                Glossy, reflective & waterproof የሆኑ ምርጥ የኢትዮጵያ የባህል የሙዚቃ መሳሪያዎች።
            </p>

            <div class="instrument-list">
                <div class="item"><span>🎻</span>በገና</div>
                <div class="item"><span>🎸</span>ክራር</div>
                <div class="item"><span>🎸</span>ቤዝ ክራር</div>
                <div class="item"><span>🎻</span>መሰንቆ</div>
                <div class="item"><span>🎷</span>ዋሽንት</div>
                <div class="item"><span>💼</span>ቦርሳ</div>
            </div>

            <div class="cta-section">
                <div class="contact-info">
                    <h3>#Order_now</h3>
                    <p>📞 0920300011 / 0991109365</p>
                    <p>✈️ Telegram: <a href="https://t.me/Nigatmelody" style="color: var(--primary-gold);">@Nigatmelody</a></p>
                    <p>🏢 አድራሻ: ኮልፌ 18 አጠናተራ ፊሊጶስ ቤተክርስቲያን ዝቅ ብሎ</p>
                </div>
                <div class="delivery-box">
                    <p>🚖 🏍 በፍጥነት ይዘዙን ባሉበት ቦታ ያለምንም ተጨማሪ ክፍያ እናደርሳለን!</p>
                    <a href="https://t.me/Nigatmelody" class="btn">አሁኑኑ ይዘዙ / ORDER NOW</a>
                </div>
            </div>
        </div>
    </div>

</body>
</html>
