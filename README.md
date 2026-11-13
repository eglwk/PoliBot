# POLIBOT

POLIBOT ist ein Web-Prototyp, der im Rahmen einer Bachelorarbeit für eine psychologische Studie entwickelt wurde. Er ermöglicht eine zeitlich begrenzte Chatinteraktion mit Textnachrichten und integrierten Videos.

## 1. Technologien

- React
- Vite
- JavaScript
- CSS

## 2. Installation und Start

Voraussetzung: Node.js und npm sind installiert.

Repository klonen und im Terminal folgende Befehle ausführen:

```bash
cd prototype
npm install
npm run dev
```

Anschließend die von Vite angezeigte lokale Adresse im Browser öffnen.



3. Aktuelle Chatlogik

Die Bot-Antworten werden aktuell über die Lookup-Tabelle botResponses in src/App.jsx erzeugt.

Beispiele für Testeingaben:

hi

hallo

was denkst du

video

danke

Andere Eingaben erzeugen derzeit keine Bot-Antwort.