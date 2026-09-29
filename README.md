<!DOCTYPE html>
<html lang="pl">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Zadanie 10 - Moje hobby</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #f5f5f5;
      padding: 40px;
    }

    h1 {
      text-align: center;
      margin-bottom: 30px;
      color: #222;
    }

    .container {
      display: flex;
      justify-content: space-between;
      align-items: stretch;
      gap: 20px;
      margin-bottom: 30px;
      flex-wrap: wrap;
    }

    .card {
      width: 240px;
      min-height: 260px;
      border-radius: 12px;
      padding: 20px;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      text-align: center;
      color: #fff;
      box-shadow: 0 6px 14px rgba(0,0,0,0.15);
    }

    .card:nth-child(1) { background: #ff7675; }
    .card:nth-child(2) { background: #74b9ff; }
    .card:nth-child(3) { background: #00b894; }
    .card:nth-child(4) { background: #fdcb6e; color: #222; }

    .icon {
      width: 80px;
      height: 80px;
      border-radius: 50%;
      background: rgba(255,255,255,0.25);
      border: 2px solid rgba(255,255,255,0.7);
      display: flex;
      justify-content: center;
      align-items: center;
      font-size: 2rem;
      margin-bottom: 15px;
    }

    h2 {
      margin: 6px 0;
      font-size: 1.6rem;
    }

    p {
      margin: 0;
      line-height: 1.5;
      font-size: 0.95rem;
    }

    .column {
      display: flex;
      flex-direction: column;
      align-items: center;
      gap: 20px;
    }
  </style>
</head>
<body>
  <h1>Moje hobby</h1>

  <div class="container">
    <div class="card">
      <div class="icon">⚽</div>
      <h2>SPORT</h2>
      <p>Uprawiam sporty, które pomagają mi utrzymać kondycję i dobrą formę.</p>
    </div>

    <div class="card">
      <div class="icon">🎵</div>
      <h2>MUZYKA</h2>
      <p>Muzyka towarzyszy mi w każdej chwili i daje energię do działania.</p>
    </div>

    <div class="card">
      <div class="icon">🎮</div>
      <h2>GRY</h2>
      <p>Uwielbiam gry, które rozwijają strategię i pozwalają odpocząć.</p>
    </div>

    <div class="card">
      <div class="icon">✈️</div>
      <h2>PODRÓŻE</h2>
      <p>Nowe miejsca, ludzi i kultury inspirują mnie do nauki i odkrywania świata.</p>
    </div>
  </div>

  <h2>Wersja pionowa</h2>
  <div class="column">
    <div class="card">
      <div class="icon">⚽</div>
      <h2>SPORT</h2>
      <p>Uprawiam sporty, które pomagają mi utrzymać kondycję.</p>
    </div>

    <div class="card">
      <div class="icon">🎵</div>
      <h2>MUZYKA</h2>
      <p>Muzyka towarzyszy mi w każdej chwili.</p>
    </div>

    <div class="card">
      <div class="icon">🎮</div>
      <h2>GRY</h2>
      <p>Uwielbiam gry strategiczne i przygodowe.</p>
    </div>

    <div class="card">
      <div class="icon">✈️</div>
      <h2>PODRÓŻE</h2>
      <p>Podróże pozwalają mi poznawać nowe miejsca.</p>
    </div>
  </div>
</body>
</html>
