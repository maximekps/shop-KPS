<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Boutique KPS</title>
    <script src="https://telegram.org/js/telegram-web-app.js"></script>
    <style>
        body { font-family: Arial, sans-serif; background-color: #f4f4f9; margin: 0; padding: 20px; text-align: center; color: #333; }
        h1 { color: #2481cc; }
        .container { max-width: 400px; margin: 0 auto; background: white; padding: 20px; border-radius: 15px; box-shadow: 0 4px 10px rgba(0,0,0,0.1); }
        .product { border: 1px solid #ddd; padding: 15px; border-radius: 10px; margin-top: 15px; background: #fff; }
        button { background-color: #2481cc; color: white; border: none; padding: 10px 20px; border-radius: 8px; cursor: pointer; font-size: 16px; margin-top: 10px; width: 100%; }
        button:hover { background-color: #1a66a3; }
    </style>
</head>
<body>

    <div class="container">
        <h1>Boutique KPS 🛒</h1>
        <p>Bienvenue dans ton application Telegram !</p>
        
        <div class="product">
            <h3>Produit Exemple #1</h3>
            <p>Prix : 10,00 €</p>
            <button onclick="acheter()">Acheter maintenant</button>
        </div>
    </div>

    <script>
        // Initialise le bouton principal de Telegram
        const tg = window.Telegram.WebApp;
        tg.expand(); // Ouvre l'app en grand écran

        function acheter() {
            tg.showAlert("Merci pour ton clic ! Ton système de boutique commence ici.");
        }
    </script>
</body>
</html>
