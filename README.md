# Medonja

Sajt za predstavljanje meda, napravljen u Reactu i TypeScriptu, sa Vite produkcijskom izgradnjom za GitHub Pages.

**Sajt:** https://trbojevicstefan.github.io/medonja/

## Lokalno pokretanje

```sh
npm ci
npm run dev
```

`npm run build` proverava TypeScript i priprema `dist/`. `npm run preview` otvara produkcijski prikaz.

Izmene na grani `main` automatski se objavljuju kroz GitHub Actions.

## Sadržaj i funkcije

- `src/App.tsx` — sadržaj, primeri proizvoda i korpa.
- `src/styles.css` — dizajn i prikaz na različitim ekranima.
- `public/favicon.svg` — ikonica sajta.

Korpa pamti izabrane proizvode lokalno u pregledaču. Tekst upita može da se kopira ili preuzme. Slanje porudžbina i plaćanje još nisu povezani.

Vrste meda su primeri. Pre stvarne prodaje dodati potvrđene proizvode, pakovanja, cene, dostupnost, fotografije, priču brenda i kontakt podatke. Trenutno nema servera niti baze podataka.
