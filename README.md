# Hanieh Motamedi · Portfolio

A bilingual (English / فارسی) personal portfolio for Hanieh Motamedi (حانیه معتمدی), a psychology student with a passion for painting and visual art.

It is a plain static site with no build step and no external dependencies: fonts, images, styles and scripts are all local.

```
index.html
css/style.css
js/main.js
assets/images/   (12 .webp images)
assets/fonts/    (7 .woff2 fonts)
.nojekyll
README.md
```

## Language

English is the default. Use the "فارسی" button in the menu, or open the page with `#fa` or `?lang=fa` at the end of the address, to start in Persian. All text lives in the `I18N` dictionary in `js/main.js`.

## Contact details

Open `js/main.js` and fill in the `CONTACT` object at the very top:

```js
var CONTACT = {
  email: "name@example.com",
  instagram: "full link to the Instagram profile",
  linkedin: "full link to the LinkedIn profile"
};
```

Each item shows only when it is filled in. While all three are empty, the card reads "Contact details coming soon."

## Publish on GitHub Pages

1. Create a new public repository on GitHub (for example `hanieh-portfolio`).
2. Upload all files, keeping the folders as they are (`css`, `js`, `assets/images`, `assets/fonts`), including the empty `.nojekyll` file.
3. In the repository, open **Settings > Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**, select branch **main** and folder **/ (root)**, then **Save**.
5. After a minute the site is live at `your-username.github.io/hanieh-portfolio/`.
