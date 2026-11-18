# Web Projects Showcase

A collection of three interactive, responsive web applications built with HTML, CSS, and JavaScript. This repository brings together projects for student profile management, online shopping, and browser-based music playback.

## Projects

| Project | File | Description |
|---|---|---|
| **Student Bio Data** | [`Studentbiodata.html`](./Studentbiodata.html) | A job-application-style student profile with academic records, charts, skills, achievements, and a printable biodata layout. |
| **Bazaarly** | [`Brazzarly.html`](./Brazzarly.html) | A demo e-commerce marketplace with product browsing, search, filters, cart, wishlist, coupons, orders, and seller listing screens. |
| **Aurora Music Player** | [`Aurora.html`](./Aurora.html) | A browser music player with local audio imports, playlists, sound controls, visual effects, and ambient soundscapes. |

> The filenames in this README match the uploaded project files. If you rename any HTML file, update the corresponding links here as well.

---

## 1. Student Bio Data

An interactive biodata and student profile page designed around the information commonly requested in a job application.

### Features

- Personal information, contact details, career objective, and profile photo upload.
- Academic records for Class X, Class XII, and graduation.
- Six-semester SGPA inputs and academic progress charts.
- Course information and essential credit tracking, including core courses, electives, laboratory work, projects/internships, and humanities/ethics.
- Skill proficiency indicators and an achievements list.
- Bank details section for demonstration purposes.
- Profile-completeness indicator.
- Light and dark themes.
- Sample-data, clear-form, and print / save-as-PDF controls.

### Technologies

- HTML5, CSS3, and JavaScript
- Tailwind CSS via CDN
- Chart.js 4.4.1
- Google Fonts

The page loads example student data when opened. Replace it with your own test data before using the print feature.

## 2. Bazaarly — Shop & Sell

A storefront-style e-commerce demo for browsing products and trying common shopping and marketplace interactions.

### Features

- Product catalogue with categories and product detail views.
- Product search, price filtering, delivery filtering, and sorting.
- Product variants, specifications, ratings, and review sections.
- Shopping cart with quantity controls and a price summary.
- Wishlist.
- Coupon-code interactions.
- Demo order screens and order tracking interface.
- Seller interface for listing a product.
- Light and dark appearance modes.
- Browser-side persistence for selected shopping data and preferences.

### Technologies

- HTML5
- CSS3
- Vanilla JavaScript
- Browser `localStorage`

Bazaarly is a front-end demonstration. Its product catalogue, reviews, checkout, orders, and seller flows are sample/demo experiences; no real payment gateway, inventory service, shipping provider, or backend is connected.

## 3. Aurora — Music Player

A responsive music player that runs in the browser and can play audio files selected from your device, as well as browser-generated synthesised tracks and ambient sounds.

### Features

- Import audio files or select an audio folder.
- Drag and drop supported audio files into the page.
- Library search and genre/artist filters.
- Play, pause, previous, next, shuffle, repeat, seek, and volume controls.
- Playlists, likes, queue, and smart track ordering.
- Custom synthesised track composer.
- Bass, mid, and treble controls, playback speed, and spatial audio-style effects.
- Ambient soundscapes, including rain, vinyl, waves, and fire.
- Sleep timer and listening-time controls.
- Multiple colour themes and interface styles.
- Audio visualiser and mobile mini-player.
- Keyboard shortcuts and an audio-output/Bluetooth selector where the browser supports it.

### Technologies

- HTML5, CSS3, and JavaScript
- Tailwind CSS via CDN
- Web Audio API
- Browser `localStorage`
- Google Fonts

**Audio-file note:** Imported device audio is handled locally in the browser. The selected files are not uploaded to a server. Re-import local audio after refreshing or reopening the page; browser file references are session-based.

---

## Technologies Across the Repository

- **HTML5** for page structure.
- **CSS3** for layouts, themes, animation, and responsive styling.
- **JavaScript** for interactivity and application behaviour.
- **Tailwind CSS** is loaded from a CDN in Student Bio Data and Aurora.
- **Chart.js** is loaded from a CDN in Student Bio Data.
- **Web Audio API** powers audio playback and sound features in Aurora.

There is no package installation or build step required for the current versions of these projects. An internet connection is needed for the CDN-hosted libraries and Google Fonts used by Student Bio Data and Aurora.

## Run Locally

You can open an HTML file directly in a modern browser. For a more consistent local setup, run a small local web server from the repository folder.

### Option 1: Python

**Windows**

```bash
py -m http.server 8000
```

**macOS / Linux**

```bash
python3 -m http.server 8000
```

Then open:

```text
http://localhost:8000/
```

Choose the project HTML file from the directory listing.

### Option 2: Visual Studio Code

1. Open the repository folder in Visual Studio Code.
2. Install the **Live Server** extension, if you do not already have it.
3. Right-click the HTML file you want to run.
4. Select **Open with Live Server**.

---

## Publish with GitHub Pages

These projects are static HTML pages, so they can be hosted with GitHub Pages.

1. Push the repository and all three HTML files to GitHub.
2. Open the repository on GitHub.
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select your publishing branch (usually `main`) and the `/ (root)` folder.
6. Save the settings and wait for GitHub Pages to publish the site.

### Open each project

After Pages is enabled, the project URLs will follow this pattern:

```text
https://YOUR-USERNAME.github.io/YOUR-REPOSITORY/Studentbiodata.html
https://YOUR-USERNAME.github.io/YOUR-REPOSITORY/Brazzarly.html
https://YOUR-USERNAME.github.io/YOUR-REPOSITORY/Aurora.html
```

Replace `YOUR-USERNAME` and `YOUR-REPOSITORY` with your GitHub username and repository name.

**Important:** The uploaded files do not include a root `index.html`. The three project pages can still be opened using the URLs above, but the repository's root Pages URL will need an `index.html` landing page if you want visitors to see a homepage with links to all three projects.

---

## Repository Structure

Keep the three HTML files and this README in the repository root:

```text
web-projects-showcase/
├── README.md
├── Studeuntbiodata.html
├── Brazzarly.html
└── Aurora.html
```

## Privacy and Demo Limitations

- These are front-end projects; no application backend or database is included.
- Bazaarly's checkout and order-related screens are demonstrations, not real commerce or payment processing.
- Student Bio Data includes personal and bank-detail fields for demonstrating a biodata layout. **Do not enter real personal, identity, or bank information on a publicly hosted demo.** Use fictional sample data, especially when sharing screenshots or the live site.
- Aurora plays audio selected by the visitor in their own browser; it does not provide a hosted music catalogue.
- Some features, such as audio output selection, depend on browser and device support.

## Contributing

Suggestions and improvements are welcome. To contribute:

1. Fork the repository.
2. Create a branch for your change.
3. Make and test your updates in a browser.
4. Submit a pull request describing what changed.

## License

No license has been specified for this repository. Add a `LICENSE` file if you intend to grant others permission to reuse, modify, or distribute the code.
