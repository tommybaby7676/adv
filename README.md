<!DOCTYPE html>
<html lang="zh-Hant">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>一頁式網站範例</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, "Noto Sans TC", sans-serif;
      line-height: 1.6;
      color: #333;
    }

    header {
      background: #111;
      color: #fff;
      padding: 80px 20px;
      text-align: center;
    }

    section {
      padding: 60px 20px;
      max-width: 1000px;
      margin: auto;
    }

    section:nth-child(even) {
      background: #f5f5f5;
    }

    h2 {
      margin-bottom: 20px;
    }

    .btn {
      display: inline-block;
      margin-top: 20px;
      padding: 12px 28px;
      background: #000;
      color: #fff;
      text-decoration: none;
      border-radius: 4px;
    }

    footer {
      background: #222;
      color: #aaa;
      text-align: center;
      padding: 20px;
      font-size: 14px;
    }
  </style>
</head>

<body>

  <!-- Hero / 首屏 -->
  <header>
    <h1>服務主標題</h1>
    <p>一句話說清楚你在幹嘛，不要廢話</p>
    <a href="#contact" class="btn">立即諮詢</a>
  </header>

  <!-- 服務介紹 -->
  <section>
    <h2>我們提供什麼</h2>
    <p>
      簡單說明服務內容，3～5 行內搞定。  
      不要堆術語，讓人看得懂比較重要。
    </p>
  </section>

  <!-- 特色 / 優勢 -->
  <section>
    <h2>為什麼選我們</h2>
    <ul>
      <li>✔ 優勢一（講人話）</li>
      <li>✔ 優勢二（不要浮誇）</li>
      <li>✔ 優勢三（能驗證最好）</li>
    </ul>
  </section>

  <!-- 行動呼籲 -->
  <section id="contact">
    <h2>下一步怎麼做</h2>
    <p>
      有興趣就行動，沒必要逼人。  
      留個聯絡方式或導 LINE。
    </p>
    <a href="#" class="btn">加入官方 LINE</a>
  </section>

  <!-- Footer -->
  <footer>
    © 2026 你的品牌名稱｜保留所有權利
  </footer>

</body>
</html>
