# bodensee-pegel-daten

Messwerte des Bodensee-Pegels **Konstanz** für [bodensee-pegel.de](https://bodensee-pegel.de),
stündlich automatisch aktualisiert.

## Dateien

| Pfad                            | Inhalt                                           |
| ------------------------------- | ------------------------------------------------ |
| `live/konstanz.json`            | aktueller Wert, Trend und die letzten 24 Stunden |
| `history/konstanz/YYYY-MM.json` | Archiv im 15-Minuten-Raster, eine Datei je Monat |

Zeitstempel in UTC, Wasserstand in cm am Pegel (Pegelnullpunkt) und in m ü. NHN.

## Quelle und Lizenz

Wasserstraßen- und Schifffahrtsverwaltung des Bundes (WSV), bereitgestellt über
[PEGELONLINE](https://www.pegelonline.wsv.de/). Lizenz:
[Datenlizenz Deutschland – Zero – Version 2.0](https://www.govdata.de/dl-de/zero-2-0).

Ungeprüfte Rohdaten, ohne Gewähr. Keine amtliche Hochwasser- oder Niedrigwasserwarnung.
