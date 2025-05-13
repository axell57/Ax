<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Jawaban Untuk Mantan</title>
  <style>
    body {
      background: linear-gradient(#ffcccc, #ffe6e6);
      font-family: 'Comic Sans MS', cursive, sans-serif;
      text-align: center;
      padding: 50px;
      color: #660000;
    }
    h1 {
      font-size: 48px;
      color: #cc0000;
      margin-top: 50px;
    }
    p {
      font-size: 24px;
      margin: 20px;
    }
    .heart-break {
      font-size: 100px;
      animation: shake 1s infinite;
    }
    @keyframes shake {
      0% { transform: rotate(0deg); }
      25% { transform: rotate(10deg); }
      50% { transform: rotate(-10deg); }
      75% { transform: rotate(10deg); }
      100% { transform: rotate(0deg); }
    }
    button {
      margin-top: 30px;
      padding: 10px 20px;
      font-size: 20px;
      border: none;
      background-color: #cc0000;
      color: white;
      border-radius: 20px;
      cursor: pointer;
      transition: background-color 0.3s;
    }
    button:hover {
      background-color: #990000;
    }
  </style>
</head>
<body>

  <div class="heart-break">💔</div>
  <h1>Maaf, Aku Sudah Move On</h1>
  <p>
    Terima kasih atas kenangan,<br>
    Tapi aku memilih melangkah ke masa depan.<br>
    Balikan? Hmm... Bukan pilihan lagi.
  </p>

  <button onclick="alert('Goodbye masa lalu, Halo masa depan!')">Klik jika Setuju</button>

  <button onclick="alert('maaf aku gak setuju')">Klik jika tidak Setuju</button>

</body>
</html>
