<!-- ELUCENIA technical documentation · escore-de-alvarado · de · no clinical/professional/rights approval -->

# Alvarado-Score

[Bedingungen, Quellen und Berechtigungen](https://elucenia.org/de/werkzeuge/escore-de-alvarado)

## Verwendung

Verwenden Sie das Werkzeug im Portal oder öffnen Sie index.html über einen lokalen HTTP-Server. Wählen Sie die Sprache, füllen Sie die Felder aus und berechnen Sie das Ergebnis.

## Eingaben und Einheiten

### Wanderung des Schmerzes in den rechten Unterbauch

`migra`

### Appetitlosigkeit (oder Aceton im Urin)

`anorex`

### Übelkeit oder Erbrechen

`nausea`

### Druckschmerz im rechten Unterbauch

`dor`

### Loslassschmerz (Blumberg-Zeichen)

`desc`

### Temperatur ≥ 37,3 °C

`febre`

### Leukozytose \> 10.000/mm³

`leuco`

### Linksverschiebung (Neutrophile \> 75 %)

`desvio`

## Fassung der Methode

Alvarado 1986: MANTRELS 8 Items, 0–10; Fassung mit Linksverschiebung

## Dokumentierte Formel

MANTRELS: Migration (1), Appetitlosigkeit (1), Nausea/Erbrechen (1), T Druckschmerz rechter Unterbauch (2), R Loslassschmerz (1), E erhöhte Temperatur (1), Leukozytose (2), S Linksverschiebung (1). Gesamt 0 bis 10.

## Grenzen und Population

Alvarado 1986 wurde anhand von 305 hospitalisierten Patienten mit appendizitisverdächtigen Bauchschmerzen und acht klinischen und Laborfaktoren erstellt. Das ursprüngliche Abstract validiert nicht automatisch verschiedene Altersgruppen, Schwangere oder Entlassungs- und Bildgebungsstrategien. Entscheidungsschwellen und Population der verwendeten Version müssen getrennt geprüft werden; das Werkzeug implementiert die Variante mit Linksverschiebung.

## Referenzen

- [Alvarado A. A practical score for the early diagnosis of acute appendicitis. Ann Emerg Med, 1986.](https://doi.org/10.1016/S0196-0644(86)80993-3)

- [Di Saverio S et al. Diagnosis and treatment of acute appendicitis: 2020 update of the WSES Jerusalem guidelines. World J Emerg Surg, 2020.](https://doi.org/10.1186/s13017-020-00306-3)

## Technische Tests reproduzieren

Führen Sie node test.cjs im Stammverzeichnis dieses Repositorys aus, um die dokumentierten synthetischen Fälle zu wiederholen. Ursprüngliche Eingaben, erwartete Ergebnisse und Toleranzen bleiben erhalten. Technische Tests stellen keine klinische Validierung dar.

```sh
node test.cjs
```

tool.json enthält Quellen, Ausgabe und Umfang der Überprüfung. examples.json bewahrt die synthetischen Eingaben und erwarteten Ergebnisse; results.json dokumentiert die tatsächlich erhaltenen Ergebnisse.

[Eintrag und Referenzen](../tool.json) · [JavaScript-Code](../calculator.js) · [Referenzfälle](../examples.json) · [results.json](../results.json)

## Überprüfung und Nutzungsbedingungen

Eine unabhängige klinische Prüfung wurde nicht durchgeführt.

Diese Benutzeroberfläche ist eine selbst erstellte Übersetzung und keine offizielle oder zertifizierte Ausgabe. Eine unabhängige klinische Überprüfung, eine professionelle sprachliche Prüfung und eine Klärung der Rechte an den Instrumenten wurden nicht durchgeführt.

Ergebnis der Formel oder Klassifikation. Interpretation, Vorgehen und Anwendbarkeit hängen von der fachlichen Beurteilung und der ausgewählten Quelle ab.

## Lizenz und Urheberangaben

Apache-2.0 gilt nur für den ELUCENIA-Code. Die Rechte an Instrumenten, Veröffentlichungen, Übersetzungen und Daten verbleiben bei den jeweiligen Rechteinhabern. Bewahren Sie LICENSE und NOTICE auf.

ELUCENIA · Felipe Guedes · Copyright © 2026

## Dokumentierte Ergebnisse

Die folgenden Angaben bewahren die Ausgaben der Methode für synthetische Beispiele. Sie stellen keine unabhängige klinische Validierung dar.

### 1

Appendizitis unwahrscheinlich (0 bis 4)

Andere Ursachen erwägen; neu beurteilen, wenn die Symptome anhalten.


### 2

Mit Appendizitis vereinbar (5 bis 6)

Beobachtung und serielle Neubewertung oder Bildgebung.


### 3

Appendizitis wahrscheinlich (7 bis 8)

Chirurgische Beurteilung; Bildgebung entsprechend dem Patientenprofil.


### 4

Appendizitis sehr wahrscheinlich (9 bis 10)

Chirurgische Beurteilung.

