<Hai Keli>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <title>Love Button</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      background-color: #ffe6e6;
      text-align: center;
      padding-top: 100px;
    }

    h1 {
      color: #cc0000;
    }

    #loveMessage {
      margin-top: 30px;
      font-size: 2em;
      color: #ff0066;
      display: none;
    }

    button {
      background-color: #ff3366;
      color: white;
      border: none;
      padding: 15px 30px;
      font-size: 1.2em;
      border-radius: 10px;
      cursor: pointer;
    }

    button:hover {
      background-color: #cc0052;
    }
  </style>
</head>
<body>

  <h1>Selamat Datang</h1>
  <button onclick="showLove()">Klik Saya 💖</button>

  <div id="loveMessage">I Love U 💘</div>

  <script>
    function showLove() {
      document.getElementById('loveMessage').style.display = 'block';
    }
  </script>

</body>
</html>
