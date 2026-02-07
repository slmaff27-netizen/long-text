<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Long Text Ceria 💙</title>

  <!-- Font lucu -->
  <link href="https://fonts.googleapis.com/css2?family=Fredoka:wght@400;600&display=swap" rel="stylesheet">

  <style>
    body {
      margin: 0;
      font-family: 'Fredoka', sans-serif;
      background: linear-gradient(to bottom, #87CEEB, #E0F6FF);
      min-height: 100vh;
    }

    .container {
      max-width: 800px;
      margin: 40px auto;
      background: #ffffff;
      padding: 28px;
      border-radius: 20px;
      box-shadow: 0 10px 25px rgba(0,0,0,0.15);
      position: relative;
    }

    h1 {
      text-align: center;
      color: #1e88e5;
      margin-bottom: 10px;
    }

    .subtitle {
      text-align: center;
      color: #555;
      margin-bottom: 30px;
    }

    .card {
      background: #f0f9ff;
      padding: 18px;
      border-radius: 16px;
      margin-bottom: 16px;
      cursor: pointer;
      transition: transform 0.2s ease, background 0.2s ease;
    }

    .card:hover {
      transform: scale(1.02);
      background: #dff3ff;
    }

    .card:active {
      transform: scale(0.97);
    }

    p {
      text-align: justify;
      margin: 0;
    }

    .cloud {
      position: absolute;
      top: -25px;
      right: 20px;
      font-size: 40px;
    }

    .stars {
      text-align: center;
      font-size: 20px;
      margin-top: 30px;
    }

    button {
      display: block;
      margin: 30px auto 0;
      padding: 12px 24px;
      font-size: 16px;
      border: none;
      border-radius: 25px;
      background: #64b5f6;
      color: white;
      cursor: pointer;
      transition: background 0.2s ease, transform 0.2s ease;
    }

    button:hover {
      background: #42a5f5;
      transform: scale(1.05);
    }
  </style>
</head>

<body>

  <div class="container">
    <div class="cloud">☁️</div>

    <h1>buat yang baca ini</h1>
    <div class="subtitle">Pencet aku ya✨</div>

    <div class="card" onclick="alert('next')">
      <p>
        hai kikk, you did a good job today. aku selalu doain tentang hasil yang kamu dapetin ko
        kalopun emang belum dapet yang terbaik it's okei
        ini bukan akhir dari semuanya ya..
      </p>
    </div>

    <div class="card" onclick="alert('next')">
      <p>
        oiya, for the last time, i have mini gift for you kik,, diterima ya.. 
        jgn diliat dari harga ya, hargain semua hal kecil.. 
        about my feelings, gausa khawatir lagi aku udah berusaha 
        buat ga naruh harapan lagi kaya yang kamu bilang kik..
      </p>
    </div>

    <div class="card" onclick="alert('next again')">
      <p>
        about your promise, gausa buka hati buat aku kik, aku gakuat sama over thinking setiap malem nya
        gausa Dateng ke hidup ku lagi ya kik, terkesan jahat tapi aku gamau sakit hati lagi.. 
        last, thx for everything ya kikkk, bahagia terus.. 
        in the future semoga kamu ditemuin sama cewe yang sesuai sama tipe kamu..

        okeii thx for the experience, and selamat bertemu di ketidak sengajaan selanjutnya, byee
      </p>
    </div>

    <button onclick="alert('MAKASII YAA UDAH DI BACA!!!')">
      
    </button>

    <div class="stars">✨ ⭐ 💫 🌈 ⭐ ✨</div>
  </div>

</body>
</html>
