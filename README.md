# Cine5-
My first repository
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Cine5 - Watch Movies for ₹5</title>
  <style>
    body {
      margin: 0;
      font-family: Arial;
      background-color: #111;
      color: white;
    }
    header {
      background: #e50914;
      padding: 15px;
      text-align: center;
      font-size: 24px;
      font-weight: bold;
    }
    .container {
      padding: 20px;
    }
    .movie {
      display: inline-block;
      width: 200px;
      margin: 15px;
      background: #222;
      border-radius: 10px;
      overflow: hidden;
      text-align: center;
    }
    .movie img {
      width: 100%;
      height: auto;
      display: block;
    }
    .movie h3 {
      margin: 10px 0;
    }
    .btn {
      display: block;
      background: #e50914;
      color: white;
      padding: 10px;
      text-decoration: none;
      margin: 10px;
      border-radius: 5px;
      transition: background .2s;
    }
    .btn:hover {
      background: #b20710;
    }
    @media (max-width: 600px) {
      .movie {
        width: 100%;
        margin: 10px 0;
      }
    }
  </style>
</head>
<body>

<header>🎬 Cine5 - Watch Movies for ₹5</header>

<div class="container">

  <div class="movie">
    <img src="https://via.placeholder.com/200x300" alt="Poster: Sample Movie 1">
    <h3>Sample Movie 1</h3>
    <a class="btn" href="#">Pay ₹5 & Watch</a>
  </div>

  <div class="movie">
    <img src="https://via.placeholder.com/200x300" alt="Poster: Sample Movie 2">
    <h3>Sample Movie 2</h3>
    <a class="btn" href="#">Pay ₹5 & Watch</a>
  </div>

  <div class="movie">
    <img src="https://via.placeholder.com/200x300" alt="Poster: Sample Movie 3">
    <h3>Sample Movie 3</h3>
    <a class="btn" href="#">Pay ₹5 & Watch</a>
  </div>

</div>

</body>
</html>
