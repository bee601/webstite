# NightfallNetwork — Minecraft Server Website

Eine moderne, ansprechende Website für den NightfallNetwork Minecraft-Server. Mit dunklem Design, Cyan-Accents und interaktiven Elementen.

## Features

✨ **Modernes Design**
- Dunkles Theme mit Cyan & Purple Accents
- Animierte Hintergrund-Partikel
- Responsive Design (mobile-friendly)
- Smooth Scrolling & Hover-Effekte

🎮 **Minecraft-Spezifische Inhalte**
- Server-Status anzeigen (Online-Spieler)
- Server IP zum Kopieren
- How-to-Join Guide (4 Schritte)
- Feature-Showcase
- Discord-Integration

⚡ **Technologie**
- Reines HTML/CSS/JavaScript (keine Abhängigkeiten!)
- Optimiert für Performance
- Cross-Browser kompatibel

## Schnellstart

1. **Repository klonen:**
```bash
git clone https://github.com/dein-username/nightfallnetwork.git
cd nightfallnetwork
```

2. **Lokal testen:**
Einfach `index.html` im Browser öffnen oder einen lokalen Server verwenden:
```bash
# Mit Python 3
python -m http.server 8000

# Mit Node.js/Live Server
npx live-server
```

3. **Im Browser öffnen:**
```
http://localhost:8000
```

## Customization

### Server IP ändern
Ersetze `nightfallnetwork.xyz` überall in der Datei mit deiner Server-IP:
```html
<!-- In der HTML Datei suchen und ersetzen -->
nightfallnetwork.xyz → deine-server-ip.de
```

### Farben anpassen
Änder die CSS-Variablen oben in der Datei:
```css
:root {
    --primary: #00d4ff;      /* Cyan */
    --accent: #a855f7;       /* Purple */
    --bg-dark: #0a0e27;      /* Dunkelblau */
    /* ... */
}
```

### Links aktivieren
- **Discord-Button**: Ersetze `alert()` mit deinem Discord-Link
- **Store-Button**: Ergänz deinen Shop-Link
- **Header-Logo**: Ändere die onclick-Funktion

## Struktur

```
├── index.html          # Haupt-Website (alles in einer Datei)
├── README.md           # Diese Datei
└── LICENSE             # MIT License
```

## Browser-Support

- Chrome/Chromium ✅
- Firefox ✅
- Safari ✅
- Edge ✅
- Mobile Browser ✅

## Performance

- **Dateigröße:** ~15 KB (minified HTML)
- **Ladezeit:** < 1 Sekunde (mit Bildern)
- **Lighthouse Score:** 90+

## Deployment

### Auf GitHub Pages
1. Repository auf GitHub pushen
2. In Einstellungen → Pages
3. Branch auswählen (main/master)
4. Fertig! Verfügbar unter: `https://dein-username.github.io/nightfallnetwork/`

### Auf einem eigenen Server
1. `index.html` auf den Server hochladen
2. Custom Domain einrichten
3. HTTPS aktivieren

## Anpassungen vom Original

Diese Website ist inspiriert von der originalen NightfallNetwork-Website und enthält:
- ✅ Alle visuellen Elemente
- ✅ Alle Funktionen (IP-Kopieren, etc.)
- ✅ Responsive Design
- ✅ Animationen
- ✅ Dark Theme

## Lizenz

MIT License - Frei verwendbar für persönliche und kommerzielle Projekte

## Support

Fragen? Issues? Erstell ein GitHub Issue oder kontaktiere direkt!

---

**Made with ❤️ für die Gaming-Community**
