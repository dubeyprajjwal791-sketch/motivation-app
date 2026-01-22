<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <title>Motivation Store</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #f2f2f2;
    }

    /* Header */
    header {
      background: #2874f0;
      color: white;
      padding: 15px;
      text-align: center;
      font-size: 20px;
      font-weight: bold;
    }

    /* Container */
    .container {
      padding: 15px;
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
      gap: 15px;
    }

    /* Card */
    .card {
      background: white;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
      padding: 15px;
      text-align: center;
    }

    .card img {
      width: 80px;
      height: 80px;
      margin-bottom: 10px;
    }

    .card h3 {
      font-size: 16px;
      margin: 5px 0;
    }

    .card p {
      font-size: 14px;
      color: #555;
    }

    footer {
      text-align: center;
      padding: 10px;
      font-size: 13px;
      color: #666;
      background: #fff;
      margin-top: 20px;
    }
  </style>
</head>

<body>

  <!-- Top Bar -->
  <header>
    Motivation Store
  </header>

  <!-- Content like Flipkart -->
  <div class="container">

    <div class="card">
      <img src="https://cdn-icons-png.flaticon.com/512/3135/3135715.png">
      <h3>Success</h3>
      <p>Think big and stay focused</p>
    </div>

    <div class="card">
      <img src="https://cdn-icons-png.flaticon.com/512/942/942748.png">
      <h3>Hard Work</h3>
      <p>No shortcut to success</p>
    </div>

    <div class="card">
      <img src="https://cdn-icons-png.flaticon.com/512/1995/1995574.png">
      <h3>Confidence</h3>
      <p>Believe in yourself</p>
    </div>

    <div class="card">
      <img src="https://cdn-icons-png.flaticon.com/512/1995/1995569.png">
      <h3>Discipline</h3>
      <p>Do it every day</p>
    </div>

  </div>

  <footer>
    © 2026 Motivation Store
  </footer>

</body>
</html>
