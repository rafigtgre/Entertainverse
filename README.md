# Entertainverse iconicstream/
├── index.html
├── admin-guide.txt
├── anime/
│   └── index.html
├── comic/
│   ├── index.html
│   └── chapters/      ← (Add folders like `chapter1/`, `chapter2/`)
├── assets/
│   └── style.css
<!DOCTYPE html>
<html>
<head>
  <title>IconicStream</title>
  <link rel="stylesheet" href="assets/style.css">
</head>
<body>
  <h1>🎬 IconicStream</h1>
  <ul>
    <li><a href="anime/index.html">Anime Section</a></li>
    <li><a href="comic/index.html">Comic Section</a></li>
  </ul>
</body>
</html>
ICONICSTREAM - ADMIN GUIDE

📁 ANIME SECTION:
- Edit anime/index.html
- Add <iframe> or <video> tags for video hosting URLs (e.g., Streamtape, Archive.org)

📁 COMIC SECTION:
- Add folders inside /comic/chapters/
- Inside each folder, place page1.jpg, page2.jpg, etc.
- Example: /comic/chapters/naruto/page1.jpg

✅ Add Mihon or external comic sources via JS loader (optional)

🌐 Hosting Support: InfinityFree, GitHub Pages, Netlify, Local browser
<!DOCTYPE html>
<html>
<head>
  <title>Anime</title>
  <link rel="stylesheet" href="../assets/style.css">
</head>
<body>
  <h2>📺 Anime Streaming</h2>
  <p>Add your video links here using <code>&lt;iframe&gt;</code> or <code>&lt;video&gt;</code>:</p>

  <!-- Example embed -->
  <!-- <iframe src="https://archive.org/embed/your-video" width="100%" height="500" allowfullscreen></iframe> -->

  <!-- Add more videos below -->
</body>
</html>
<!DOCTYPE html>
<html>
<head>
  <title>Comic</title>
  <link rel="stylesheet" href="../assets/style.css">
</head>
<body>
  <h2>📚 Comic Reader</h2>
  <p>Upload comic folders inside <code>/chapters/</code> (e.g., <code>/chapter1/</code>)</p>

  <!-- Optional Mihon-style JS or external manga loader can go here -->

  <p>For manual comics, open chapters folder and create one folder per chapter with image files.</p>
</body>
</html>
body {
  font-family: Arial, sans-serif;
  background: #0e0e0e;
  color: #ffffff;
  padding: 20px;
}
a {
  color: #00f7ff;
  text-decoration: none;
}
h1, h2 {
  color: #ffcc00;
}
comic/chapters/naruto/
  ├─ page1.jpg
  ├─ page2.jpg
