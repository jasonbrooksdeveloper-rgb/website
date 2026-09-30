A.Shridhar website - recovered from Wayback Machine
Snapshot: https://web.archive.org/web/20250620001514/https://ashridhar.com/
Recovered: 2026-09-30

CONTENTS
- index.html (homepage, restored from index.php)
- about.php, contact.php, testimonials.php, awards-recognition.php
- projects/ (17 project pages, each as projects/<name>/index.html)
  anantara, anantara_abode, anantara_alora, anantara_alpines,
  anantara_imperial, vaikunth, kaveri_soham_vistara,
  kaveri_soham_vivanta, rameshwar_city, trident_elanzza,
  athens, absolute, kalrav_farms, kalrav_trails,
  kalrav_treasure, kalrav_nest, kalrav_seasons
- css/, js/, img/, images/, gif/, video/ (homepage hero videos included)

HOW TO VIEW
Option 1: Double-click index.html to open in browser.
Option 2 (recommended, avoids browser file:// limits):
  cd ashridhar_recovered
  python -m http.server 8000
  Then open http://localhost:8000

NOTES
- PHP files are static HTML snapshots; they open fine as-is. index.html = index.php.
- External CDN links (Bootstrap, jQuery CDN, Google Fonts, Font-Awesome) still load from internet.
- Project sub-images (sliders, maps, certificates, construction updates) were rate-limited by archive.org during recovery (HTTP 429/SSL errors after ~100 requests). The HTML for all project pages is complete; some <img> may 404 locally. Re-run recovery slowly to fill gaps, or browse originals at web.archive.org.
- Homepage videos total ~343MB (alora.mp4 130MB, Kalrav_new.mp4 113MB, etc.).
- 8 missing project CSS files (main64c0.css etc.) were never archived; style6d70.css + device6d70.css (the core) are included.
