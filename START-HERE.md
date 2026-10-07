# Difference / BrandistiQ — start here

Ovo je čista početna verzija projekta. Ne koristi postojeći GitHub repository `difference-seo-web`.

## 1. Napravi novi GitHub repository

Preporučeni naziv:

`difference-usluge-web`

Repozitorij ostavi prazan (bez README-a, .gitignore-a ili licence).

## 2. Upload projekta

Raspakiraj ZIP i prenesi sadržaj projekta u novi repository tako da su `package.json`, `astro.config.mjs`, `netlify.toml` i mapa `src` u rootu repozitorija.

## 3. Netlify

Na Netlifyju napravi novi site iz tog novog GitHub repositoryja.

Build command:

`npm run build`

Publish directory:

`dist`

Node je već definiran u `netlify.toml` kao 22.

## 4. Važno

Ne povezuj ovaj projekt s postojećim `difference-seo-web` repositoryjem. Stari repository više ne koristimo za ovu verziju.

## 5. Sadržaj

Tekstovi su u `src/content/`:

- `src/content/usluge/`
- `src/content/projekti/`
- `src/content/vodic/`

Nove vodiče i projekte možemo kasnije dodavati bez diranja postojeće strukture ruta.
