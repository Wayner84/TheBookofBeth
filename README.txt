Escape Velocity by HTML5 UP
html5up.net | @ajlkn
Free for personal and commercial use under the CCA 3.0 license (html5up.net/license)

# The Book of Beth

The Book of Beth is a static website that gathers together my creative work—from poetry and short stories to university projects and videos. The site runs on the **Escape Velocity** HTML5 UP theme with a custom green palette that keeps every page visually consistent with the homepage.

## Project Overview

- **Home (`index.html`)** – Introduces Beth, highlights personal stories, and shares quick navigation to key areas of the site.
- **Creative Writing (`creative-writing.html`)** – Lists short fiction and prose pieces. Individual entries live in the `creative-writing/` directory and are loaded dynamically.
- **Poetry (`poetry.html`)** – Curates poetry pieces. Each poem has its own HTML page stored within the `poetry/` directory.
- **University (`university.html`)** – Collects university-related work, including videos such as the “Statistically Speaking” open mic performance.
- **Videos (`videos/`)** – Houses supporting media referenced throughout the site.

## Structure at a Glance

```
assets/           Theme stylesheets, scripts, and fonts
images/           Site imagery (portraits, banners, etc.)
creative-writing/ Individual creative writing pieces
poetry/           Individual poems
university/       University-focused posts and resources
videos/           Video files embedded on the site
style.css         Additional site-wide custom styling
```

## Working Locally

Because the project is a static site, you can preview it without a heavy toolchain:

1. Clone the repository.
2. Open `index.html` in your browser, or start a lightweight web server such as:
   ```bash
   python3 -m http.server
   ```
3. Navigate to `http://localhost:8000` to browse the site.

## Customising Content & Styles

- Add or edit poems and stories by creating new HTML files in the relevant directory and updating the corresponding listing page (`poetry.html`, `creative-writing.html`, etc.).
- Global design tweaks live in `assets/css/main.css`, while bespoke layout adjustments (like the reading log) live in `style.css`. Both stylesheets now share the same darker green palette so that every page inherits the refreshed theme.
- Images and videos should be placed in the `images/` and `videos/` folders respectively, with references updated inside the relevant HTML files.

## Credits & Licences

- Theme: Escape Velocity by HTML5 UP (see licence details above).
- Icons: Font Awesome, included with the theme assets.
- JavaScript utilities: jQuery and Responsive Tools, bundled with the HTML5 UP template.

All written content, photography, and media within this repository are © Beth Holder unless stated otherwise.
