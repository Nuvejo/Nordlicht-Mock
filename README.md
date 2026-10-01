# Nordlicht Physiotherapie — Herford

Fiktive Einseiten-Website für eine familiengeführte Physiotherapiepraxis (Familie Brandt, seit 2005).
Demo- und Portfoliostück für **Nuvejo**. Praxis, Team, Adresse und Kontaktdaten sind frei erfunden.

## Öffnen

Doppelklick auf `index.html` genügt — es gibt keinen Build-Schritt.
Für die Google-Maps-Einbettung ist eine Internetverbindung nötig.

Optional über einen lokalen Server (z. B. `npx serve .`), falls das Datei-Protokoll stört.

## Struktur

```
index.html
assets/
  css/styles.css   – Design-Tokens, Layout, Komponenten
  js/main.js       – Navigation, Scroll-Reveals, Buchungsformular
  img/             – Logo (Kopfzeile & Fußzeile), Hero-Foto, Favicon
```

## Technik

- Vanilla HTML/CSS/JS, keine Frameworks, keine Build-Tools
- Buchungsformular in drei Schritten mit clientseitiger Validierung und simuliertem Versand
  (kein Backend, keine Netzwerkanfragen, keine Datenspeicherung)
- Scroll-Reveals über `IntersectionObserver`, deaktiviert bei `prefers-reduced-motion`
- Semantisches HTML, sichtbare Fokuszustände, `aria-live`-Fehlermeldungen, Skip-Link
- Google-Maps-Einbettung ohne API-Schlüssel (`output=embed`)

## Schriften

Fraunces (Überschriften) und Source Sans 3 (Fließtext), geladen über Google Fonts.
