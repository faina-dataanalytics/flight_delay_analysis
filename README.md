#LAX Flight Delay Analysis (2015–2017)
Power BI · SQL · Data Modeling · Data Storytelling

##Projektbeschreibung
Dieses Projekt analysiert Flugverspätungen am Los Angeles International Airport (LAX) im Zeitraum 2015–2017.
Ziel ist es, Muster, Ursachen und kritische Zeiträume der Verspätungen zu identifizieren und visuell aufzubereiten.
Die Analyse wurde im Rahmen eines Data‑Analytics‑Trainings durchgeführt und umfasst den gesamten Workflow:
Datenimport → Bereinigung → Modellierung → Measures → Visualisierung → Storytelling.

##Datenbasis
Die Daten stammen aus einer PostgreSQL‑Datenbank (flights) sowie einer ergänzenden CSV‑Datei (UNIQUE_CARRIERS).

##Datenmodellierung
Die Modellierung erfolgte in Power BI:

##Visualisierungen (Power BI Dashboards)
▪ Gesamtüberblick
▪ Fluggesellschaften
▪ Zeitliche Muster
▪ Detail-Analyse


##Kernergebnisse
▪ 70 % aller Flüge sind unpüntlich
▪ Durchschnittliche Verspätung: 26 Minuten
▪ Ankünfte deutlich stärker betroffen (78 %) als Abflüge (50 %)
▪ Starke Peaks in Nachtstunden und Wintermonaten
▪ Wenige Airlines verursachen Großteil der Verspätungen (Southwest, American, SkyWest)


##Empfehlungen
Einsatz von Prognosemodellen zur frühzeitigen Erkennung von Delay‑Risiken
Optimierung der Nacht‑Slots und Bodenprozesse
Zusammenarbeit mit Airlines mit hohen Verspätungsraten
Berücksichtigung saisonaler Peaks (Winter/Sommer)


##Technologien
Power BI
SQL / PostgreSQL (Datenextraktion)
