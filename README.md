# LAX Flight Delay Analysis (2015–2017)

**Power BI · SQL · Data Modeling · Data Storytelling**

---

## Projektbeschreibung

Dieses Projekt analysiert Flugverspätungen am Los Angeles International Airport (LAX) im Zeitraum 2015–2017.
Ziel ist es, Muster, Ursachen und kritische Zeiträume der Verspätungen zu identifizieren und visuell aufzubereiten.

Die Analyse umfasst den gesamten Workflow:
**Datenimport → Bereinigung → Modellierung → Measures → Visualisierung → Storytelling**

---

## Datenbasis

Die Daten stammen aus:

* einer PostgreSQL-Datenbank (`flights`)
* einer ergänzenden CSV-Datei (`UNIQUE_CARRIERS`)

---

## Datenbereinigung & Transformation

* Zeitkorrekturen (Umwandlung von Textwerten in gültige Zeitformate)
* Korrektur ungültiger Werte (z. B. 2400 → 23:59)
* Datenmodellierung

---

## Visualisierungen (Power BI Dashboards)

1. Gesamtüberblick
2. Fluggesellschaften
3. Zeitliche Muster
4. Detail-Analyse

---

## Kernergebnisse

* 70 % aller Flüge verspätet
* Durchschnittliche Verspätung: 26 Minuten
* Ankünfte deutlich stärker betroffen (82 %) als Abflüge (58 %)
* Starke Peaks in Nachtstunden und Wintermonaten
* Wenige Airlines verursachen Großteil der Verspätungen (Southwest, American, SkyWest)

---

## Empfehlungen

* Einsatz von Prognosemodellen zur frühzeitigen Erkennung von Delay-Risiken
* Optimierung der Nacht-Slots und Bodenprozesse
* Engere Zusammenarbeit mit Airlines mit hohen Verspätungsraten
* Berücksichtigung saisonaler Peaks (Winter/Sommer)

---

## Technologien

* Power BI (Datenmodell, DAX, Visualisierung)
* Power Query (Transformationen)
* SQL / PostgreSQL (Datenextraktion)
* DAX (Measures)

---
