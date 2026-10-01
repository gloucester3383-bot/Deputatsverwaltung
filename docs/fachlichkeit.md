# Fachlichkeit (Ubiquitous Language)

Begriffe, die im Code genau so heißen sollen.

| Begriff | Bedeutung |
|---|---|
| **Lehrkraft** | Person mit Lehrergruppe, Beschäftigungsart und Beschäftigungsumfang |
| **Lehrergruppe** | wissenschaftliche LK, technische LK (Fachrichtung), LiA – bestimmt das Regelstundenmaß |
| **Beschäftigungsart** | Beamt/in, tarifbeschäftigt unbefristet, tarifbeschäftigt befristet |
| **Regelstundenmaß** | Wochenstunden bei Vollzeit (z. B. 25, 27, 28) – aus dem Regelwerk |
| **Regelwerk** | Alle Landesvorgaben eines Schuljahres als Parameter (nie im Code fest verdrahtet) |
| **Ermäßigung** | Altersermäßigung, Schwerbehindertenermäßigung – regelbasiert berechnet |
| **Anrechnung** | Schulleitung, Abteilungsleitung, Entlastungspool, Fachbetreuung, Netzwerk, Personalrat – manuell vergeben, mit Gültigkeit |
| **Soll-Deputat** | Regelstundenmaß × Beschäftigungsumfang − Ermäßigungen − Anrechnungen |
| **Unterricht** | Lehrkraft × Klasse × Fach × Wochenstunden × Wertfaktor, mit Gültigkeit von–bis |
| **Aufsicht** | Tätigkeit ohne Fach (Handyraum, Bewegungsraum, Lernbetreuung) mit Wertfaktor |
| **Wertfaktor** | Anrechnungswert einer Stunde (z. B. 0,5 bei Klassenteilung) – wie „Wert“ in UNTIS |
| **Ist-Deputat** | Σ (Wochenstunden × Wertfaktor) über Unterricht und Aufsichten |
| **Saldo** | Ist-Deputat − Soll-Deputat |
| **Stichtag** | Datum, zu dem der gültige Stand ermittelt wird |
| **MAU** | Mehrarbeitsunterricht, Abrechnung je Kalendermonat |
| **Bagatellgrenze** | MAU-Stunden pro Monat ohne Vergütung |
| **Bugwelle (RMA)** | Regelstundenmaßausgleich: Mehrarbeit > 3 Monate zusammengefasst, Ausgleich i. d. R. im Folgeschuljahr |
| **Deputatserhöhung** | Befristete oder dauerhafte Aufstockung des Beschäftigungsumfangs |

## Rechenregeln (Stand Recherche 01.10.2026 – vor Umsetzung fachlich bestätigen)

**MAU / Bagatellgrenze** (§ 67 Abs. 3 LBG; Merkblatt SSA/ÖPR Ludwigsburg 10/2024)
- Vollzeit (Beamte und Tarif): 3 Unterrichtsstunden je Kalendermonat.
- Teilzeit Beamte: Teilzeitdeputat ÷ Regelstundenmaß × 3.
- Wird die Grenze überschritten, zählen **alle** MAU-Stunden des Monats.
- Tarif Teilzeit: keine Bagatellgrenze, Vergütung ab der 1. Stunde bis zum vollen Deputat.
- Tarif befristet: Mehrarbeit grundsätzlich nicht vorgesehen → Warnhinweis.
- Tarif: Ausschlussfrist 6 Monate → Warnhinweis.
- Freizeitausgleich hat Vorrang vor Vergütung.

**Bugwelle (RMA)** (VwV Arbeitszeit der Lehrer, A. IV.)
- Mehrarbeit über zusammenhängend > 3 Monate kann zusammengefasst werden; Genehmigung durch Schulaufsicht.
- Ausgleich spätestens im darauffolgenden Schuljahr; Abbau auf Antrag.

**Ermäßigungen** (Lehrkräfte-ArbeitszeitVO 2014 – Werte prüfen)
- Altersermäßigung: ab 60 → 1 Std., ab 62 → 2 Std. (Teilzeitregeln prüfen).
- Schwerbehinderung: GdB ≥ 50 → 2, ≥ 70 → 3, ≥ 90 → 4 Std. (Teilzeit abweichend).

## Offene Punkte

- Welche UNTIS-Exporte gibt es (Format, Inhalt)?
- Welche AS-DBW-Felder werden pro Lehrkraft erfasst, in welcher Reihenfolge?
- Standard-Wertfaktoren für Teilung und Kopplung: feste Regel oder immer manuell?
- Altersermäßigung und Schwerbehindertenermäßigung bei Teilzeit: aktuelle Werte bestätigen.
