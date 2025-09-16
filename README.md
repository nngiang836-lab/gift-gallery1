<!doctype html>
<html lang="vi">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Quà tặng dành cho bạn 💌</title>
  <style>
    body {
      font-family: system-ui, Arial, sans-serif;
      margin: 0;
      padding: 20px;
      background: #f7f7f7;
      color: #333;
    }
    h1 {
      margin: 0 0 16px;
      text-align: center;
    }
    p.note {
      text-align: center;
      color: #555;
      margin-bottom: 20px;
    }
    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(160px, 1fr));
      gap: 16px;
    }
    .card {
      background: #fff;
      padding: 8px;
      border-radius: 12px;
      box-shadow: 0 2px 6px rgba(0,0,0,.08);
      overflow: hidden;
      transition: transform .2s ease;
    }
    .card:hover {
      transform: scale(1.03);
    }
    .card img {
      width: 100%;
      height: 180px;
      object-fit: cover;
      display: block;
      border-radius: 10px;
    }
  </style>
</head>
<body>
  <h1>🎁 Một món quà nhỏ cho bạn</h1>
  <p class="note">Hy vọng những tấm hình này sẽ làm bạn mỉm cười ✨</p>

  <div class="grid">
    <div class="card"><img src="images/photo1.jpg" alt="Ảnh 1"></div>
    <div class="card"><img src="images/photo2.jpg" alt="Ảnh 2"></div>
    <div class="card"><img src="images/photo3.jpg" alt="Ảnh 3"></div>
    <div class="card"><img src="images/photo4.jpg" alt="Ảnh 4"></div>
    <div class="card"><img src="images/photo5.jpg" alt="Ảnh 5"></div>
    <div class="card"><img src="images/photo6.jpg" alt="Ảnh 6"></div>
  </div>
</body>
</html>
