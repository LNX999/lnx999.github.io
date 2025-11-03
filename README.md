# lnx999.github.io
artworks
<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>LNX.999 – L’art sans antivirus</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header>
    <h1>LNX.999</h1>
    <p class="slogan">L’art sans antivirus</p>
    <nav>
      <a href="index.html" class="active">Accueil</a>
      <a href="boutique.html">Boutique</a>
      <a href="contact.html">Contact</a>
    </nav>
  </header>

  <section class="hero">
    <h2>Fait main, fait tard, fait avec chaos.</h2>
  </section>

  <section class="intro">
    <p>
      Créations en papier, carton, peinture et intuition.  
      Chaque pièce est unique — née du bruit du papier, du silence et de la nuit.
    </p>
  </section>

  <footer>
    <p>© 2025 LNX.999 – L’art sans antivirus</p>
  </footer>
</body>
</html>
<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Contact – LNX.999</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header>
    <h1>LNX.999</h1>
    <nav>
      <a href="index.html">Accueil</a>
      <a href="boutique.html">Boutique</a>
      <a href="contact.html" class="active">Contact</a>
    </nav>
  </header>

  <section class="contact">
    <p>📩 <a href="mailto:lnx.showtime@gmail.com">lnx.showtime@gmail.com</a></p>
    <p>Instagram / QR code à venir</p>
  </section>

  <footer>
    <p>© 2025 LNX.999 – L’art sans antivirus</p>
  </footer>
</body>
</html>@import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@300;500&display=swap');

body {
  background-color: #000;
  color: #fff;
  font-family: 'Montserrat', sans-serif;
  margin: 0;
  padding: 0;
  text-align: center;
}

header {
  padding: 40px 0 20px;
}

h1 {
  font-size: 2.5rem;
  letter-spacing: 3px;
}

.slogan {
  font-size: 0.9rem;
  opacity: 0.6;
  margin-top: -10px;
}

nav {
  margin: 20px 0;
}

nav a {
  color: #aaa;
  margin: 0 10px;
  text-decoration: none;
  text-transform: uppercase;
  font-size: 0.8rem;
  letter-spacing: 2px;
}

nav a.active, nav a:hover {
  color: #fff;
  text-decoration: underline;
}

.hero {
  background: linear-gradient(180deg, #111, #000);
  padding: 100px 20px;
}

.intro {
  padding: 60px 20px;
  max-width: 600px;
  margin: auto;
  line-height: 1.6;
}

.shop {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 40px;
  padding: 40px;
}

.product {
  width: 250px;
  border: 1px solid #222;
  padding: 20px;
  background-color: #0a0a0a;
}

.product img {
  width: 100%;
  height: auto;
  border-bottom: 1px solid #222;
  margin-bottom: 15px;
}

button {
  background: none;
  color: #fff;
  border: 1px solid #fff;
  padding: 8px 16px;
  cursor: pointer;
  transition: 0.3s;
}

button:hover {
  background: #fff;
  color: #000;
}

footer {
  padding: 40px 0;
  opacity: 0.5;
  font-size: 0.8rem;
}
