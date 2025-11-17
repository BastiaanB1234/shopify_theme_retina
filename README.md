# De Notenmarkt Modern Theme

Een moderne Shopify theme gebaseerd op de Retina theme, volledig aangepast voor De Notenmarkt met premium styling en functionaliteit.

## 🎨 Features

- **Moderne Styling**: Gebaseerd op de Retina theme met custom De Notenmarkt branding
- **Custom Fonts**: Playfair Display, Inter, en Dancing Script voor een premium uitstraling
- **Nutritional Table**: Moderne tabbed interface voor voedingswaarde informatie
- **Responsive Design**: Volledig geoptimaliseerd voor mobiel, tablet en desktop
- **Product Pages**: Verbeterde product pagina's met voedingswaarde tabel
- **Custom Colors**: Brown en gold kleurenschema dat past bij noten en zuidvruchten

## 📁 Structuur

```
denotenmarkt_modern/
├── assets/
│   ├── denotenmarkt-custom.css      # Custom styling voor De Notenmarkt
│   ├── nutritional-table.css         # Styling voor voedingswaarde tabel
│   └── styles.scss.css              # Originele Retina theme styles
├── config/
│   ├── settings_data.json           # Theme instellingen
│   └── settings_schema.json         # Theme configuratie schema
├── layout/
│   └── theme.liquid                  # Hoofdlayout met custom fonts
├── snippets/
│   └── nutritional-table.liquid     # Voedingswaarde tabel snippet
├── templates/
│   ├── index.liquid                  # Homepage
│   ├── product.liquid                # Product pagina (met nutritional table)
│   └── ...
└── locales/
    └── nl-bas.json                   # Nederlandse vertalingen
```

## 🚀 Installatie

1. **Upload naar Shopify**:
   - Ga naar Shopify Admin → Online Store → Themes
   - Klik op "Add theme" → "Upload zip file"
   - Of gebruik GitHub Connect voor automatische updates

2. **Configureer Menu's**:
   - Ga naar Online Store → Navigation
   - Maak menu's aan (bijv. "main-menu", "footer")
   - Koppel menu's in Theme Editor → Header sectie

3. **Theme Instellingen**:
   - Ga naar Theme Editor
   - Pas kleuren, fonts en layout aan via Theme Settings
   - Upload hero afbeeldingen voor homepage slideshow

## 🎯 Belangrijke Bestanden

### Custom Styling
- `assets/denotenmarkt-custom.css`: Alle custom styling voor De Notenmarkt branding
- `assets/nutritional-table.css`: Premium styling voor voedingswaarde tabel

### Templates
- `templates/product.liquid`: Product pagina met geïntegreerde nutritional table
- `templates/index.liquid`: Homepage met slideshow en product grid

### Snippets
- `snippets/nutritional-table.liquid`: Tabbed interface voor voedingswaarde informatie

## 🔧 Aanpassingen

### Kleuren Aanpassen
Bewerk `assets/denotenmarkt-custom.css` en pas de CSS variabelen aan:
```css
:root {
  --color-primary-500: #8B4513;  /* Primary brown */
  --color-accent-300: #DAA520;   /* Accent gold */
}
```

### Voedingswaarde Tabel
De tabel wordt automatisch getoond op product pagina's. Data wordt bepaald op basis van product titel (cashew/amandel).

## 📝 Notities

- Theme is gebaseerd op Retina 3.1
- Gebruikt Liquid templating language
- Volledig responsive en mobiel-vriendelijk
- Compatibel met Shopify 2.0 features

## 🔗 GitHub

Repository: https://github.com/BastiaanB1234/denotenmarkt_modern

## 📄 Licentie

Gebaseerd op Retina theme door Out of the Sandbox.
