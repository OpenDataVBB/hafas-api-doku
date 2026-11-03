# VBB Fahrinfo-API – Dokumentation

Entwicklerdokumentation der VBB Fahrinfo-API (HAFAS ReST 2.52) für Fahrplanauskunft, Abfahrts- und Ankunftstafeln, Fahrzeugpositionen und Störungsmeldungen in Berlin und Brandenburg.

**Zur Dokumentation:** <https://opendatavbb.github.io/hafas-api-doku/> <!-- nach dem Einrichten von GitHub Pages anpassen -->

## Auf einen Blick

| | |
|---|---|
| Basis-URL Produktivsystem | `https://vbb.hafas.cloud/api/fahrinfo/latest` |
| Basis-URL Demosystem | `https://vbb.demo.hafas.cloud/api/fahrinfo/latest` |
| Version | HAFAS ReST 2.52 |
| Zugang Demosystem | formlose E-Mail an [api@vbb.de](mailto:api@vbb.de), ohne vorherige Zustimmung zu Bedingungen |
| Zugang Produktivsystem | über das [Antragsformular](https://unternehmen.vbb.de/digitale-services/api/zugang-produktivsystem/) mit Zustimmung zu vier Bedingungen |
| Anfragelimits | Produktivsystem: je Kennung individuell vereinbart; Demosystem: etwas strenger |
| Umstellung | Die bisherige Schnittstelle `fahrinfo.vbb.de/restproxy` (2.49) wird am **30.11.2026** ersetzt. |

Die Dokumentation enthält alle Services mit Parametern, Beispielanfragen und -antworten, die Fehlerbehandlung, Empfehlungen für den Betrieb sowie einen Changelog und eine Checkliste für die Umstellung von 2.49 auf 2.52.

## Weitere Open-Data-Angebote des VBB

- **GTFS-Fahrplandatensatz (Solldaten):** <https://vbb.de/gtfs>
- **GTFS-Realtime-Feed:** <https://production.gtfsrt.vbb.de/data> – Echtzeitdaten für das gesamte Netz, ohne Zugangskennung

## Fehler in der Dokumentation melden

Fehler und Verbesserungsvorschläge zur Dokumentation bitte als Issue in diesem Repository. Fragen zum Zugang, zu Anfragelimits und zum Betrieb der Schnittstelle an [api@vbb.de](mailto:api@vbb.de).

## Aufbau des Repositorys

```
index.html   Dokumentation (eine Datei, ohne externe Abhängigkeiten)
LICENSE      Lizenztext CC BY 4.0
fonts/       IBM Plex, lokal eingebunden (SIL Open Font License 1.1, siehe fonts/OFL.txt)
.nojekyll    sorgt dafür, dass GitHub Pages die Dateien unverändert ausliefert
```

Die Seite lädt keine Ressourcen von Drittanbietern; Schriften und Skripte sind lokal eingebunden.

## Lizenz

Die Dokumentation steht unter der Lizenz [Creative Commons Namensnennung 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/deed.de), siehe `LICENSE`. Sie dürfen sie für beliebige Zwecke, auch kommerziell, vervielfältigen, verbreiten, verändern und weiterverarbeiten, sofern Sie die Quelle angeben, zum Beispiel:

> VBB Fahrinfo-API – Dokumentation, Verkehrsverbund Berlin-Brandenburg (VBB), CC BY 4.0

Geben Sie an, wenn Sie Änderungen vorgenommen haben.

Die Code-Beispiele (Beispielanfragen und Codeschnipsel) sind zusätzlich nach [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/deed.de) freigegeben und können ohne Quellenangabe in eigenen Code übernommen werden.

Die Schriften stehen unter der SIL Open Font License 1.1 (`fonts/OFL.txt`).

Die Lizenz der Dokumentation betrifft nicht die Nutzung der Schnittstelle und ihrer Daten. Dafür gelten die Bedingungen, denen Sie beim [Antrag auf Zugang zum Produktivsystem](https://unternehmen.vbb.de/digitale-services/api/zugang-produktivsystem/) zustimmen.
