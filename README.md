# Dawit Zeleke Admassu — Portfolio

Personal portfolio site: PhD research, industry experience, publications, and professional credentials.

## Structure

This is a single self-contained static HTML file — no build step, no dependencies, no package manager.

```
.
├── index.html   # the entire site (HTML + CSS + JS inlined)
└── README.md
```

Everything the page needs — styles, the dark/light mode script, and the favicon — is inlined directly in `index.html`. The only external resource it loads is the JetBrains Mono font from Google Fonts.

## Publishing with GitHub Pages

1. Create a new GitHub repository and add these two files at its root (`index.html` must be at the repo root, not in a subfolder, for GitHub Pages' default setup).
2. Push to GitHub.
3. In the repo, go to **Settings → Pages**, set **Source** to your default branch (e.g. `main`) and folder `/ (root)`, then save.
4. GitHub will publish the site at `https://<your-username>.github.io/<repo-name>/` (or your custom domain, if configured).

## After publishing

Once the site has its permanent URL, update these two lines near the top of `index.html` (currently placeholders pointing at this draft's temporary link):

```html
<link rel="canonical" href="...">
<meta property="og:url" content="...">
```

If you set up a custom domain through GitHub Pages, add a `CNAME` file at the repo root containing just that domain name (GitHub's Pages settings page will prompt you for this).

## Local preview

No server required — just open `index.html` directly in a browser, or serve it locally:

```
python3 -m http.server 8000
```

then visit `http://localhost:8000`.


=================================================================================

Sure, man. Here’s the **remaining checklist** from where we are now:

### ✅ DONE — Website

* [x] Portfolio design/content
* [x] GitHub repository
* [x] GitHub Pages deployment
* [x] `dawitzeleke.com` domain
* [x] `www.dawitzeleke.com`
* [x] DNS configuration
* [x] HTTPS / SSL
* [x] Enforce HTTPS
* [x] Canonical URL → `https://dawitzeleke.com`
* [x] Open Graph URL → `https://dawitzeleke.com`
* [x] All website links tested

### ✅ DONE — Google

* [x] Google Search Console property created
* [x] Domain ownership verified
* [x] TXT verification record added
* [x] Search Console dashboard working

### 🟡 OPTIONAL — Google SEO

* [ ] **URL Inspection → request indexing** for `https://dawitzeleke.com/`
* [ ] Wait for Google to collect search data (Search Console currently says data is processing and to check again in about a day). 
* [ ] Later check whether your site appears in Google Search

### 🟢 OPTIONAL — Professional finishing

* [ ] Add website URL to LinkedIn
* [ ] Add website URL to résumé/CV
* [ ] Add website to email signature
* [ ] Make sure Google Scholar / ResearchGate / LinkedIn links are correct
* [ ] Eventually review Google search appearance

**Bottom line:** Nothing is broken or incomplete. Your portfolio is **live and ready to share now**.

The only thing I'd personally do next is **URL Inspection → Request Indexing**. After that, you're done.

