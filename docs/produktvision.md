# Produktvision

**Für** Schulleitungen, Abteilungsleitungen und Stundenplaner beruflicher Schulen in Baden-Württemberg,
**die** Deputate heute in UNTIS und Excel parallel pflegen und beim Übertragen Fehler machen,
**ist** die Deputatsverwaltung
**eine** einzige verlässliche Quelle für Soll, Ist und Saldo jeder Lehrkraft,
**die** jede Änderung nachvollziehbar macht und den Abgleich mit UNTIS und AS-DBW Zeile für Zeile abhakbar macht.
**Anders als** Excel rechnet sie mit dem geltenden Regelwerk des Landes und zeigt den Stand zu jedem Stichtag.

## Rahmen

| Thema | Festlegung |
|---|---|
| Schule | Berufliche Schule, bis ca. 180 Lehrkräfte |
| Betrieb | Test auf einem PC, später Linux-Server im Verwaltungsnetz (Windows-Clients, Browser) |
| SaaS | Erst nach erfolgreicher Testphase; Mandantenfähigkeit nur vorbereitet (Schul-ID) |
| Daten | In Entwicklung und Test ausschließlich erfundene Testdaten |
| Statistik-Stichtag | i. d. R. 21.11. (einstellbar) |

## Rollen

| Rolle | Rechte |
|---|---|
| Schulleitung | lesen + bearbeiten |
| Abteilungsleitung | lesen + bearbeiten (alle Lehrkräfte, abteilungsübergreifend) |
| Stundenplaner | nur lesen |
| Personalrat, Datenschutzbeauftragte/r | Prüfrolle: Funktionen und Datenumfang einsehen, Freigabe dokumentieren (keine Sperre) |

Eine Person kann mehrere Rollen haben.

## Umsysteme

| System | Richtung | Weg |
|---|---|---|
| Eigenes Stundenplanprogramm | nur Import → Deputatsverwaltung | Austauschformat, das wir definieren (JSON) |
| UNTIS | manueller Abgleich, später ggf. Import (Vertretungen) | Abgleichsansicht; Exportformate noch offen |
| AS-DBW | manueller Abgleich | Abgleichsansicht; Felder noch offen |
