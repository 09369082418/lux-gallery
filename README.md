# lux-gallery<!DOCTYPE html><html lang="fa" dir="rtl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>لوکس گالری | Lux Gallery</title>
  <style>
    body {
      font-family: sans-serif;
      background-color: #111;
      color: #fff;
      margin: 0;
      padding: 0;
    }
    header {
      background-color: #222;
      padding: 20px;
      text-align: center;
    }
    h1 {
      margin: 0;
      font-size: 2em;
    }
    .container {
      padding: 20px;
    }
    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
      gap: 20px;
    }
    .card {
      background-color: #333;
      border-radius: 10px;
      overflow: hidden;
      box-shadow: 0 0 10px rgba(255,255,255,0.1);
    }
    .card img {
      width: 100%;
      height: auto;
    }
    .card-content {
      padding: 15px;
    }
    .card-content p {
      margin: 10px 0 0;
    }
  </style>
</head>
<body>
  <header>
    <h1>لوکس گالری | Lux Gallery</h1>
    <p>نمایشگاهی از خودروهای لوکس و گران‌قیمت<br>Showcase of luxury and expensive cars</p>
  </header>  <div class="container">
    <div class="gallery">
      <div class="card">
        <img src="https://cdn.pixabay.com/photo/2017/01/06/19/15/car-1957037_1280.jpg" alt="Lamborghini">
        <div class="card-content">
          <p>لامبورگینی اونتادور، ترکیبی از سرعت و طراحی فوق‌العاده<br>Lamborghini Aventador – A mix of speed and stunning design</p>
        </div>
      </div><div class="card">
    <img src="https://cdn.pixabay.com/photo/2013/07/13/12/46/bugatti-159340_1280.png" alt="Bugatti">
    <div class="card-content">
      <p>بوگاتی ویرون، یکی از سریع‌ترین ماشین‌های دنیا<br>Bugatti Veyron – One of the fastest cars in the world</p>
    </div>
  </div>

  <div class="card">
    <img src="https://cdn.pixabay.com/photo/2020/05/14/20/34/ferrari-5171757_1280.jpg" alt="Ferrari">
    <div class="card-content">
      <p>فراری 488، نماد ظرافت و قدرت ایتالیایی<br>Ferrari 488 – Symbol of Italian elegance and power</p>
    </div>
  </div>
</div>

  </div>
</body>
</html>
