<!DOCTYPE html>
<html lang="tr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <title>Arslan Studio</title>

  <link rel="stylesheet" href="style.css">

  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>

  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">
</head>

<body>

  <nav>
    <h2>Arslan Studio</h2>

    <a target="_blank" href="https://www.instagram.com/arslan_muhammedanil?igsh=MTh4cjd1Mmdobjk4Nw==">
      Instagram
    </a>
  </nav>

  <section class="hero">

    <h1>Web Tasarım & Geliştirme Hizmetleri</h1>

    <p>
      Arslan Studio olarak modern, hızlı ve profesyonel web siteleri tasarlıyoruz.
      İşletmeler ve kişisel markalar için güçlü dijital çözümler sunuyoruz.
    </p>

    <button onclick="alert('Bize Instagram üzerinden ulaşabilirsin!')">
      İletişime Geç
    </button>

  </section>

  <section class="services">

    <h3>Yapabildiklerimiz</h3>

    <ol type="1">
      <li>Modern Web Site Tasarımı</li>
      <li>Mobil Uyumlu Responsive Siteler</li>
      <li>Portföy ve Kişisel Web Siteleri</li>
      <li>UI / UX Tasarım</li>
      <li>Hızlı ve SEO Uyumlu Sayfalar</li>
    </ol>

  </section>
  </body> 
  </html>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: 'Poppins', sans-serif;

  background: linear-gradient(135deg, #0f172a, #1e293b);

  color: white;

  min-height: 100vh;
}

/* NAVBAR */

nav {
  display: flex;

  justify-content: space-between;

  padding: 25px 60px;
}

nav h2 {
  color: #60a5fa;

  font-size: 30px;
}

nav a {
  color: white;

  text-decoration: none;

  background: #2563eb;

  padding: 10px 20px;

  border-radius: 10px;

  transition: 0.3s;
}

nav a:hover {
  transform: scale(1.1);

  background: #1d4ed8;
}

/* HERO */

.hero {
  text-align: center;

  padding: 120px 20px;
}

.hero h1 {
  font-size: 60px;

  margin-bottom: 20px;
}

.hero p {
  font-size: 20px;

  color: #cbd5e1;

  max-width: 700px;

  margin: auto;
}

/* BUTTON */

button {
  margin-top: 30px;

  padding: 15px 40px;

  border: none;

  border-radius: 12px;

  background: #3b82f6;

  color: white;

  font-size: 18px;

  cursor: pointer;

  transition: 0.3s;
}

button:hover {
  transform: scale(1.1);

  background: #2563eb;
}

/* SERVICES */

.services {
  width: 85%;

  margin: 60px auto;

  padding: 40px;

  background: rgba(255,255,255,0.05);

  border-radius: 20px;
}

.services h3 {
  font-size: 30px;

  margin-bottom: 20px;

  color: #60a5fa;
}

.services li {
  margin: 10px 0;

  font-size: 18px;
}

</body>
</html>
