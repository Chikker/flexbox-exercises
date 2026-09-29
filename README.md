<!DOCTYPE html>
<html lang="pl">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Zadanie 10 - Moje hobby</title>
  <style>
    * { box-sizing: border-box; }
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: linear-gradient(135deg, #1f2937, #7c3aed, #ec4899);
      color: white;
      padding: 0 0 40px 0;
    }

    .topbar {
      background: rgba(17, 24, 39, 0.5);
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 18px 30px;
      flex-wrap: wrap;
      gap: 12px;
    }

    .brand {
      font-size: 1.8rem;
      font-weight: 700;
    }

    .nav {
      display: flex;
      flex-wrap: wrap;
      gap: 10px;
      justify-content: center;
    }

    .nav a {
      text-decoration: none;
      color: white;
      background: rgba(255,255,255,0.08);
      border: 1px solid rgba(255,255,255,0.25);
      border-radius: 10px;
      padding: 8px 14px;
      font-weight: bold;
      transition: 0.25s;
    }

    .nav a:hover,
    .nav a.active {
      background: #f472b6;
      border-color: #f472b6;
      color: #1f2937;
      transform: translateY(-2px);
    }

    h1 {
      text-align: center;
      margin: 40px 0 20px;
      font-size: 3rem;
      text-shadow: 0 4px 16px rgba(0,0,0,0.3);
    }

    .container {
      display: flex;
      justify-content: space-between;
      align-items: stretch;
      gap: 20px;
      margin: 20px auto 30px;
      max-width: 1200px;
      padding: 0 20px;
      flex-wrap: wrap;
    }

    .card {
      width: 250px;
      min-height: 280px;
      border-radius: 18px;
      padding: 24px 18px;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      text-align: center;
      color: #fff;
      box-shadow: 0 12px 28px rgba(0,0,0,0.18);
      border: 1px solid rgba(255,255,255,0.2);
    }

    .card:nth-child(1) { background: linear-gradient(135deg, #ef4444, #f97316); }
    .card:nth-child(2) { background: linear-gradient(135deg, #3b82f6, #06b6d4); }
    .card:nth-child(3) { background: linear-gradient(135deg, #10b981, #22c55e); }
    .card:nth-child(4) { background: linear-gradient(135deg, #facc15, #f59e0b); color: #1f2937; }

    .icon {
      width: 90px;
      height: 90px;
      border-radius: 50%;
      background: rgba(255,255,255,0.22);
      border: 2px solid rgba(255,255,255,0.8);
      display: flex;
      justify-content: center;
      align-items: center;
      font-size: 2.5rem;
      margin-bottom: 18px;
    }

    h2 {
      margin: 10px 0;
      font-size: 1.7rem;
    }

    p {
      margin: 0;
      line-height: 1.6;
      font-size: 0.96rem;
    }

    .column {
      display: flex;
      flex-direction: column;
      align-items: center;
      gap: 18px;
      max-width: 1200px;
      margin: 0 auto;
      padding: 0 20px;
    }
  </style>
</head>
<body>
  <div class="topbar">
    <div class="brand">Flexbox</div>
    <nav class="nav">
      <a href="zadanie1.html">1</a>
      <a href="zadanie2.html">2</a>
      <a href="zadanie3.html">3</a>
      <a href="zadanie4.html">4</a>
      <a href="zadanie5.html">5</a>
      <a href="zadanie6.html">6</a>
      <a href="zadanie7.html">7</a>
      <a href="zadanie8.html">8</a>
      <a href="zadanie9.html">9</a>
      <a href="zadanie10.html" class="active">10</a>
    </nav>
  </div>

  <h1>Moje hobby</h1>

  <div class="container">
    <div class="card">
      <div class="icon">⚽</div>
      <h2>SPORT</h2>
      <p>Uprawiam sporty, które pomagają mi być sprawnym i pełnym energii.</p>
    </div>

    <div class="card">
      <div class="icon">🎵</div>
      <h2>MUZYKA</h2>
      <p>Muzyka towarzyszy mi na co dzień i daje ogromną motywację.</p>
    </div>

    <div class="card">
      <div class="icon">🎮</div>
      <h2>GRY</h2>
      <p>Uwielbiam gry, które rozwijają strategię i pozwalają odpocząć.</p>
    </div>

    <div class="card">
      <div class="icon">✈️</div>
      <h2>PODRÓŻE</h2>
      <p>Nowe miejsca i kultury inspirują mnie do nauki i odkrywania świata.</p>
    </div>
  </div>

  <div class="column">
    <div class="card">
      <div class="icon">⚽</div>
      <h2>SPORT</h2>
      <p>Aktywność fizyczna pomaga mi zachować kondycję i dobry humor.</p>
    </div>

    <div class="card">
      <div class="icon">🎵</div>
      <h2>MUZYKA</h2>
      <p>Muzyka daje mi energię i poprawia nastrój.</p>
    </div>

    <div class="card">
      <div class="icon">🎮</div>
      <h2>GRY</h2>
      <p>Granie w gry pozwala mi rozwijać koncentrację i kreatywność.</p>
    </div>

    <div class="card">
      <div class="icon">✈️</div>
      <h2>PODRÓŻE</h2>
      <p>Podróże sprawiają, że chcę poznawać nowe miejsca i ludzi.</p>
    </div>
  </div>
</body>
</html>
