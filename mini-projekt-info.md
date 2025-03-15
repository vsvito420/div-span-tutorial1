# Mini-Projekt: Persönliche Profilseite

## Übersicht

Dieses Mini-Projekt bietet eine Vorlage für eine persönliche Profilseite mit semantischem HTML und CSS. Die Seite ist so gestaltet, dass sie leicht anpassbar ist und gleichzeitig moderne Webstandards einhält.

## Semantisches HTML

Die Vorlage verwendet semantische HTML-Elemente, die die Struktur und Bedeutung des Inhalts klar definieren:

| Element | Verwendung | Vorteil |
|---------|------------|---------|
| `<header>` | Kopfbereich der Seite | Definiert den Einführungsbereich der Seite |
| `<nav>` | Navigationsmenü | Kennzeichnet Navigationslinks |
| `<main>` | Hauptinhalt | Umschließt den Hauptinhalt der Seite |
| `<section>` | Thematische Abschnitte | Gruppiert zusammengehörige Inhalte |
| `<article>` | Eigenständiger Inhalt | Für in sich geschlossene Inhalte wie das Kontaktformular |
| `<figure>` | Medieninhalt | Für Bilder mit optionaler Beschreibung |
| `<fieldset>` | Formulargruppen | Gruppiert zusammengehörige Formularelemente |
| `<footer>` | Fußbereich | Enthält Informationen zum Dokument |

### Vorteile semantischer HTML-Elemente:

1. **Bessere Zugänglichkeit**: Screenreader und andere Hilfstechnologien können die Struktur der Seite besser verstehen.
2. **Verbesserte SEO**: Suchmaschinen können den Inhalt besser interpretieren.
3. **Klarere Codestruktur**: Der Code ist leichter zu verstehen und zu warten.
4. **Zukunftssicherheit**: Semantisches HTML ist ein Standard, der langfristig unterstützt wird.

## CSS-Styling

Die Vorlage enthält bereits ein responsives Design mit:

- Flexbox für flexible Layouts
- Farbkodierung für visuelle Hierarchie
- Hover-Effekte für interaktive Elemente
- Abgerundete Ecken und Schatten für ein modernes Aussehen

## Anpassungsmöglichkeiten

### Grundlegende Anpassungen:

1. **Persönliche Informationen**: Ersetze die Platzhalter mit deinen eigenen Daten.
2. **Profilbild**: Füge dein eigenes Bild ein, indem du den Platzhalter ersetzt:
   ```html
   <figure class="profile-image">
     <img src="dein-bild.jpg" alt="Dein Name">
   </figure>
   ```
3. **Farbschema**: Passe die Farben an, indem du die CSS-Variablen änderst:
   ```css
   :root {
     --primary-color: #4CAF50; /* Ändere diese Farbe */
     --secondary-color: #333;  /* Ändere diese Farbe */
   }
   ```

### Erweiterte Anpassungen:

1. **Neue Abschnitte**: Füge weitere Abschnitte hinzu, z.B. für Lieblingsbücher oder Filme:
   ```html
   <section id="lieblingsbuecher">
     <h2>Meine Lieblingsbücher</h2>
     <ul>
       <li>Buchtitel 1</li>
       <li>Buchtitel 2</li>
     </ul>
   </section>
   ```

2. **Medieneinbindung**: Füge Videos oder andere Medien ein:
   ```html
   <section id="videos">
     <h2>Meine Videos</h2>
     <figure>
       <video controls>
         <source src="mein-video.mp4" type="video/mp4">
         Dein Browser unterstützt keine Videos.
       </video>
       <figcaption>Beschreibung des Videos</figcaption>
     </figure>
   </section>
   ```

3. **Social Media Links**: Erweitere den Kontaktbereich mit Social-Media-Links:
   ```html
   <div class="social-links">
     <a href="https://instagram.com/dein_benutzername" aria-label="Instagram">
       <i class="fa fa-instagram"></i> Instagram
     </a>
     <a href="https://twitter.com/dein_benutzername" aria-label="Twitter">
       <i class="fa fa-twitter"></i> Twitter
     </a>
   </div>
   ```

## Tipps für die Weiterentwicklung

1. **Responsive Design**: Teste deine Seite auf verschiedenen Geräten und Bildschirmgrößen.
2. **Barrierefreiheit**: Stelle sicher, dass alle Bilder Alt-Texte haben und die Seite mit der Tastatur navigierbar ist.
3. **Performance**: Optimiere Bilder und halte den Code schlank.
4. **Validierung**: Überprüfe deinen HTML- und CSS-Code mit dem [W3C Validator](https://validator.w3.org/).

## Weiterführende Ressourcen

- [MDN Web Docs: HTML-Elemente](https://developer.mozilla.org/de/docs/Web/HTML/Element)
- [MDN Web Docs: CSS-Referenz](https://developer.mozilla.org/de/docs/Web/CSS/Reference)
- [W3C: HTML5-Spezifikation](https://www.w3.org/TR/html52/)
- [Web Accessibility Initiative (WAI)](https://www.w3.org/WAI/)

---

Viel Spaß beim Anpassen und Erweitern deiner persönlichen Profilseite!
