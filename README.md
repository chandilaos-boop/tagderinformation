# Wortwelt-Abenteuer 🦉

Ein Englisch-Vokabelspiel für Kinder der 4. Klasse (Tag der offenen Tür).
Ein Kind wählt einen Partner-Wortling, läuft über eine Karte und trifft
6 Wortlinge. Jeder Wortling stellt Vokabelfragen – richtige Antworten sind
Angriffe. Am Ende gibt es eine Urkunde. Spieldauer: ca. 10 Minuten.

- **Eine Datei:** `index.html` – keine Installation, kein Internet nötig, sobald sie geladen ist.
- **Für das iPad gemacht:** große Knöpfe, Hoch- und Querformat.
- **Ton:** Die englischen Wörter werden vorgelesen (🔊). Die deutschen Texte kann man sich auch vorlesen lassen.
  Bitte Lautstärke am iPad einschalten und den Lautlos-Schalter ausschalten.
- **Niemand verliert:** Bei falschen Antworten wird das richtige Wort gezeigt und später noch einmal gefragt.
  Sind alle Herzen weg, gibt Professorin Eule einen Heiltrank.

## Themen

| Ort | Thema | Beispiele |
|---|---|---|
| Blumenwiese | Tiere | dog, cat, horse, rabbit … |
| Regenbogenwald | Farben | red, blue, yellow, purple … |
| Zahlenstrand | Zahlen 1–12 | one, seven, twelve … |
| Picknickplatz | Essen | apple, bread, cheese, ice cream … |
| Spielzeugstadt | Schule & Zuhause | book, pencil, chair, school bag … |
| Die Schule (Endgegner) | alles gemischt | |

Fragearten: Bild → englisches Wort, deutsches Wort → Englisch, englisches Wort → Deutsch, Hören → Bild.

## Anpassen

Oben im `<script>`-Teil von `index.html`:

```js
const SCHULNAME = "unserer Gesamtschule";   // z. B. "der Gesamtschule Musterstadt"
const FRAGEN_PRO_KAMPF = 4;                // mehr Fragen = längeres Spiel
const FRAGEN_BOSS = 6;
```

Die Vokabeln stehen direkt darunter in `THEMES` und lassen sich leicht ändern.

## Auf die iPads bringen

Die Datei muss über eine Webadresse erreichbar sein, z. B.:

1. **Netlify Drop:** <https://app.netlify.com/drop> öffnen und den Ordner mit `index.html` hineinziehen.
2. **GitHub Pages:** im Repository unter *Settings → Pages* den Branch auswählen.

Dann die Adresse in Safari öffnen → Teilen → **„Zum Home-Bildschirm“**. So startet das Spiel im Vollbild wie eine App.

## Für die Betreuung

- **⟲** oben rechts: neues Spiel für das nächste Kind.
- **🔈** oben rechts: Ton an/aus.
- Nach der Urkunde startet **„Neues Spiel“** direkt von vorn.
