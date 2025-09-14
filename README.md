<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Kabar Sintang</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>Kabar Sintang</h1>
    <nav>
      <a href="#">Beranda</a>
      <a href="#">Kriminal</a>
      <a href="#">Umum</a>
      <a href="#">Hukum</a>
    </nav>
  </header>

  <main>
    <section class="news">
      <article>
        <h2>Judul Berita Pertama</h2>
        <p>Isi singkat berita pertama akan tampil di sini...</p>
      </article>
      <article>
        <h2>Judul Berita Kedua</h2>
        <p>Isi singkat berita kedua akan tampil di sini...</p>
      </article>
    </section>
  </main>

  <footer>
    <p>&copy; 2025 Kabar Sintang | Media Online</p>
  </footer>
</body>
</html>/* Style dasar Kabar Sintang */
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  line-height: 1.6;
  background: #fafafa;
}

header {
  background: #222;
  color: #fff;
  padding: 15px;
  text-align: center;
}

header nav a {
  color: #fff;
  margin: 0 15px;
  text-decoration: none;
  font-weight: bold;
}

header nav a:hover {
  text-decoration: underline;
}

.news {
  padding: 20px;
}

article {
  background: #fff;
  margin-bottom: 15px;
  padding: 15px;
  border-radius: 8px;
  box-shadow: 0 2px 4px rgba(0,0,0,0.1);
}

footer {
  background: #f4f4f4;
  text-align: center;
  padding: 15px;
  font-size: 14px;
}
