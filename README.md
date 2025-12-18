# INTERAKTIVER WASSERFALL
Ein Projekt von Nadia Giliberti

## ÜBERBLICK
Beschrieb, was ist mein Projekt

Hier evtl. ein Bild vom fertigen Projekt

### VIDEOS:
**Insights Projektaufbau**:
**Demovideo Installation**:


## PROJEKT REPRODUZIEREN
### BENÖTIGTE RESSOURCEN:
- Touchdesigner
- Madmapper
- Slamtec RP Lidar A1
- Beamer jeglicher Art

### INSTALLATION VORGEHEN
1. Dateien "wasserfall_lidartrack.toe" und "SlamtecCHOP_V3.dll" aus Github-Projekt herunterladen und in Ordner der Wahl platzieren.  
Wichtig: beide Dateien in gleicher Ordnerebene belassen.
2. "wasserfall_lidartrack.toe" in Touchdesigner öffnen
3. Lidartrack an Gerät anschliessen
4. Geräte-Manager (auf dem Computer) öffnen und schauen welchen COM Port für den Lidartrack verwendet wird.  
Problembehebung: Wenn Lidartrack unter den Geräten nicht erkannt wird. Treiber auf der offiziellen Website herunterladen:  
[https://www.silabs.com/software-and-tools/usb-to-uart-bridge-vcp-drivers?tab=downloads](https://www.silabs.com/software-and-tools/usb-to-uart-bridge-vcp-drivers?tab=downloads)
5. Im Projekt cplusplus1 anwählen und im Register "Connection Settings" den soeben ermittelten Port bei "COM Port" eingeben.  

![Screenshot Port](bilder_doku/cplusplus1_COM_Port)

6. Register "Lidar Settings" öffnen und Active von Off auf On setzen.  

![Screenshot Lidar aktiv setzen](bilder_doku/cplusplus1_lidar_active)

7. Daten sollten nun vom Lidar erfasst werden und den Wasserfall beeinflussen
8. MadMapper öffnen, Beamer anstecken und ausprobieren...


### KOMPONENTEN DIAGRAMM
- kommt noch

### REFLEXION
- Planung und umsetzung
- Herausforderungen: Beamer kabel kaputt - Bern vs. Chur - PC alternative für lidar - kabel Lidar kurz
- Aufgabenverteilung - me myself and i
- Lernerfolg: komplett neue Programme. Vorher noch nie was mit Touchdesigner/Madmapper was gemacht.
- verwendete Tools: KI nur wenig. teilweise mit Claude oder Chatgpt problembehebungen versucht. Coachings mit Dozenten. Tutorials auf Youtube
- bekannte Bugs: 
