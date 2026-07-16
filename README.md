# ifixIT

Website voor ifixIT (Iris) — PC- en laptopherstellingen, hardware upgrades, software oplossingen en onderhoud in Diepenbeek.

Gebouwd met [Astro](https://astro.build) + [Tailwind CSS v4](https://tailwindcss.com) — statisch gegenereerd voor maximale snelheid en SEO.

## Ontwikkelen

```bash
npm install
npm run dev
```

## Build

```bash
npm run build
npm run preview
```

## Structuur

- `src/pages/` — de pagina's (Home, Diensten, Over mij, FAQ, Contact)
- `src/components/` — Header, Footer, herbruikbare componenten
- `src/layouts/BaseLayout.astro` — gedeelde layout met SEO meta-tags
- `src/assets/` — bronafbeeldingen (automatisch geoptimaliseerd door Astro)
- `public/` — statische bestanden (favicon, robots.txt, og-image)

## Openstaand

- Placeholder-afbeeldingen (foto's van Iris, achtergronden) moeten vervangen worden door echte foto's — zie de blauwe kaders met "Foto volgt".
- `/algemene-voorwaarden/` en `/privacybeleid/` zijn nog lege pagina's.
- Het contactformulier opent de mail-app van de bezoeker (mailto) — er is geen backend. Voor formulierinzendingen zonder mailto kan later een dienst zoals Formspree gekoppeld worden.
