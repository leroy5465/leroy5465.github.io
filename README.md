html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Redirect to Menu</title>
  <style>
    body {
      display: flex;
      justify-content: center;
      align-items: center;
      min-height: 100vh;
      margin: 0;
      background-image: url("https://i.ibb.co/mBx9VBn/download.gif");
      background-repeat: no-repeat;
      background-size: cover;
      font-size: 20px;
      font-weight: bold;
      text-align: center;
    }
    img {
      max-width: 100vw;
      height: auto;
      margin-top: 100px;
    }
  </style>
  <script>
    setTimeout(() => {
      window.location.replace("Menu.html");
    }, 3000);
  </script>
</head>
<body>
  <img src="https://source.unsplash.com/random?city,night" alt="City Night" style="position: absolute; top: 50px; z-index: 1000; opacity: 0.5; filter: alpha(opacity=50);" />
  <div style="position: relative; z-index: 1001; color: #fff; padding: 50px; border-radius: 20px; background-color: #000; opacity: 0.75; width: 300px; margin: 0 auto; text-align: center;">
    <h1 style="color: #fff; text-shadow: 0 0 5px #000;">Redirecting to the Menu...</h1>
    <p style="color: #fff; text-shadow: 0 0 5px #000;">loading ....</p>
  </div>
</body>
</html>
