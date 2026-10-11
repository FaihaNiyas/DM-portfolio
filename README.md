# Salamath Faiha · Portfolio

Personal portfolio of **M.N. Salamath Faiha**, Digital Marketing & SEO Executive (Colombo, Sri Lanka).

A single-page static site: plain HTML, CSS and JavaScript. No build step and nothing to install.

## Files

```
index.html                  The whole site (styles and scripts are inside)
favicon.svg                 Browser tab icon
og-image.jpg                Preview image for WhatsApp / LinkedIn / Facebook shares (1200×630)
robots.txt                  Tells search engines they may index the site
sitemap.xml                 Page list for Google Search Console
.nojekyll                   Tells GitHub Pages to serve files as they are
assets/images/              Profile photo and company logos
```

## Before you publish: set your web address

Open `index.html`, `robots.txt` and `sitemap.xml` and replace every `YOUR-DOMAIN` with your real address, without `https://` and without a trailing slash.

| Where you host | Replace `YOUR-DOMAIN` with |
|---|---|
| GitHub Pages, repo named `USERNAME.github.io` | `USERNAME.github.io` |
| GitHub Pages, any other repo name | `USERNAME.github.io/REPO-NAME` |
| Netlify | `your-site-name.netlify.app` |
| Your own domain | `salamathfaiha.com` (for example) |

`index.html` has it in 5 places near the top, `robots.txt` in 1 and `sitemap.xml` in 1. Until it's set, link previews won't show the share image.

## Host on GitHub Pages (free)

1. Sign in at github.com and click **New repository**.
2. Name it `USERNAME.github.io` (your GitHub username). The site will then be at `https://USERNAME.github.io`. Set it to **Public** and click **Create repository**.
3. Click **uploading an existing file**, then drag in **everything inside this folder** (not the folder itself), including the `assets` folder. Click **Commit changes**.
4. Go to **Settings → Pages**. Under *Build and deployment*, choose **Deploy from a branch**, branch **main**, folder **/ (root)**, then **Save**.
5. Wait 1–2 minutes and open `https://USERNAME.github.io`.

`.nojekyll` is a hidden file. If your computer hides it, the site still works without it.

## Host on Netlify (even quicker)

1. Go to app.netlify.com/drop.
2. Drag this whole folder onto the page. It's live in seconds.
3. Rename the site under **Site configuration → Change site name**.

## After it's live

- **Google Search Console:** add your site, then submit `sitemap.xml` so Google finds it faster.
- **Test the share preview:** paste your link into the LinkedIn Post Inspector or the Facebook Sharing Debugger.
- **Custom domain:** buy one (for example `salamathfaiha.com`), then connect it under GitHub *Settings → Pages → Custom domain* or Netlify *Domain management*.

## Updating

- **Text:** edit `index.html`. All content is in plain HTML below the `<style>` block.
- **Images:** replace files in `assets/images/`, keeping the same file names.
- **Fonts:** load from Google Fonts. **Scroll animations:** use GSAP, loaded from cdnjs. Both need an internet connection; without one the site still works, just with system fonts and no animations.
