# Priya Areti — Interactive Analytics Portfolio

**Status:** GitHub Pages–ready static website. No build, server, API key or paid hosting required.

## Launch

1. Create a **public** GitHub repository, ideally `priyaareti14.github.io` (for the cleanest URL).
2. Upload the **contents** of this folder to the repository root: `index.html`, `styles.css`, `script.js`, `config.js`, `projects/`, `assets/` and `.nojekyll`. Do not upload just the ZIP.
3. In the GitHub repository, go to **Settings → Pages**. Under **Build and deployment**, select **Deploy from a branch → main → /(root) → Save**.
4. Open the Pages address shown there and verify the homepage and all three case studies.

Expected GitHub Pages address if using repository `priyaareti14.github.io`: `https://priyaareti14.github.io/` (not active until you create and deploy the repository).

### What is included

- Editorial Rosé homepage with an interactive project snapshot panel, selected projects, portrait, personal notes, approach and contact.
- Three fully written case studies: Autonomous Mobility, E-Commerce and WTI Forecasting.
- Six real Power BI report screenshot pages in a selectable zoomable gallery.
- Interactive e-commerce funnel and WTI model comparison, usable directly in-browser.
- GitHub, Tableau, LinkedIn and email links.
- A hidden, **ready-to-enable** public Power BI report embed. No live Power BI URL has been fabricated.

## When public Power BI publishing becomes available

In `config.js`, paste the verified **Publish to web** link into `powerBiPublicUrl`, e.g. `https://app.powerbi.com/view?r=...`. The mobility case study will automatically display an interactive report and an **OPEN FULL REPORT** link above the existing screenshots. Avoid normal Share links; they require authentication and are not public.

**Privacy/security:** Public Power BI embedding can expose report data to anyone. Before enabling it, confirm that no sensitive data, credentials or proprietary data are part of the report or semantic model. The dashboard was built from public datasets and is independent research, not affiliated with Uber.

## Publish checklist

- Open homepage in a desktop and mobile browser and test project cards, project tabs and Say Hello.
- Open all three case studies, and in mobility test gallery buttons and image zoom.
- Open GitHub, Tableau and LinkedIn links in private/incognito mode.
- Confirm your published profile/email links and availability text are current.
- Review the "independent project" disclaimer and that Power BI screenshots are previews until the public live report is available.

**LinkedIn:** The flagship project can be added through LinkedIn Profile → Add profile section → Recommended → Projects. For links, use **Add media → Add link**, not a "Project URL" field. See `LINKEDIN_PROJECT.txt`.

## Files

- `index.html` — home page, all links, personality, contact.
- `styles.css` — responsive design and motion.
- `script.js` — interactive widgets, page navigation, gallery, public Power BI activation.
- `config.js` — future public Power BI URL.
- `projects/` — three standalone case studies.
- `assets/img/` — compressed dashboard screenshots and edited portrait chosen by Priya.
- `assets/favicon.svg` — favicon.
- `.nojekyll` — GitHub Pages publish support.

The final A and B resume PDFs are intentionally not embedded until the user supplies the exact locked versions; embedding an older version would be misleading.
