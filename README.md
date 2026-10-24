
<!DOCTYPE html>
<html lang="bn">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>YUMMY | Premium Banana Chips</title>

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: Arial, sans-serif;
      background: #fffaf7;
      color: #292522;
    }

    header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 20px 8%;
      background: white;
      border-bottom: 1px solid #eee;
    }

    .logo {
      font-size: 30px;
      font-weight: bold;
      color: #e85d8e;
      letter-spacing: 2px;
    }

    nav a {
      text-decoration: none;
      color: #333;
      margin-left: 20px;
      font-size: 15px;
    }

    .hero {
      min-height: 75vh;
      display: flex;
      align-items: center;
      justify-content: space-between;
      gap: 30px;
      padding: 60px 8%;
      background: linear-gradient(135deg, #fff0f5, #fffaf7);
    }

    .hero-text {
      max-width: 520px;
    }

    .hero-text small {
      color: #e85d8e;
      font-weight: bold;
      letter-spacing: 2px;
    }

    h1 {
      font-size: clamp(38px, 6vw, 65px);
      line-height: 1.15;
      margin: 20px 0;
    }

    h1 span {
      color: #e85d8e;
    }

    .hero-text p {
      font-size: 17px;
      line-height: 1.8;
      color: #666;
      margin-bottom: 30px;
    }

    .btn {
      display: inline-block;
      background: #e85d8e;
      color: white;
      text-decoration: none;
      padding: 15px 30px;
      border-radius: 30px;
      font-weight: bold;
    }

    .product {
      width: min(100%, 380px);
      min-height: 330px;
      border-radius: 30px;
      background: #ffe0eb;
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 100px;
    }

    .features {
      text-align: center;
      padding: 55px 8%;
    }

    .features h2 {
      font-size: 32px;
      margin-bottom: 15px;
    }

    .features p {
      color: #777;
      line-height: 1.8;
    }

    footer {
      text-align: center;
      padding: 25px;
      background: #292522;
      color: white;
    }

    @media (max-width: 700px) {
      header {
        padding: 18px 5%;
      }

      nav a {
        margin-left: 10px;
        font-size: 13px;
      }

      .hero {
        flex-direction: column;
        text-align: center;
        padding: 45px 6%;
      }

      .product {
        min-height: 230px;
        font-size: 75px;
      }
    }
  </style>
</head>

<body>

  <header>
    <div class="logo">YUMMY</div>
    <nav>
      <a href="#home">হোম</a>
      <a href="#product">পণ্য</a>
      <a href="#contact">যোগাযোগ</a>
    </nav>
  </header>

  <section class="hero" id="home">
    <div class="hero-text">
      <small>CRUNCH INTO HAPPINESS</small>

      <h1>প্রতিটি কামড়ে<br>
        <span>মজার স্বাদ!</span>
      </h1>

      <p>
        YUMMY নিয়ে এসেছে মজাদার কলার চিপস।
        প্রতিদিনের স্ন্যাকস হোক আরও আনন্দময়
        এবং স্বাদে ভরপুর।
      </p>

      <a class="btn" href="#product">আমাদের পণ্য দেখুন</a>
    </div>

    <div class="product" id="product">
      🍌
    </div>
  </section>

  <section class="features">
    <h2>কেন YUMMY?</h2>
    <p>
      মজাদার স্বাদ, আকর্ষণীয় প্যাকেজিং
      এবং আপনার স্ন্যাকসের আনন্দ বাড়াতে
      আমাদের বিশেষ আয়োজন।
    </p>
  </section>

  <footer id="contact">
    <p>YUMMY — Taste the Happiness</p>
    <p>© 2026 YUMMY. All Rights Reserved.</p>
  </footer>

</body>
</html>
