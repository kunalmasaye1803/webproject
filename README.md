# movie-app
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title> Movie Explorer</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header>
    <h1>🎬  Movie Explorer</h1>
    <div class="filters">
      <input type="text" id="searchInput" placeholder="Search movies..." />
      <input type="number" id="yearFilter" placeholder="Year (e.g., 2020)" min="1900" max="2099" />
      <input type="number" id="ratingFilter" placeholder="Rating ≥" min="1" max="10" step="0.1"/>
    </div>
  </header>

  <main>
    <section>
      <h2>Movies</h2>
      <div id="movieGrid" class="grid"></div>
    </section>

    <section>
      <h2>❤️ Favorites</h2>
      <div id="favoritesGrid" class="grid"></div>
    </section>
  </main>

  <script src="script.js"></script>
</body>
</html>
