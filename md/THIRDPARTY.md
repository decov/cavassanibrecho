# alguns sites que auxiliaram no desenvolvimento do site

abaixo estão algumas dependências de terceiros que foram utilizados ao decorrer do desenvolvimento do projeto do site do brechó.

- [CMS Filter](https://www.finsweet.com/attributes/cms-filter) - [docs](https://www.finsweet.com/attributes/cms-filter#documentation)

```javascript
<script async src="https://cdn.jsdelivr.net/npm/@finsweet/attributes-cmsfilter@1/cmsfilter.js"></script>
```

---

- [ESLint](https://eslint.org/) - [docs](https://prettier.io/docs/en/index.html) - [github](https://github.com/eslint/eslint)

comando para instalar o ESLint

```
npm init @eslint/config
```

pré-requisitos para instalação do ESLint: [Node.js](https://nodejs.org/en/) ([^12.22.0](https://nodejs.org/download/release/v12.22.0/), [^14.17.0](https://nodejs.org/download/release/v14.17.0/) ou [>=16.0.0](https://nodejs.org/download/release/v16.0.0/)).

```json
{
    "rules": {
        "semi": ["error", "always"],
        "quotes": ["error", "double"]
    }
}
```

---

- [Favicon](https://favicon.io/) - [docs](https://favicon.io/tutorials/)

```html
<link rel="apple-touch-icon" sizes="180x180" href="/apple-touch-icon.png">
<link rel="icon" type="image/png" sizes="32x32" href="/favicon-32x32.png">
<link rel="icon" type="image/png" sizes="16x16" href="/favicon-16x16.png">
<link rel="manifest" href="/site.webmanifest">
```

---

- [Git](https://git-scm.com/) - [docs](https://git-scm.com/doc)

```sh
git clone https://github.com/username/username.github.io
```

---

- [GitHub Pages](https://pages.github.com/) - [docs](https://docs.github.com/pt/pages)

```sh
git clone https://github.com/username/username.github.io
```

```sh
cd username.github.io
echo "Hello World" > index.html
```

```sh
git add --all
git commit -m "Initial commit"
git push -u origin main
```

---

- [gtag.js](https://developers.google.com/analytics/devguides/collection/gtagjs)

instalação da tag do google

```html
<script async src="https://www.googletagmanager.com/gtag/js?id=GA_TRACKING_ID"></script>

<script>
    window.dataLayer = window.dataLayer || [];

    function gtag() {
        window.dataLayer.push(arguments);
    }
    gtag('js', new Date());

    gtag('config', 'GA_TRACKING_ID');
</script>
```

---

- [Meta Tags](https://metatags.io/)

```html
<title>Meta Tags — Preview, Edit and Generate</title>
<meta name="title" content="Meta Tags — Preview, Edit and Generate">
<meta name="description" content="With Meta Tags you can edit and experiment with your content then preview how your webpage will look on Google, Facebook, Twitter and more!">

<meta property="og:type" content="website">
<meta property="og:url" content="https://metatags.io/">
<meta property="og:title" content="Meta Tags — Preview, Edit and Generate">
<meta property="og:description" content="With Meta Tags you can edit and experiment with your content then preview how your webpage will look on Google, Facebook, Twitter and more!">
<meta property="og:image" content="https://metatags.io/assets/meta-tags-16a33a6a8531e519cc0936fbba0ad904e52d35f34a46c97a2c9f6f7dd7d336f2.png">

<meta property="twitter:card" content="summary_large_image">
<meta property="twitter:url" content="https://metatags.io/">
<meta property="twitter:title" content="Meta Tags — Preview, Edit and Generate">
<meta property="twitter:description" content="With Meta Tags you can edit and experiment with your content then preview how your webpage will look on Google, Facebook, Twitter and more!">
<meta property="twitter:image" content="https://metatags.io/assets/meta-tags-16a33a6a8531e519cc0936fbba0ad904e52d35f34a46c97a2c9f6f7dd7d336f2.png">
```

---

- [Node.js](https://nodejs.org/) - [docs](https://nodejs.org/en/docs/) - [github](https://github.com/nodejs/node)

checar versão do seu node

```sh
node -v
```

---

- [npm](https://www.npmjs.com/) - [docs](https://docs.npmjs.com/) - [github](https://github.com/npm/cli)

checar versão do seu npm

```sh
npm -v
```

---

- [Open Graph Protocol](https://ogp.me/)

---

- [Prettier](https://prettier.io/) - [docs](https://eslint.org/docs/latest/user-guide/getting-started) - [github](https://github.com/prettier/prettier)