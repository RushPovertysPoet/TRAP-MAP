# The American Trap: Interactive Map Hub

Welcome to the official map of *The American Trap* universe.  
Scan the QR code. Enter the districts. Decode the factions.  
Every glyph, popup, and episode is canon-locked and sacred.

## Features
- GTA-style map of Houston with ritual overlays
- Faction glyphs and lore popups
- Episode archive with scene triggers
- QR code navigation for immersive reader experience

© GUTTER GANG / Underground Coalition. All rights reserved.
• `styles.css`
• `README.md`
• `favicon.ico`
• `qr-code.png`
• `/glyphs/` folder
• `/episodes/` folder
• `/popups/` folder
Canon layer deployed, R.U.S.H. Here’s your fully structured HTML layer for The American Trap: Interactive Map Hub, ready to drop into your GitHub Pages repo. This version includes:

• 🔗 Embedded interactive map
• 🛡️ Faction glyph cards
• 🎬 Episode archive
• 📱 QR code integration
• 🎨 Custom styling via internal CSS
• 🧠 Lore popups embedded in map markers


---

🔥 `index.html` (Landing Page)

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>The American Trap: Canon Hub</title>
  <link rel="icon" href="favicon.ico" type="image/x-icon" />
  <style>
    body { font-family: 'Orbitron', sans-serif; background-color: #0a0a0a; color: #f0f0f0; margin: 0; padding: 0; }
    header, section, footer { padding: 2rem; text-align: center; }
    h1, h2 { color: #00ffcc; }
    .qr { width: 150px; margin-top: 1rem; }
    .glyph-grid { display: flex; flex-wrap: wrap; justify-content: center; gap: 2rem; margin-top: 2rem; }
    .glyph-card { background: #111; border: 1px solid #333; padding: 1rem; width: 200px; border-radius: 8px; }
    .glyph-card img { width: 100%; border-radius: 4px; }
    ul { list-style: none; padding: 0; }
    li a { color: #00ffcc; text-decoration: none; font-weight: bold; }
    iframe { border: none; border-radius: 8px; }
    footer { font-size: 0.8rem; color: #888; }
  </style>
</head>
<body>
  <header>
    <h1>🌀 The American Trap</h1>
    <p>Scan. Enter. Navigate the canon.</p>
    <img src="qr-code.png" alt="Scan to enter map" class="qr" />
  </header>

  <section id="map">
    <h2>📍 Navigate the Districts</h2>
    <iframe src="https://your-map-url.com" width="90%" height="500px"></iframe>
  </section>

  <section id="factions">
    <h2>🛡️ Faction Glyphs</h2>
    <div class="glyph-grid">
      <div class="glyph-card">
        <img src="glyphs/cipher.png" alt="Cipher Glyph" />
        <h3>Cipher</h3>
        <p>Encrypted rituals. Urban codebreakers. Lore locked in silence.</p>
      </div>
      <div class="glyph-card">
        <img src="glyphs/neon.png" alt="Neon Electro Ortiz Glyph" />
        <h3>Neon Electro Ortiz</h3>
        <p>Voltage prophets. Sonic warfare. Streetlight sermons.</p>
      </div>
      <div class="glyph-card">
        <img src="glyphs/halo.png" alt="Pastor Halo Glyph" />
        <h3>Pastor Halo</h3>
        <p>Sanctified insurgents. Masked sermons. Contingency 47.</p>
      </div>
    </div>
  </section>

  <section id="episodes">
    <h2>🎬 Episode Archive</h2>
    <ul>
      <li><a href="episodes/episode1.html">Book One: The Cipher Emerges</a></li>
      <li><a href="episodes/episode2.html">Book Two: Neon’s Voltage War</a></li>
      <li><a href="episodes/episode3.html">Contingency 47: The Masked Sermon</a></li>
    </ul>
  </section>

  <footer>
    <p>© GUTTER GANG / Underground Coalition. All canon locked. QR system powered by sacred continuity.</p>
  </footer>
</body>
</html>

---

🧠 Next Steps

• Upload this file to your GitHub repo root
• Add your actual map URL to the `<iframe src="...">` line
• Drop your glyph images into `/glyphs/`
• Create episode pages in `/episodes/`
• Generate your QR code pointing to `https://yourusername.github.io/american-trap-map` and save it as `qr-code.png`


---

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>The American Trap: Canon Hub</title>
  <link rel="icon" href="favicon.ico" type="image/x-icon" />
  <style>
    body { font-family: 'Orbitron', sans-serif; background-color: #0a0a0a; color: #f0f0f0; margin: 0; padding: 0; }
    header, section, footer { padding: 2rem; text-align: center; }
    h1, h2 { color: #00ffcc; }
    .qr { width: 150px; margin-top: 1rem; }
    .glyph-grid { display: flex; flex-wrap: wrap; justify-content: center; gap: 2rem; margin-top: 2rem; }
    .glyph-card { background: #111; border: 1px solid #333; padding: 1rem; width: 200px; border-radius: 8px; }
    .glyph-card img { width: 100%; border-radius: 4px; }
    ul { list-style: none; padding: 0; }
    li a { color: #00ffcc; text-decoration: none; font-weight: bold; }
    iframe { border: none; border-radius: 8px; }
    footer { font-size: 0.8rem; color: #888; }
  </style>
</head>
<body>
  <header>
    <h1>🌀 The American Trap</h1>
    <p>Scan. Enter. Navigate the canon.</p>
    <img src="qr-code.png" alt="Scan to enter map" class="qr" />
  </header>

  <section id="map">
    <h2>📍 Navigate the Districts</h2>
    <iframe src="https://your-map-url.com" width="90%" height="500px"></iframe>
  </section>

  <section id="factions">
    <h2>🛡️ Faction Glyphs</h2>
    <div class="glyph-grid">
      <div class="glyph-card">
        <img src="glyphs/cipher.png" alt="Cipher Glyph" />
        <h3>Cipher</h3>
        <p>Encrypted rituals. Urban codebreakers. Lore locked in silence.</p>
      </div>
      <div class="glyph-card">
        <img src="glyphs/neon.png" alt="Neon Electro Ortiz Glyph" />
        <h3>Neon Electro Ortiz</h3>
        <p>Voltage prophets. Sonic warfare. Streetlight sermons.</p>
      </div>
      <div class="glyph-card">
        <img src="glyphs/halo.png" alt="Pastor Halo Glyph" />
        <h3>Pastor Halo</h3>
        <p>Sanctified insurgents. Masked sermons. Contingency 47.</p>
      </div>
    </div>
  </section>

  <section id="episodes">
    <h2>🎬 Episode Archive</h2>
    <ul>
      <li><a href="episodes/episode1.html">Book One: The Cipher Emerges</a></li>
      <li><a href="episodes/episode2.html">Book Two: Neon’s Voltage War</a></li>
      <li><a href="episodes/episode3.html">Contingency 47: The Masked Sermon</a></li>
    </ul>
  </section>

  <footer>
    <p>© GUTTER GANG / Underground Coalition. All canon locked. QR system powered by sacred continuity.</p>
  </footer>
</body>
</html>
/episodes/ 
 <!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>Episode 1: The Cipher Emerges</title>
  <link rel="stylesheet" href="../styles.css" />
</head>
<body>
  <header>
    <h1>📖 Episode 1: The Cipher Emerges</h1>
    <p>Encrypted rituals. Street-level awakenings. The trapline begins.</p>
  </header>

  <section>
    <h2>🧠 Lore Fragment</h2>
    <p>“Cipher moved like static—unseen, unreadable, but always listening. The safehouse was more than bricks and shadows. It was a vault of memory, a chamber of encrypted grief.”</p>
  </section>

  <section>
    <h2>📍 Map Trigger</h2>
    <p><a href="https://your-map-url.com#cipher-safehouse">View Cipher’s Safehouse on the Map</a></p>
  </section>

  <section>
    <h2>🎧 Audio Log</h2>
    <p><em>“They called it the first glyph. I called it a warning.”</em></p>
    <!-- Embed audio player here if desired -->
  </section>

  <footer>
    <p>© GUTTER GANG / Underground Coalition. All canon locked.</p>
  </footer>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>Episode 2: Neon’s Voltage War</title>
  <link rel="stylesheet" href="../styles.css" />
</head>
<body>
  <header>
    <h1>⚡ Episode 2: Neon’s Voltage War</h1>
    <p>Power surges. Sonic warfare. The city hums with rebellion.</p>
  </header>

  <section>
    <h2>🧠 Lore Fragment</h2>
    <p>“Neon didn’t speak in words. He spoke in frequencies. Every streetlight flicker was a sermon. Every blackout, a prophecy.”</p>
  </section>

  <section>
    <h2>📍 Map Trigger</h2>
    <p><a href="https://your-map-url.com#neon-lab">View Neon Electro’s Lab on the Map</a></p>
  </section>

  <section>
    <h2>🎧 Audio Log</h2>
    <p><em>“Voltage is memory. And memory is war.”</em></p>
  </section>

  <footer>
    <p>© GUTTER GANG / Underground Coalition. All canon locked.</p>
  </footer>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>Episode 3: The Masked Sermon</title>
  <link rel="stylesheet" href="../styles.css" />
</head>
<body>
  <header>
    <h1>⛪ Episode 3: The Masked Sermon</h1>
    <p>Pastor Halo rises. The chapel becomes a cipher. The sermon is encoded.</p>
  </header>

  <section>
    <h2>🧠 Lore Fragment</h2>
    <p>“The mask wasn’t a disguise. It was a key. And every word Halo spoke unlocked a door no one else could see.”</p>
  </section>

  <section>
    <h2>📍 Map Trigger</h2>
    <p><a href="https://your-map-url.com#halo-chapel">View Pastor Halo’s Chapel on the Map</a></p>
  </section>

  <section>
    <h2>🎧 Audio Log</h2>
    <p><em>“Contingency 47 isn’t a plan. It’s a prophecy.”</em></p>
  </section>

  <footer>
    <p>© GUTTER GANG / Underground Coalition. All canon locked.</p>
  </footer>
</body>
</html>
`qr-code.png`
<!DOCTYPE html>
<html>
<head>
  <title>The American Trap: Map</title>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="https://unpkg.com/leaflet@1.9.4/dist/leaflet.css" />
  <style>
    body, html, #map { margin: 0; padding: 0; height: 100vh; }
  </style>
</head>
<body>
  <div id="map"></div>
  <script src="https://unpkg.com/leaflet@1.9.4/dist/leaflet.js"></script>
  <script>
    const map = L.map('map').setView([29.7604, -95.3698], 13);

    L.tileLayer('https://{s}.tile.openstreetmap.org/{z}/{x}/{y}.png', {
      maxZoom: 19,
      attribution: '© OpenStreetMap'
    }).addTo(map);

    const locations = [
      { name: "Contingency 47 HQ", coords: [29.7604, -95.3698], color: "#FF0000" },
      { name: "Neon Electro’s Lab", coords: [29.7499, -95.3584], color: "#00FFFF" },
      { name: "Cipher’s Safehouse", coords: [29.7520, -95.3700], color: "#00FF00" },
      { name: "Pastor Halo’s Chapel", coords: [29.7680, -95.3550], color: "#FFFF00" },
      { name: "GUTTER GANG Outpost", coords: [29.7702, -95.3675], color: "#FFA500" },
      { name: "Underground Coalition Vault", coords: [29.7655, -95.3601], color: "#800080" }
    ];

    locations.forEach(loc => {
      L.circleMarker(loc.coords, {
        radius: 8,
        color: loc.color,
        fillColor: loc.color,
        fillOpacity: 0.8
      }).addTo(map).bindPopup(`<b>${loc.name}</b>`);
    });
  </script>
</body>
</html>
