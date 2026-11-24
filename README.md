# MATCHUP – The World of Cricket

A responsive, zero-cost static cricket media website starter built with HTML, CSS and JavaScript.

## Preview locally
Open `index.html` in a browser. For best results, use VS Code with the free Live Server extension, or run `python -m http.server 8000` in this folder and visit `http://localhost:8000`.

## Publish free with GitHub Pages
1. Create a free account at https://github.com/
2. Create a repository named `YOUR-USERNAME.github.io` (replace with your GitHub username).
3. Upload all files and folders from this project to the repository root.
4. Open repository **Settings → Pages**.
5. Under Build and deployment, select **Deploy from a branch**, choose `main` and `/ (root)`, then Save.
6. Wait for deployment. Your website will be at `https://YOUR-USERNAME.github.io/`.
7. Replace `YOUR-USERNAME` in `robots.txt`, `sitemap.xml`, and the canonical/structured metadata in `index.html` with your actual username URL.

## Publish a news story
1. Open `articles.js`.
2. Copy one article object inside the `ARTICLES` array.
3. Change `title`, `category`, `date`, `excerpt`, `image` and `url`.
4. Use categories: `Pakistan`, `PSL`, `International`, or `Transfers` (or add a filter/category deliberately).
5. Upload the updated `articles.js` file to GitHub, replacing the old one. GitHub Pages will publish the change.

This starter displays article cards. To create full article pages, add a separate HTML file for each story and set its `url` to that file. Each full story page should have its own title, meta description, canonical URL, Open Graph metadata and Article JSON-LD.

## Important before launch
- Replace sample/demo stories and fixture placeholders with verified information.
- Replace social URLs and `hello@example.com` with your real links/contact details.
- Replace the logo if you have a final approved brand asset.
- Use images you own, have permission to use, or that are properly licensed. The demo photography is loaded from Unsplash and requires internet access.
- The Google Fonts import and remote demo images require internet access; local fallback fonts and backgrounds are provided.
- GitHub Pages is static hosting: it does not provide a secure private admin panel or server-side database. Never put passwords, API keys or private data in this repository.
- Free hosting and platform terms/limits can change; check GitHub Pages documentation.
