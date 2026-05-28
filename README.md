# Buurtsuper Goethals — Website met CMS

## Wat zit er in deze map?

```
goethals-site/
├── index.html          ← De website zelf
├── netlify.toml        ← Netlify instellingen
├── admin/
│   ├── index.html      ← Het beheerpaneel
│   └── config.yml      ← Wat er bewerkbaar is
└── content/
    ├── algemeen.json   ← Winkelnaam, adres, etc.
    ├── openingstijden.json
    ├── hero.json
    └── over.json
```

## Hoe online zetten (stap voor stap)

### 1. GitHub account aanmaken
Ga naar github.com en maak een gratis account aan.

### 2. Nieuwe repository aanmaken
- Klik op "New repository"
- Naam: `goethals-site`
- Klik "Create repository"
- Upload alle bestanden uit deze map

### 3. Netlify koppelen
- Ga naar netlify.com en maak een gratis account
- Klik "Add new site" → "Import an existing project"
- Kies GitHub en selecteer `goethals-site`
- Klik "Deploy site"

### 4. CMS activeren
- Ga in Netlify naar: Site settings → Identity → Enable Identity
- Scroll naar "Git Gateway" → Enable Git Gateway
- Ga naar Identity → Invite users → voer het e-mailadres van de klant in

### 5. Klant kan nu inloggen
- De klant gaat naar: jouwsite.netlify.app/admin
- Logt in met het e-mailadres
- Kan teksten, openingstijden en reviews aanpassen

## Wat kan de klant zelf aanpassen?
✓ Openingstijden
✓ Teksten op de pagina
✓ Klantbeoordelingen toevoegen/verwijderen
✓ Webshop categorieën beheren
✓ Contactgegevens

## Wat kan de klant NIET zelf aanpassen?
✗ De lay-out en het design (dat is goed zo, dan blijft het er mooi uitzien)
✗ Foto's in de hero (die kun je wel handmatig vervangen)
