<!DOCTYPE html>
<html lang="zh-TW">
<head>
    <meta charset="UTF-8">
    <title>阿忠的山寨 - 掃碼導航</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            margin: 0;
            background-color: #f4f4f9;
        }
        .print-card {
            background: #ffffff;
            border: 3px solid #000;
            border-radius: 16px;
            padding: 40px;
            width: 350px;
            text-align: center;
            box-shadow: 0 10px 25px rgba(0,0,0,0.1);
        }
        h1 {
            font-size: 28px;
            margin-bottom: 10px;
            color: #1a1a1a;
        }
        p {
            font-size: 16px;
            color: #555;
            margin-bottom: 25px;
            line-height: 1.5;
        }
        .qr-code {
            margin: 0 auto 20px auto;
            padding: 15px;
            border: 2px dashed #333;
            border-radius: 12px;
            display: inline-block;
        }
        .qr-code img {
            width: 220px;
            height: 220px;
            display: block;
        }
        .footer-note {
            font-size: 14px;
            font-weight: bold;
            color: #d9534f;
            margin-top: 15px;
        }
        @media print {
            body { background: none; }
            .print-card { box-shadow: none; border-color: #000; }
        }
    </style>
</head>
<body>

<div class="print-card">
    <h1>🏰 阿忠的山寨</h1>
    <p>掃描下方 QR Code<br>快速開啟導航與寨主通訊！</p>
    
    <div class="qr-code">
        <!-- 直接產生網址專屬的純淨黑白 QR Code -->
        <img src="https://api.qrserver.com/v1/create-qr-code/?size=220x220&data=https://yah-chong-castle.netlify.app" alt="阿忠的山寨 QR Code">
    </div>

    <div class="footer-note">🅿️ 備有停車場 • 抵達請撥寨主專线</div>
</div>

</body>
</html># yyah-chong-castle
