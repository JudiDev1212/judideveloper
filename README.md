<!DOCTYPE html>
<html lang="tr">
<head>
  <meta charset="UTF-8">
  <title>Selam Sitesi</title>
  <style>
    body {
      background-color: #121212;
      color: white;
      font-family: Arial, sans-serif;
      display: flex;
      align-items: center;
      justify-content: center;
      height: 100vh;
      flex-direction: column;
    }
    button {
      padding: 15px 30px;
      font-size: 20px;
      border: none;
      border-radius: 8px;
      background-color: #1e88e5;
      color: white;
      cursor: pointer;
    }
    h1 {
      margin-top: 30px;
    }
  </style>
</head>
<body>
  <button onclick="showMessage()">Tıkla Bakalım</button>
  <h1 id="message"></h1>

  <script>
    function showMessage() {
      document.getElementById("message").innerText = "Selam 👋";
    }
  </script>
</body>
</html>
