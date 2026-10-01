# Backlog

## Release 1 (MVP) – Priorität des Stakeholders

### Epic 0: Grundlagen
- **US-0.1** Als Schulleitung melde ich mich an und sehe nur, was meine Rollen erlauben (SL/AL bearbeiten, Stundenplaner liest).
- **US-0.2** Als Schulleitung sehe ich zu jeder Änderung, wer was wann geändert hat (Änderungsprotokoll – Grundlage für den späteren Stichtagsvergleich).

### Epic 1: Stammdaten und Soll-Deputat
- **US-1.1** Als Schulleitung pflege ich das Regelwerk eines Schuljahres (Regelstundenmaße je Lehrergruppe, Ermäßigungsstufen, Bagatellgrenze).
- **US-1.2** Als Abteilungsleitung lege ich eine Lehrkraft an (Lehrergruppe, Beschäftigungsart, Beschäftigungsumfang, Geburtsdatum, ggf. GdB).
- **US-1.3** Als Abteilungsleitung sehe ich Alters- und Schwerbehindertenermäßigung automatisch berechnet.
- **US-1.4** Als Schulleitung vergebe ich Anrechnungen (Art, Stunden, gültig von–bis).
- **US-1.5** Als Nutzer sehe ich das Soll-Deputat einer Lehrkraft zu einem gewählten Stichtag.

  *Akzeptanzbeispiel:* Wiss. LK, Vollzeit, 25 Std., Abteilungsleitungsanrechnung 3 Std. → Soll 22 Std.

### Epic 2: Unterrichtsverteilung und Ampel
- **US-2.1** Als Abteilungsleitung pflege ich Klassen und Fächer.
- **US-2.2** Als Abteilungsleitung ordne ich Unterricht zu (Lehrkraft, Klasse, Fach, Wochenstunden, Wertfaktor, gültig von–bis).
- **US-2.3** Als Abteilungsleitung erfasse ich Aufsichten (Handyraum, Bewegungsraum, Lernbetreuung) mit Wertfaktor.
- **US-2.4** Als Nutzer sehe ich eine Übersicht aller Lehrkräfte mit Soll, Ist, Saldo und Ampel; filterbar nach Abteilung.

  *Akzeptanzbeispiel:* 2 Std. Englisch geteilt (Wert 0,5) + 2 Std. Lernbetreuung (Wert 0,5) → Ist 2,0 Std.

### Epic 3: Monatliche MAU
- **US-3.1** Als Schulleitung erfasse ich MAU-Stunden je Lehrkraft und Kalendermonat.
- **US-3.2** Als Schulleitung sehe ich die persönliche Bagatellgrenze und ob/wie viele Stunden ausgleichs- bzw. vergütungsfähig sind.
- **US-3.3** Als Schulleitung werde ich gewarnt bei befristet Tarifbeschäftigten und vor Ablauf der 6-Monats-Ausschlussfrist.

  *Akzeptanzbeispiele:*
  - Beamt/in Vollzeit, 3 MAU im Monat → 0 vergütungsfähig.
  - Beamt/in Vollzeit, 4 MAU im Monat → 4 vergütungsfähig.
  - Beamt/in Teilzeit 18/25, Grenze 2,16 → 3 MAU → 3 vergütungsfähig.
  - Tarif Teilzeit, 1 MAU → 1 vergütungsfähig.

## Release 2+
- **Freigaben:** Personalrat und Datenschutzbeauftragte/r erhalten eine eigene Prüfrolle mit Lesezugriff auf Funktionen und Datenumfang und dokumentieren ihre Freigabe je Funktion (wer, wann, welche Version). Das Programm sperrt nichts, die Freigaben dienen als Nachweis (z. B. für das Verzeichnis der Verarbeitungstätigkeiten).
- **Stichtagsvergleich:** Änderungen zwischen zwei Stichtagen anzeigen.
- **Bugwelle (RMA)** über mehrere Schuljahre inkl. Abbau auf Antrag.
- **Deputatserhöhungen** befristet/dauerhaft.
- **Stundentafeln** pflegen.
- **Import aus dem Stundenplanprogramm** (Austauschformat definieren wir; nur Import, kein Rückschreiben).
- **Abgleichsansicht UNTIS** mit Abhaken (sobald Exportinfos vorliegen).
- **Abgleichsansicht AS-DBW** (sobald Felder bekannt).
- **Import Vertretungen aus UNTIS** für MAU.
- **Mandantenfähigkeit** für SaaS.
