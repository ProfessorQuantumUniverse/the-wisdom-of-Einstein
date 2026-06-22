> ## 📦 This project has moved
>
> **The Wisdom of Einstein** is now part of the **[toolsperiments](https://github.com/ProfessorQuantumUniverse/toolsperiments)** collection.
>
> - 🌐 **Live demo:** https://professorquantumuniverse.github.io/toolsperiments/einstein-wisdom/
> - 📂 **Source:** https://github.com/ProfessorQuantumUniverse/toolsperiments/tree/main/einstein-wisdom
>
> This repository is **archived** and no longer maintained here.

---

# Die Weisheit Einsteins | The Wisdom of Einstein

Eine moderne, immersive Web-App, die Albert Einstein und andere große Wissenschaftler ehrt.

A modern, immersive web app honoring Albert Einstein and other great scientists.

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)

## ✨ Features / Funktionen

### 🎲 Zufallszitate / Random Quotes
Die App zeigt inspirierende Zitate über Zukunft, Wissenschaft, Neugier und Fortschritt.

The app displays inspiring quotes about future, science, curiosity, and progress.

### 🎯 Themenfilter / Theme Filters
Nutzer können Zitate nach Themen durchsuchen:
- 🔬 Physik / Physics
- 💭 Philosophie / Philosophy
- 💪 Motivation
- 😄 Humor
- 🔭 Wissenschaft / Science
- 🤔 Neugier / Curiosity
- 🚀 Zukunft / Future

### 🎨 Immersives Design / Immersive Design
- Moderner Look mit dunklem Hintergrund
- Leuchtende Akzente (Blau/Violett, futuristisch)
- Animierte Übergänge und Parallax-Effekte
- Header mit Einstein-Porträt
- Schwebende Partikel und animierter Sternenhimmel

Modern look with dark background, glowing accents (blue/violet, futuristic), animated transitions, parallax effects, header with Einstein portrait, floating particles, and animated starry sky.

### 🎪 Interaktive Features / Interactive Features
- **Zitat des Tages** / Quote of the Day: Täglich wechselndes inspirierendes Zitat
- **Teilen-Funktion** / Share Feature: Zitate einfach teilen
- **Favoriten** / Favorites: Zitate speichern und später wiederfinden
- **Zufallszitat-Button** / Random Quote Button: Mit animierter Overlay-Anzeige
- **🌍 Mehrsprachigkeit** / Multilingual: Deutsch/Englisch Umschaltung

### 📱 Responsive Design
Optimiert für Desktop, Tablet und Mobile-Geräte.

Optimized for desktop, tablet, and mobile devices.

## 🚀 Installation & Usage / Nutzung

### Schnellstart / Quick Start

1. **Repository klonen / Clone the repository:**
   ```bash
   git clone https://github.com/ProfessorQuantumUniverse/the-wisdom-of-Einstein.git
   cd the-wisdom-of-Einstein
   ```

2. **Öffnen / Open:**
   Öffnen Sie einfach die `index.html` Datei in Ihrem Browser.
   
   Simply open the `index.html` file in your browser.

   **Oder starten Sie einen lokalen Server / Or start a local server:**
   ```bash
   # Python 3
   python -m http.server 8000
   
   # Python 2
   python -m SimpleHTTPServer 8000
   
   # Node.js (mit npx)
   npx http-server
   ```

3. **Im Browser öffnen / Open in browser:**
   ```
   http://localhost:8000
   ```

## 📂 Projektstruktur / Project Structure

```
the-wisdom-of-Einstein/
├── index.html          # Haupt-HTML-Datei / Main HTML file
├── styles.css          # Styling und Animationen / Styling and animations
├── app.js              # JavaScript-Logik / JavaScript logic
├── quotes.json         # Zitate-Datenbank / Quotes database
├── README.md           # Dokumentation / Documentation
└── LICENSE             # MIT Lizenz / MIT License
```

## 🎯 Technische Details / Technical Details

### Frontend-Technologien / Frontend Technologies
- **HTML5**: Semantisches Markup
- **CSS3**: 
  - CSS Grid & Flexbox für Layout
  - CSS Animationen und Transitions
  - CSS Custom Properties (Variablen)
  - Responsive Design mit Media Queries
- **Vanilla JavaScript (ES6+)**:
  - Async/Await für Datenladung
  - LocalStorage für Persistenz
  - Intersection Observer API für Scroll-Animationen
  - Web Share API für Social Sharing

### Kein Backend erforderlich / No Backend Required
Alle Daten werden aus der `quotes.json` Datei geladen. Die App läuft vollständig im Browser.

All data is loaded from the `quotes.json` file. The app runs entirely in the browser.

## 🎨 Anpassung / Customization

### Eigene Zitate hinzufügen / Add Custom Quotes

Bearbeiten Sie die `quotes.json` Datei:

Edit the `quotes.json` file:

```json
{
  "quotes": [
    {
      "id": 31,
      "author": "Neuer Wissenschaftler / New Scientist",
      "textDE": "Deutsches Zitat",
      "textEN": "English quote",
      "category": "physics",
      "themes": ["physics", "motivation"]
    }
  ]
}
```

### Farbschema ändern / Change Color Scheme

Bearbeiten Sie die CSS-Variablen in `styles.css`:

Edit the CSS variables in `styles.css`:

```css
:root {
    --primary-color: #6366f1;
    --secondary-color: #8b5cf6;
    --accent-color: #0ea5e9;
    /* ... weitere Farben / more colors */
}
```

## 🌟 Features im Detail / Features in Detail

### Zitat des Tages / Quote of the Day
- Ändert sich täglich automatisch / Changes automatically daily
- Wird im LocalStorage gespeichert / Stored in LocalStorage
- Kann geteilt und favorisiert werden / Can be shared and favorited

### Favoriten-System / Favorites System
- Speicherung im Browser (LocalStorage)
- Persistiert zwischen Sessions
- Einfaches Hinzufügen/Entfernen mit ❤️-Button

### Animationen / Animations
- Sanfte Übergänge bei Interaktionen / Smooth transitions
- Scroll-reveal Effekte / Scroll-reveal effects
- Schwebende Partikel / Floating particles
- Animierter Sternenhimmel / Animated starry background
- Pulsierender Glow-Effekt / Pulsing glow effects

### Teilen-Funktion / Share Function
- Native Web Share API (mobile)
- Fallback: Kopieren in Zwischenablage / Clipboard fallback
- Mit visueller Bestätigung / With visual confirmation

## 🔮 Erweiterungsmöglichkeiten / Extension Possibilities

Das Projekt ist erweiterbar für:
- Weitere Wissenschaftler hinzufügen
- Mehr Sprachen (Französisch, Spanisch, etc.)
- Audio-Quotes (Text-to-Speech)
- Benutzer-Kommentare
- Quiz-Modus
- Dark/Light Mode Toggle
- Export-Funktion für Favoriten

The project can be extended with:
- Add more scientists
- More languages (French, Spanish, etc.)
- Audio quotes (text-to-speech)
- User comments
- Quiz mode
- Dark/Light mode toggle
- Export function for favorites

## 🐛 Browser-Kompatibilität / Browser Compatibility

Getestet und kompatibel mit / Tested and compatible with:
- ✅ Chrome 90+
- ✅ Firefox 88+
- ✅ Safari 14+
- ✅ Edge 90+
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## 📜 Lizenz / License

MIT License - siehe [LICENSE](LICENSE) Datei für Details.

MIT License - see [LICENSE](LICENSE) file for details.

## 👨‍🔬 Wissenschaftler in der App / Scientists in the App

Die App enthält Zitate von / The app contains quotes from:
- Albert Einstein
- Marie Curie
- Stephen Hawking
- Carl Sagan
- Isaac Newton
- Nikola Tesla
- Galileo Galilei
- Richard Feynman
- Max Planck
- Werner Heisenberg

## 🙏 Danksagung / Acknowledgments

Inspiriert von den großen Köpfen der Wissenschaft, die unser Verständnis des Universums geformt haben.

Inspired by the great minds of science who have shaped our understanding of the universe.

## 📧 Kontakt / Contact

Bei Fragen oder Vorschlägen öffnen Sie bitte ein Issue auf GitHub.

For questions or suggestions, please open an issue on GitHub.

---

**Erstellt mit Begeisterung für Wissenschaft und Inspiration** 🚀⚛️🌌

**Created with passion for science and inspiration** 🚀⚛️🌌
