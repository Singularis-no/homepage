# Singularis - Nettsider som funker

En moderne, responsiv nettside for Singularis AS - et selskap som leverer skreddersydde nettsider og Shopify-løsninger.

## 🚀 Om prosjektet

Denne nettsiden er bygget med Astro og presenterer Singularis' tjenester på en klar og profesjonell måte. Nettsiden fokuserer på:

- **Enkle, raske nettsider** som fungerer
- **Shopify-prosjekter** med skreddersydde temaer
- **Retainer-pakker** for kontinuerlig forbedring
- **Tydelige priser** og fleksible løsninger

## 🛠️ Teknisk stack

- **Framework**: [Astro](https://astro.build/) v5.14.7
- **Styling**: Vanilla CSS med modulær struktur
- **Fonts**: Inter (Google Fonts)
- **Deployment**: GitHub Pages / Netlify / Vercel

## 📁 Prosjektstruktur

```
/
├── public/
│   └── favicon.svg
├── src/
│   ├── components/          # Astro komponenter
│   │   ├── Header.astro     # Navigasjon og logo
│   │   ├── Hero.astro       # Hovedbanner
│   │   ├── Approach.astro   # "Slik jobber vi"
│   │   ├── Priser.astro     # Priser og pakker
│   │   ├── RetainerPakker.astro # Retainer-pakker
│   │   ├── PrisKort.astro   # Individuelle priskort
│   │   ├── Kontakt.astro    # Kontaktinformasjon
│   │   └── Footer.astro     # Footer med kontaktinfo
│   ├── layouts/
│   │   └── BaseLayout.astro # Grunnleggende layout
│   ├── pages/
│   │   └── index.astro      # Hovedside
│   ├── styles/              # CSS filer
│   │   ├── global.css       # Globale stiler
│   │   ├── header.css       # Header-stiler
│   │   ├── hero.css         # Hero-seksjon
│   │   ├── approach.css     # Approach-seksjon
│   │   ├── priser.css       # Priser-seksjon
│   │   ├── priskort.css     # Pris-kort
│   │   ├── kontakt.css      # Kontakt-seksjon
│   │   └── footer.css       # Footer-stiler
│   └── images/
│       └── logo-small.png
├── astro.config.mjs
├── package.json
└── tsconfig.json
```

## 🚀 Kom i gang

### Forutsetninger

- Node.js 18+
- npm eller yarn

### Installasjon

1. **Klon repositoriet**

   ```bash
   git clone https://github.com/Singularis-no/homepage.git
   cd homepage
   ```

2. **Installer avhengigheter**

   ```bash
   npm install
   ```

3. **Start utviklingsserveren**

   ```bash
   npm run dev
   ```

4. **Åpne i nettleseren**
   ```
   http://localhost:4321
   ```

## 📋 Tilgjengelige kommandoer

| Kommando          | Beskrivelse                                  |
| ----------------- | -------------------------------------------- |
| `npm run dev`     | Starter utviklingsserver på `localhost:4321` |
| `npm run build`   | Bygger produksjonsversjon til `./dist/`      |
| `npm run preview` | Forhåndsviser produksjonsbygg lokalt         |
| `npm run astro`   | Kjører Astro CLI-kommandoer                  |

## 🎨 Design og struktur

### Komponenter

- **Modulær arkitektur** - Hver seksjon er sin egen komponent
- **Responsivt design** - Fungerer på alle skjermstørrelser
- **Semantisk HTML** - God tilgjengelighet og SEO
- **CSS-moduler** - Organiserte stiler per komponent

### Farger og typografi

- **Primærfarge**: Blå toner (#0066CC)
- **Sekundærfarge**: Grå toner (#666666, #999999)
- **Font**: Inter (300, 400, 500, 600, 700)
- **Responsive typografi** med fluid scaling

## 📱 Responsivt design

Nettsiden er optimalisert for:

- **Mobil** (320px+)
- **Tablet** (768px+)
- **Desktop** (1024px+)
- **Stor skjerm** (1440px+)

## 🚀 Deployment

### GitHub Pages

```bash
npm run build
# Upload dist/ mappe til GitHub Pages
```

### Netlify

```bash
npm run build
# Deploy dist/ mappe til Netlify
```

### Vercel

```bash
npm run build
# Deploy dist/ mappe til Vercel
```

## 📞 Kontakt

- **E-post**: kontakt@singularis.no
- **Telefon**: +47 41 10 67 97
- **Nettside**: [singularis.no](https://singularis.no)

## 📄 Lisens

© 2024 Singularis AS. Alle rettigheter forbeholdt.

---

**Utviklet med ❤️ av Singularis AS**
