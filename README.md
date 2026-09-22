# Al Salam Oxygen Plant — Website

Single-page static website for Al Salam Oxygen Plant, Hargeisa, Somaliland.

## Deploy to GitHub Pages (free)

1. Create a new repository on GitHub, e.g. `al-salam-oxygen`.
2. Push this `oxygen-site` folder's contents (or the folder itself) to the repo.
3. On GitHub, go to **Settings → Pages** and choose:
   - Source: `Deploy from a branch`
   - Branch: `main` → folder `/ (root)` (or `/docs` if you placed files there)
4. Save. Your site will be live at `https://<your-username>.github.io/al-salam-oxygen/`.

## After deploy — update these for SEO

- In `index.html`, replace the placeholder canonical URL:
  - `<link rel="canonical" href="https://alsalamoxygen.example.com/" />`
  - Set it to your actual GitHub Pages URL (or your custom domain).
- In `sitemap.xml`, replace `https://alsalamoxygen.example.com/` with your real URL.

## Submit to Google (for indexing)

1. Go to [Google Search Console](https://search.google.com/search-console) and add your site URL.
2. Verify ownership (easiest with the HTML tag or DNS method).
3. Submit your `sitemap.xml` URL so Google crawls and indexes your page.

## Custom domain (optional)

You can buy a domain (e.g. `alsalamoxygen.com`) and point it to GitHub Pages for a cleaner,
more memorable address that also ranks better in local search.
