# For-you
<!DOCTYPE html>
<html>
<head>
  <title>Untuk Irish Imanina</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      background-color: #fff0f5;
      color: #333;
      text-align: center;
      padding: 50px;
      overflow-x: hidden;
    }
    .card {
      background-color: #ffe4e1;
      padding: 30px;
      border-radius: 15px;
      display: inline-block;
      box-shadow: 0 4px 10px rgba(0,0,0,0.2);
      animation: slideIn 1.5s ease-out;
    }
    @keyframes slideIn {
      from { transform: translateX(-100%); opacity: 0; }
      to { transform: translateX(0); opacity: 1; }
    }
    h1 {
      color: #d63384;
    }
    button {
      padding: 10px 20px;
      background-color: #d63384;
      color: white;
      border: none;
      border-radius: 10px;
      font-size: 16px;
      cursor: pointer;
    }
    #kucing {
      width: 200px;
      margin-top: 20px;
      animation: bounce 2s infinite;
    }
    @keyframes bounce {
      0%, 100% { transform: translateY(0); }
      50% { transform: translateY(-15px); }
    }
  </style>
</head>
<body>
  <div class="card">
    <h1>Hai Irish Imanina!</h1>
    <img id="kucing" src="https://i.pinimg.com/originals/4c/ff/8e/4cff8e059dc2ef61a994417e47a9ef25.gif" alt="Cute Cat Love">
    <p>Kamu itu seperti matahari pagi, selalu bikin hari lebih indah.</p>
    <p>Kalau senyummu bisa jadi wallpaper HP, mungkin baterai aku nggak akan pernah habis.</p>
    <p>Aku cuma mau bilang...</p>
    <h2 style="color: #c2185b;">Kamu luar biasa cantik dan istimewa!</h2>
    <br>
    <button onclick="akhir()">Klik kalau kamu penasaran</button>
    <p id="pesan" style="margin-top: 20px; font-size: 18px;"></p>
  </div>

  <script>
    function akhir() {
      document.getElementById("pesan").innerText = "Tolong ya... buka block aku. Aku rindu!";
    }
  </script>
</body>
</html>
