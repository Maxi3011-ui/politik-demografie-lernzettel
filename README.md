# Politik Lernzettel – Demografischer Wandel

Kompakter Lernzettel für Handy und Apple Watch zu *Politik aktuell G9*, Kapitel 1 (S. 8–35), Kurzarbeit am 15.10.2026.

**Live:** https://maxi3011-ui.github.io/politik-demografie-lernzettel/

## Lernstoff

- **1.1 Bevölkerung:** Grundbegriffe, Bevölkerungspyramide analysieren, historische Einschnitte, sieben Pyramidenformen, Bevölkerungsentwicklung und Sozialstruktur.
- **1.2 Ursachen:** Familie, Wertewandel, niedrige Geburtenhäufigkeit, steigende Lebenserwartung, staatliche Ansätze und demografischer Übergang.
- **1.3 Folgen:** Generationenvertrag, Umlageverfahren, Herausforderungen und Chancen.
- Kapitel 1.4 ist nicht Teil des Lernstoffs.

Die sieben Bezeichnungen aus der vorhandenen Fassung bleiben erhalten: Pyramidenform, verbreiterte Pyramidenform, stationäre Form, Glockenform, Urnenform, Birnenform und Tropfenform. Die Skizzen sind schematisch und keine statistischen Diagramme.

## Bedienung

Das Auswahlmenü enthält nur die drei Hauptkapitel und folgt beim Scrollen der Leseposition. Unterthemen sind per URL verlinkbar, z. B. `#rente` oder `#pyramide-analysieren`. Am Seitenende stehen die Quellen. Eine Druckansicht ist per Browserdruck verfügbar.

## Inhalte und Quellen

`content.js` enthält den Lernstoff und Quellenlinks; `index.html` die Darstellung, Navigation und Skizzen. Keine externen Bibliotheken oder Schriftarten erforderlich.

Die ursprüngliche Fassung nennt Heft, Musterlösung, „Wissen kompakt“ und „Wissen im Kontext“ als Grundlage. Diese Originalmaterialien liegen im Repository nicht vor. Die Überarbeitung präzisiert Aussagen anhand von Destatis, bpb und Deutscher Rentenversicherung; sie ersetzt keinen Abgleich mit der Unterrichtsvorlage. Zahlen sind mit Bezugsjahr angegeben (z. B. 1,58 Kinder je Frau im Jahr 2021). Unbelegte Prognosewerte und pauschale Aussagen zur Produktivität älterer Menschen wurden entfernt.

## Lokal ansehen

```sh
python3 -m http.server 8765 --bind 127.0.0.1
```

Danach `http://127.0.0.1:8765` öffnen. Veröffentlichung über GitHub Pages aus `main`.
