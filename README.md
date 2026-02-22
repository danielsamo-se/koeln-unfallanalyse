# Unfallanalyse Köln – Jupyter Notebooks

Dieses Repository enthält die Ergebnisse eines Datenanalyse-Projekts zu Verkehrsunfällen in Köln.  
Ziel war es, Unfallmuster systematisch zu untersuchen (zeitlich und räumlich), die Unfallschwere zu vergleichen und Zusammenhänge mit Umgebungsfaktoren (z. B. Nähe zu Bars) explorativ auszuwerten.

## Projektziele
- **Datenaufbereitung** und einheitliche Feature-Erstellung (Zeitkategorien, Nacht/Tag, Wochenenden, etc.)
- **Deskriptive Analysen** zur Unfallhäufigkeit und -schwere nach:
  - Stunde / Tageszeit
  - Wochentag / Wochenende
  - Monat / Jahreszeit
- **Räumliche Analysen** mit Distanz- und Zonen-Konzepten:
  - Distanz zum nächsten POI (z. B. Bars)
  - Vergleich von Unfallmustern „in Nähe“ vs. „nicht in Nähe“
- **Modellierung** zur Erklärung/Vorhersage von Unfallmustern auf aggregierter Ebene:
  - Lineare Regression
  - LightGBM

## Inhalt
- Datenaufbereitung und Feature Engineering
- Zeitbasierte Auswertungen (Tageszeit, Wochentage, Jahreszeiten)
- Analysen zur Unfallschwere (UKATEGORIE) in verschiedenen Kontexten
- Distanz-Analysen (z. B. Distanz zu Bars)
- Grid-/Zonen-Analysen und weiterführende Auswertungen (je nach Notebook)
- Modellierung (Lineare Regression, LightGBM)

## Notebooks
Die Analysen sind in mehreren Jupyter Notebooks organisiert (siehe Dateien im Repository).  
Die Dateinamen orientieren sich an den jeweiligen Analyse-Schritten bzw. Themenbereichen.

## Autor:innen
- Nour Meddeb
- Daniel Samoylov
