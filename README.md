HTML
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <script src="https://telegram.org/js/telegram-web-app.js"></script>
    <style>
        body { background-color: #1a1a1a; color: #c5a059; font-family: sans-serif; display: flex; flex-direction: column; align-items: center; justify-content: center; height: 100vh; margin: 0; }
        .card { border: 1px solid #c5a059; padding: 40px; text-align: center; width: 80%; }
        h1 { font-size: 40px; margin: 10px 0; }
        button { background: none; border: 1px solid #c5a059; color: #c5a059; padding: 10px 20px; margin: 10px; text-transform: uppercase; }
    </style>
</head>
<body>
    <div style="letter-spacing: 5px;">SIGNET</div>
    <div class="card">
        <div style="font-size: 12px; color: #888;">БАЛАНС</div>
        <h1>0.00 ₽</h1>
    </div>
    <div>
        <button>Ввод</button>
        <button>Вывод</button>
    </div>
    <script>window.Telegram.WebApp.ready();</script>
</body>
</html>
