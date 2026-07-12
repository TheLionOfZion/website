<!-- Markdown rendition of the site's home page (index.html) -->

<p align="center">
  <img src="images/hero.png" alt="The Lion Of Zion — האריה מציון" width="320">
</p>

<h1 align="center"><a href="https://thelionofzion.org">TheLionOfZion.org</a></h1>

<p align="center">Email: <a href="mailto:tiger@thelionofzion.org">tiger@thelionofzion.org</a></p>

---

## About this repository

The official website of **The Lion Of Zion** (האריה מציון), a non-profit
organization — served as static files (HTML, CSS, images, self-hosted fonts) via
**GitHub Pages**.

- **Live site:** https://thelionofzion.org
- **Contact:** tiger@thelionofzion.org

### What's here

```
index.html      The home page
style.css       Styling (fluid, viewport-relative layout)
favicon.png     Site icon (lion)
fonts/          Self-hosted Lato 400/700/900 (no external font requests)
images/         Hero artwork (lion + Hebrew banner): hero.webp + hero.png fallback
```

No build step, framework, or tracking scripts — plain static HTML/CSS.
Open `index.html` in a browser to preview locally.

### Deploying

GitHub Pages serves this repository automatically:
**Settings → Pages → Deploy from a branch → `main` / root.**
Any change pushed to `main` redeploys the site in about a minute.
