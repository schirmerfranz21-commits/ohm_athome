---
tags:
Autor: "[[Jonathan Grunewald]]"
---
# Motorkalibrierung:
## Allg. Anleitung

1. Servo Adapter über Netzteil mit Strom versorgen, über USB mit Pie verbinden (Adapter am Arbeitsplatz mit Aufschricht 50 vmtl. defekt; einen vom Robo probieren)

2. Im Pi (Konsole): Debug-Programm über Konsolenbefehl: FT_SCServo_Debug_Qt starten
(wenn nicht Verfügbar: Installation über https://github.com/Kotakku/FT_SCServo_Debug_Qt )

3. Nach Anleitung von Pid "Motor kalibrieren" arbeiten (Nullpunkt kalibrieren; Sehne so einstellen dass Finger/Handgelenk leicht gebeugt (bei "Hauptgelenken" in neutrale Position kalibrieren); ID zuweisen); Tabelle für Zuordnung vom Schaltplan