# Internship-Task-1

      <!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Mini Car Gallery</title>
  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; }
    body {
      font-family: 'Arial', sans-serif;
      line-height: 1.6;
      background: #f5f5f5;
      color: #333;
    }
    header {
      background: #2c3e50;
      color: white;
      padding: 15px 0;
      text-align: center;
      margin-bottom: 20px;
      border-radius: 5px;
    }
    .car-container {
      display: flex;
      flex-wrap: wrap;
      gap: 15px;
      justify-content: center;
    }
    .car {
      background: white;
      padding: 10px;
      border-radius: 5px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
      width: 150px;
      text-align: center;
    }
    .car img {
      width: 100%;
      border-radius: 3px;
      margin-bottom: 5px;
    }
    footer {
      text-align: center;
      margin-top: 20px;
      padding: 10px;
      font-size: 0.9em;
    }
  </style>
</head>
<body>
  <header>
    <h1>Mini Car Gallery</h1>
  </header>

  <div class="car-container">
    <div class="car">
      <img src="https://images.unsplash.com/photo-1541899481282-d53bffe3c35d?w=300" alt="Red Sports Car">
      <p>Sports Car</p>
    </div>
    <div class="car">
      <img src="https://images.unsplash.com/photo-1503376780353-7e6692767b70?w=300" alt="Classic Car">
      <p>Classic</p>
    </div>
  </div>

  <footer>
    <p>© 2024 Mini Car Gallery | All about cars</p>
  </footer>
</body>
</html>
