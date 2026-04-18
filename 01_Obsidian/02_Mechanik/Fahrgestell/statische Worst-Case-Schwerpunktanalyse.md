#mathe
1.0 Schwerpunkt eines einzelnen Körpers
		-Material Bearbeiten (Alu, PETG, Benutzerdef.)
	1.1 Volumenkörper definieren und Masse zuweisen
		-Masse und Schnitteigenschaften anzeigen (unten Rechts)


2.0 Mehre Körper -> OnShape 
	2.1 Step für pib + Knie + Plattform
		-Knie Motoren Masse: 1420 g ± 20 g x 3 bis 4 mal
	2.2 OnShape nutzten für Gesamtschwerpunkt der Baugruppe

3.0 Greiflast modellieren
	3.1 Schwerpunkt auf Boden projizieren (Standfläche)
	3.2 Stabiliätsregel: "Schwerpunkt liegt innerhalb der Aufstandsfläche + 5° vom Kipppunkt"

4.0 MuJoCo Simulation
	4.1 Assambly mit 4 Freiheitsgraden
	4.2 vereinfachte Kontaktfläche zum abbilden der balligkeit
	4.3 einstellen von Maides ->URDF Datei
	4.4 Python Skript + URDF Datei -> Terminal 

![[Pasted image 20260418201451.png]]

