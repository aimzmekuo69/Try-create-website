<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Portofolio Saya</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f4f6fb;
      margin: 0;
      padding: 20px;
      text-align: center;
    }
    .card {
      background: white;
      padding: 30px;
      border-radius: 12px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.1);
      max-width: 600px;
      margin: auto;
    }
    h1 { color: #333; }
    button {
      background: #0073e6;
      color: white;
      padding: 10px 20px;
      border: none;
      border-radius: 8px;
      cursor: pointer;
    }
    button:hover { background: #005bb5; }
  </style>
</head>
<body>
  <div class="card">
    <h1>Halo, Saya [Nama Kamu]</h1>
    <p>Ini website pertama saya 🚀</p>
    <p id="msg">Klik tombol di bawah untuk kejutan:</p>
    <button onclick="showMessage()">Klik Saya</button>
  </div>

  <script>
    function showMessage() {
      document.getElementById('msg').innerText = "🔥 Selamat! Kamu baru saja menjalankan JavaScript!";
      alert("Hai, kamu berhasil belajar coding interaktif!");
    }
  </script>
</body>
</html>
