# HTML & CSS Grundlagen: Block- und Inline-Elemente

## Lernziele
- GitHub Repository forken und klonen
- Block- und Inline-Elemente in HTML verstehen und anwenden
- DIV- und SPAN-Elemente korrekt einsetzen
- HTML-Klassen zur Gestaltung verwenden
- Semantische HTML-Elemente kennenlernen
- Das CSS Box-Modell verstehen und anwenden
- Elemente mit CSS zentrieren

## Zeitplan (1,5 Stunden)
1. Einführung & Ziele (5 Min)
2. GitHub Repository forken (10 Min)
3. HTML Grundlagen: Block vs. Inline (10 Min)
4. DIV-Element Übung (15 Min)
5. SPAN-Element Übung (15 Min)
6. HTML Klassen verstehen (10 Min)
7. Semantische HTML-Elemente (10 Min)
8. CSS Box-Modell (15 Min)
9. CSS Margin & Zentrierung (10 Min)
10. Mini-Projekt (20 Min)

## Materialien
- GitHub Desktop
- Texteditor (VS Code)
- Webbrowser

## Schritt 1: GitHub Repository forken
1. Öffne GitHub Desktop
2. Navigiere zum Repository: github.com/vsvito420/div-span-tutorial1
3. Klicke auf "Fork this repository"
4. Wähle einen lokalen Speicherort
5. Klicke auf "Clone"

Weitere Informationen: [Ein Repository forken - GitHub-Dokumentation](https://docs.github.com/de/pull-requests/collaborating-with-pull-requests/working-with-forks/fork-a-repo)

## Schritt 2: Block- vs. Inline-Elemente
### Block-Elemente
- Nehmen die gesamte verfügbare Breite ein
- Beginnen immer auf einer neuen Zeile
- Beispiele: `<div>`, `<h1>`, `<p>`, `<ul>`, `<li>`

### Inline-Elemente
- Nehmen nur so viel Platz wie nötig ein
- Bleiben in der Zeile
- Beispiele: `<span>`, `<a>`, `<img>`, `<strong>`, `<em>`

Weitere Informationen: [HTML Block and Inline Elements](https://www.w3schools.com/html/html_blocks.asp)

## Schritt 3: DIV-Element Übung
Öffne die Datei `div-uebung.html` und:
1. Analysiere den Code:
   ```html
   <div class="city">
     <h2>London</h2>
     <p>London is the capital of England.</p>
   </div>
   ```
2. Beachte, wie die CSS-Klasse "city" alle Div-Elemente gestaltet
3. **Übung**: 
   - Füge eine vierte Stadt hinzu (z.B. Berlin)
   - Ändere die Hintergrundfarbe für eine bestimmte Stadt

## Schritt 4: SPAN-Element Übung
Öffne die Datei `span-uebung.html` und:
1. Analysiere den Code:
   ```html
   <h1>My <span class="note">Important</span> Heading</h1>
   ```
2. Beachte, wie das span-Element nur einen Teil des Textes hervorhebt
3. **Übung**:
   - Füge weitere hervorgehobene Wörter hinzu
   - Erstelle eine neue Klasse für andere Hervorhebungen (z.B. blau für Fachbegriffe)

## Schritt 5: HTML-Klassen
- Klassen ermöglichen die Gestaltung mehrerer Elemente auf die gleiche Weise
- Syntax: `<element class="klassenname">`
- In CSS: `.klassenname { eigenschaft: wert; }`
- Ein Element kann mehrere Klassen haben: `<div class="klasse1 klasse2">`

**Übung**: Erstelle eine neue Klasse und wende sie auf verschiedene Elemente an

Weitere Informationen: [HTML Classes - The Class Attribute](https://www.w3schools.com/html/html_classes.asp)

## Schritt 6: Semantische HTML-Elemente
- Semantische Elemente beschreiben ihre Bedeutung
- Wichtig für Barrierefreiheit und SEO
- Beispiele:
  - `<header>`: Kopfbereich
  - `<nav>`: Navigation
  - `<main>`: Hauptinhalt
  - `<section>`: Abschnitt
  - `<article>`: Eigenständiger Inhalt
  - `<footer>`: Fußbereich

**Übung**: Wandle eine div-basierte Struktur in semantische Elemente um

Weitere Informationen: [HTML Semantic Elements](https://www.w3schools.com/html/html5_semantic_elements.asp)

## Schritt 7: CSS Box-Modell
![CSS Box-Modell](https://www.w3schools.com/css/box-model.gif)

- Content: Der eigentliche Inhalt
- Padding: Innenabstand zwischen Inhalt und Rahmen
- Border: Rahmen um das Element
- Margin: Außenabstand zu anderen Elementen

**Übung**: Experimentiere mit den verschiedenen Box-Modell-Eigenschaften

Weitere Informationen: [CSS Grundlagen • Box Positionierung Step by Step Guide](https://www.website-advisor.de/grundlagen/css/box-positionierung.php)

## Schritt 8: CSS Margin & Zentrierung
- `margin: 10px;` - Gleicher Abstand auf allen Seiten
- `margin: 10px 20px;` - 10px oben/unten, 20px links/rechts
- `margin: 10px 20px 15px 25px;` - oben, rechts, unten, links
- Zentrierung:
  - Text: `text-align: center;`
  - Block-Elemente: `margin: 0 auto;`

**Übung**: Zentriere verschiedene Elemente auf der Seite

## Mini-Projekt: Persönliche Profilseite
Erstelle eine einfache Profilseite mit:
1. Semantischer HTML-Struktur (header, main, footer)
2. Verschiedenen Block- und Inline-Elementen
3. CSS-Klassen zur Gestaltung
4. Korrekter Anwendung des Box-Modells
5. Zentrierung von Elementen

### Beispielstruktur:
```html
<!DOCTYPE html>
<html>
<head>
  <title>Mein Profil</title>
  <style>
    /* Hier kommen deine CSS-Regeln */
  </style>
</head>
<body>
  <header>
    <!-- Kopfbereich mit Titel und Navigation -->
  </header>
  <main>
    <!-- Hauptinhalt mit Abschnitten -->
    <section class="info">
      <!-- Persönliche Informationen -->
    </section>
    <section class="hobbies">
      <!-- Hobbys und Interessen -->
    </section>
  </main>
  <footer>
    <!-- Fußbereich mit Kontaktinformationen -->
  </footer>
</body>
</html>
```

## Weiterführende Ressourcen
- [W3Schools HTML Tutorial](https://www.w3schools.com/html/)
- [W3Schools CSS Tutorial](https://www.w3schools.com/css/)
- [MDN Web Docs](https://developer.mozilla.org/de/docs/Web)
