# Arnold-shop
Shopping
<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Arnold Shopping - Vêtements & Chaussures</title>
  <style>
    body {
      margin: 0;
      font-family: 'Arial', sans-serif;
      background-color: #f5f5f5;
      color: #333;
    }

    header {
      background-color: #222;
      color: white;
      padding: 30px 20px;
      text-align: center;
    }

    header h1 {
      margin: 0;
      font-size: 2.5em;
    }

    section {
      padding: 40px 20px;
      max-width: 1000px;
      margin: auto;
    }

    .intro {
      text-align: center;
    }

    .intro p {
      font-size: 1.2em;
      margin-top: 10px;
    }

    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
      margin-top: 30px;
    }

    .gallery-item {
      background-color: white;
      border-radius: 8px;
      overflow: hidden;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
    }

    .gallery-item img {
      width: 100%;
      height: 300px;
      object-fit: cover;
    }

    .gallery-item h3 {
      padding: 10px;
      font-size: 1.1em;
    }

    .contact {
      text-align: center;
    }

    .contact a {
      display: inline-block;
      margin: 10px;
      padding: 12px 24px;
      background-color: #222;
      color: white;
      text-decoration: none;
      border-radius: 6px;
    }

    footer {
      text-align: center;
      padding: 20px;
      font-size: 0.9em;
      background-color: #eee;
    }
  </style>
</head>
<body>

  <header>
    <h1>Arnold Shopping</h1>
    <p>Vêtements & Chaussures tendance pour tous les styles</p>
  </header>

  <section class="intro">
    <h2>Bienvenue chez Arnold Shopping</h2>
    <p>Nous vous proposons une sélection de vêtements et chaussures stylés à prix abordables. Livraison rapide et qualité garantie.</p>
  </section>

  <section>
    <h2>Nos Produits</h2>
    <div class="gallery">
      <div class="gallery-item">
        <img src="https://via.placeholder.com/300x300?text=Veste+Homme" alt="Veste homme">
        <h3>Veste Homme - 25€</h3>
      </div>
      <div class="gallery-item">
        <img src="https://via.placeholder.com/300x300?text=Chaussures+Femme" alt="Chaussures femme">
        <h3>Chaussures Femme - 30€</h3>
      </div>
      <div class="gallery-item">
        <img src="https://via.placeholder.com/300x300?text=Jean+Slim" alt="Jean slim">
        <h3>Jean Slim - 20€</h3>
      </div>
    </div>
  </section>

  <section class="contact">
    <h2>Contact</h2>
    <p>Intéressé(e) par un produit ? Commandez ou posez-nous une question :</p>
    <a href="https://wa.me/237XXXXXXXX" target="_blank">📲 WhatsApp</a>
    <a href="mailto:tonemail@example.com">✉️ Email</a>
  </section>

  <footer>
    &copy; 2025 Arnold Shopping. Tous droits réservés.
  </footer>

</body>
</html>
