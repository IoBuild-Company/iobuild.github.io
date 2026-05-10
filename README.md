# IoBuild - Landing Page

SaaS platform specialized in IoT devices for construction companies. Informative landing page with translation system, responsive design, and modern animations.

## 📌 Description

IoBuild is a landing page for an IoT SaaS platform focused on the construction industry. The site showcases the benefits, technical features, testimonials, and pricing plans of the platform.

## ⚙️ Technologies

- **HTML5** - Semantic structure
- **CSS3** - Styles with CSS variables and responsive design
- **JavaScript Vanilla** - Interactivity without frameworks
- **Google Fonts** - Typography (Poppins, Roboto)
- **Font Awesome 6.3** - Icons

## 📁 Project Structure

```
landing_page/
├── index.html           # Main page
├── about-us.html        # About Us page
├── faq.html             # Frequently Asked Questions page
├── styles/
│   ├── reset.css        # CSS reset
│   └── style.css        # Main styles
├── scripts/
│   └── script.js        # JavaScript functionality
└── assets/
    ├── translations.json    # i18n translations
    └── images/              # Graphic assets
```

## 📄 Pages

### index.html
Main page with:
- Hero section
- Benefits section
- Technical features
- Testimonials
- Pricing plans
- Final CTA
- Complete footer

### about-us.html
Corporate page with:
- Company mission
- Values
- Team members

### faq.html
Help page with:
- Frequently asked questions organized by categories
- Interactive accordion

## 🛠️ Features

- **Responsive Design** - Adaptable to mobile devices, tablets, and desktop
- **i18n System** - Support for Spanish and English with JSON translations
- **Scroll Animations** - Fade-in effects when scrolling
- **Lazy Loading** - Deferred image loading
- **Mobile Menu** - Hamburger navigation for mobile devices
- **SEO Optimized** - Meta tags, Open Graph, and Schema.org
- **Accessibility** - ARIA attributes and keyboard navigation
- **Smooth Navigation** - Smooth scrolling between sections

## 🧑‍💻 Installation

1. Clone or download the repository
2. Open `index.html` in a browser
3. No server required for development (works with local files)

## ⚙️ Configuration

### 🔠 Translations

The `assets/translations.json` file contains all translations:

```json
{
  "en": {
    "index": { ... },
    "about": { ... },
    "faq": { ... },
    "common": { ... }
  },
  "es": {
    "index": { ... },
    "about": { ... },
    "faq": { ... },
    "common": { ... }
  }
}
```

### Default Language

Change the default language in `scripts/script.js`:

```javascript
let currentLang = 'en'; // Change to 'es' for Spanish
```

## 🎨 Customization

### Colors

The main colors are defined as CSS variables in `styles/style.css`:

```css
:root {
  --color-primary: #your-color;
  --color-secondary: #your-color;
  /* ... */
}
```

### Fonts

Fonts are loaded from Google Fonts in the `<head>` of each page. Modify in the HTML files.

### Images

Project images should be replaced in:
- `assets/images/logo.png` - Logo
- `assets/images/hero-dashboard.png` - Hero image
- `assets/images/testimonies/` - Testimonial photos
- `assets/images/team/` - Team photos

## 👥 Team
1. [Jhosep Argomedo](https://github.com/JhosepAC)
2. [Sebastian Ramirez](https://github.com/SRT0808)
3. [Axel Ordoñez](https://github.com/nOOmzzzz)
4. [Fabrizio Panta](https://github.com/F4brizio24)
5. [Brayan Ccarita](https://github.com/hallzyx)
