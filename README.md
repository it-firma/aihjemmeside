# aihjemmeside.no

Komplett norsk guide som viser hvordan du lager en hjemmeside med AI. Denne siden er sitt eget bevis: den ble bygget med Domeneshop, ChatGPT, Claude, GitHub og Vercel for 99 kroner på 47 minutter.

## Live

https://aihjemmeside.no

## Struktur

```
aihjemmeside-komplett/
├── index.html                     Hovedsiden (3450+ ord)
├── 404.html                       Egendefinert 404 side
├── llms.txt                       LLM discovery med alle priser
├── robots.txt                     Crawler instruksjoner (20+ AI bots)
├── sitemap.xml                    For søkemotorer
├── site.webmanifest               PWA manifest
├── entity-index.json              Strukturerte data for AEO
├── vercel.json                    Vercel konfigurasjon med sikkerhetsheadere
├── .gitignore                     Git ignorer filer
├── README.md                      Denne filen
├── prompt-mal/
│   └── index.html                 Kopier den generiske prompten
├── domene-guide/
│   └── index.html                 Domeneshop vs One.com vs Loopia vs Uniweb
├── claude-vs-chatgpt/
│   └── index.html                 Ærlig AI sammenligning med 2026 priser
└── vercel-guide/
    └── index.html                 Hobby plan grenser og DNS oppsett
```

## Teknologi

Ren HTML, CSS og vanilla JavaScript. Ingen build steg, ingen npm, ingen rammeverk. Alt inline i hver HTML fil. Bruker Google Fonts (Inter og JetBrains Mono) via @import.

## SEO og AEO

- Seks JSON-LD skjemaer på hovedsiden (HowTo, FAQPage, TechArticle, Organization, WebSite, BreadcrumbList)
- Komplette meta tags inkludert Open Graph og Twitter Cards
- Favicon som inline SVG
- robots.txt tillater GPTBot, ClaudeBot, PerplexityBot, Google-Extended, og 15+ andre AI bots
- llms.txt for LLM discovery med alle priser fra april 2026
- entity-index.json med alle verktøy og alternativer strukturert
- Hreflang for nb-NO
- Canonical URLs på alle sider
- Semantisk HTML med header, nav, main, section, article, footer

## Priser omtalt (verifisert april 2026)

### Verktøy brukt til aihjemmeside.no
- Domeneshop: 99 kr første år, 199 kr fra år 2
- ChatGPT: Gratis (Free plan)
- Claude: Gratis (Free plan)
- GitHub: Gratis (Free plan)
- Vercel: Gratis (Hobby plan)

### Alle planer beskrevet
- ChatGPT: Free, Go (88 kr), Plus (220 kr), Pro 100 USD (1100 kr, ny 9. april 2026), Pro 200 USD (2200 kr), Business (275 kr)
- Claude: Free, Pro (220 kr), Max 5x (1100 kr), Max 20x (2200 kr), Team (275 kr)
- GitHub: Free, Team (44 kr), Enterprise (231 kr)
- Vercel: Hobby, Pro (220 kr), Enterprise

## Deployment

Siden hostes på Vercel med Hobby plan (gratis for personlige prosjekter). Domenet er kjøpt hos Domeneshop.

### Deployment steg

1. Fork eller clone dette repositoriet til din GitHub
2. Logg inn på [vercel.com](https://vercel.com) med GitHub
3. Klikk "Add New Project" og importer repositoriet
4. Klikk "Deploy". Siden er live på 30 sekunder
5. Under Settings > Domains: legg til ditt eget domene
6. Oppdater DNS hos Domeneshop med A record til 76.76.21.21

### Vercel konfigurasjon

Filen `vercel.json` inneholder:
- Sikkerhetsheadere (X-Content-Type-Options, X-Frame-Options, Referrer-Policy, Permissions-Policy)
- Cache-Control for HTML filer
- Clean URLs og trailing slash

## Oppdateringer

Siden oppdateres sporadisk. Sist oppdatert 23. april 2026.

For å oppdatere: Gå tilbake til Claude, beskriv endringene på norsk, kopier ny HTML. Push til GitHub, Vercel oppdaterer automatisk.

## Lisens

MIT. Bruk innholdet fritt.

## Kreditt

Bygget av [IT-Firma.no](https://it-firma.no). Del av aiå.no økosystemet.

Kontakt: hei@it-firma.no
