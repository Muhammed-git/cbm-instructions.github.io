---
title: "Thunderbirds und die Internetversorgung aus dem All"
categories: instructions
layout: post
date: 2016-06-22 15:09:51 +0200
--- 

Exponat, das eine Internetversorgung aus dem Weltall darstellt. Auf einer Weltkarte sind die Kontinente zu sehen und der Spieler muss sie über einen Satelliten ansteuern und mit Netz versorgen.

![Startbild](/images/thunderbirds/Startbild.gif)



# 1. Projekt

Ziel dieses Projektes war es Studierende, aus anderen Fakultäten von der Informatik und somit auch den dazugehörigen Studiengängen, zu überzeugen.
Das Projekt hat 15 Wochen gedauert.
Die Unterteilung dieses Projekts erfolgte in 2 Phasen.
 * Design Thinking 
 * Umsetzung der Idee

---
 
# 2. Einleitung

    POV:
    Lisas Stimmung wird beim Betreten des Gebäudes gedrückt, weil sie sich nicht 
    mit der Informatik identifizieren kann.
 
---

# 3. Material und Werkzeug

### Material (technisch)

* Arduino Uno (2)
* Kabel (Anzahl)
* Photoresistoren (6)
* Widerstände 100 kOhm (5)
* Widerstände 10 Ohm (6) 
* Lötzinn
* Sekundenkleber (4 g)
* Kleber („kleben statt bohren“)
* 5m LED Strip
* Lötplatine (10 cm x 10 cm)
* Atari 2600 - Quickjoy SV 127 TopStar Joystick (1)

### Material

* Spanplatte (100cm x 60cm x 2cm)
* Holz (50cm x 50cm x2cm), ausgesägte Kontinente
* Dünnes Holz (2qm), ausgesägte Kontinente
* Holzstab (87cm x 5cm x 2cm)
* Schleifpapier (Stärke?)
* Cremetuben (6)
* Durchsichtiges Plexiglas (50cm x 125cm x 2mm)
* Lackspray schwarz matt
* Lasermodul [Conrad.de] (https://www.conrad.de/de/lasermodul-punkt-rot-1-mw-laserfuchs-lfd650-1-12-9x20-816476.html)
* Schrauben (22)
* Auto-K Transparent-Spray Special schwarz (Art.-Nr. 33117, 2 Dosen)

### Werkzeug

* Lötkolben
* Bohrmaschine
   * Aufsätze: 10er und 4er Holzbohrer
* Akkuschrauber
* Schere
* Teppichmesser
* Zange
* Feile
* Schwarzes Isolierband
* Feine Säge
* Stichsäge 
* Kreissäge -> Werkstatt an der HS
* 3. Hand zum Löten

---

# 4. Vorbereitung

### Was muss vor dem Start gemacht werden?
* Kauf der LED Strips
* Holz besorgen
* Kleber kaufen
* Fehlendes Werkzeug organisieren
* Joystick kaufen

### Downloads
1. Bibliothek PololuLedStrip herunterladen. [Download](https://github.com/cbm-instructions/thunderbirds/tree/master/libraries/PololuLedStrip)
2. IDE Arduino herunterladen. [Download](https://www.arduino.cc/en/Main/Software)
3. Schaltplan LED Strip. [Download](https://github.com/cbm-instructions/thunderbirds/blob/master/Schaltpläne/Thunderbirds_Schaltplan_Board.png)
4. Schaltplan Joystick + Laser. [Download](https://github.com/cbm-instructions/thunderbirds/blob/master/Schaltpläne/Thunderbirds_Schaltplan_Joystick_Board.png)
5. Code für das LED Strip und die Weltkarte. [Download](https://github.com/cbm-instructions/thunderbirds/tree/master/src/Laser_Photoresistor_LED)
6. Code für den Joystick und Laser. [Download](https://github.com/cbm-instructions/thunderbirds/tree/master/src/Joystick_Laser_Final)

[kompletter Download als zip](https://github.com/cbm-instructions/thunderbirds.git)

### Liste mit benötigten Kenntnissen?
* Zur Programmierung wird nur die Arduino interne Programmiersprache verwendet. (C) 
* Umgang mit dem Lötkolben sind von Vorteil.

---


# 5. Step-by-Step-Guide


### 1. Schritt: 
Eine Holzspanplatte der Größe 50cm x 50cm dient als die Grundfläche für die Karte. Das Holz ist weiß.

![Dicke Basis Holzplatte](/images/thunderbirds/Bild_1.png)

### 2. Schritt: 
Eine weitere dicke (2 cm) Holzplatte für den unteren Zuschnitt der Kontinente. An die zugeschnittenen Kontinente wird das LED Strip geklet

### 3. Schritt: 
Dünnes Holz (Rückenwand eines Schranks) für das detaillierte Zuschneiden der Kontinente.

![Dünne Holzplatte](/images/thunderbirds/Bild_2.png)

### 4. Schritt:
Die Kontinente werden auf die Spanplatte unter Verwendung einer Vorlage gezeichnet.

![Vorlage](/images/thunderbirds/Bild_3.png)
![Dicke Holzplatte mit Konturen](/images/thunderbirds/Bild_4.png)

### 5. Schritt:
Die vorgezeichneten Kontinente werden anschließend mit der Bandsäge und Stichsäge ausgeschnitten.

### 6. Schritt:
Die ausgeschnittenen Kontinente werden mit Hilfe einer Feile verwendet.
Tipp: Die Kontinente müssen nicht detailliert ausgeschnitten werden. 

![Ausgeschnittene Grund Kontinente](/images/thunderbirds/Bild_5.png)
![Kontinent](/images/thunderbirds/Bild_6.png)

### 7. Schritt:
Die zugeschnittenen Kontinente werden auf die Basis Spanplatte (100cm x 60cm x 2cm) gelegt. 

### 8. Schritt:
Die Konturen der zugeschnittenen Kontinente werden mit einem Stift gezeichnet damit eine Befestigung erfolgen kann.

![Kontinente auf der Basis Holzplatte](/images/thunderbirds/Bild_7.png)

### 9. Schritt:
Die Kontinente werden nun mit Schrauben von hinten befestigt. Der Akkubohrer reicht in diesem Fall aus.

![Schrauben](/images/thunderbirds/Bild_8.png)

### 10. Schritt:
Erneut werden die Kontinente unter Verwendung der Vorlage auf das dünne Holz gezeichnet. Mit Hilfe einer Stichsäge werden die Kontinente ausgeschnitten.
Achtung: Konturen der Kontinente müssen sehr detailliert sein.

![Konturen auf dem dünnen Holz](/images/thunderbirds/Bild_9.png)

### 11. Schritt:
Kontinente mit der Spraydose schwarz matt lackieren.

![Lackiertes dünnes Holz](/images/thunderbirds/Bild_10.png)

### 12. Schritt:
Die getrockneten Kontinente werden auf die befestigten Kontinente gelegt und es wird „zentral“ ein Loch, dass durch alle 3 Platten geht. Für die Bohrung wird eine Bohrmaschine mit einem Holz Bohraufsatz verwendet.

![Bohraufsätze](/images/thunderbirds/Bild_40.png)
![Gebohrtes Loch](/images/thunderbirds/Bild_12.png)

### 13. Schritt:
Nun kann das LED Strip an den Kontinenten befestigt werden. Das LED Strip wird an den markierten Stellen geschnitten und gelötet. Das LED Strip wird mit Sekundenkleber befestigt.

![LED kleben](/images/thunderbirds/Bild_13.png)
![LED Weg](/images/thunderbirds/Bild_14.png)

### 14. Schritt:
Die dünnen schwarzen Kontinente werden mit dem Kleber („kleben statt bohren“) auf die Kontinente geklebt.

![Dünne Kontinente geklebt](/images/thunderbirds/Bild_15.png)

### 15. Schritt:
Die Cremetuben werden einmal bis zum Deckel geschnitten. Anschließend mit dem Kleber „kleben statt bohren“ bestrichen und von hinten in die Löcher der Kontinente geschoben und mit einem Edding von vorne ausgebreitet.
Tipp: Sollte die Tube nicht perfekt kleben, einfach nochmal mit Sekundenkleber nachhelfen und erneut mit dem Edding ausgebreitet.

![Tube](/images/thunderbirds/Bild_16.png)
![Tube von oben](/images/thunderbirds/Bild_17.png)
![Tube Schnitt](/images/thunderbirds/Bild_18.png)

### 16. Schritt:
Um die kleinen Inseln befestigen zu können wurden Schrauben in die Basis Holzplatte geschraubt und mit dem Kleber „kleben statt bohren“ festgeklebt.

![Insel](/images/thunderbirds/Bild_19.png)
![Insel Seite](/images/thunderbirds/Bild_20.png)

### 17. Schritt:
An die Photoresistoren werden Kabel dran gelötet und eins der Beinchen des Photoresistors wird mit Isolierband abgeklebt. Anschließend werden die Photoresistoren in die Cremetuben gesteckt.

![Photoresistor](/images/thunderbirds/Bild_21.png)
![Isolierung](/images/thunderbirds/Bild_22.png)

### 18. Schritt:
Als nächstes wird der Satellit gebaut. Dafür wird erneut das dünne Holz verwendet. Es werden 5 Quadrate mit den Maßen 8cm x 8cm zugeschnitten.

![Satellit_oben](/images/thunderbirds/Bild_23.png)
![Satellit_unten](/images/thunderbirds/Bild_24.png)
![Satellit_Seite](/images/thunderbirds/Bild_25.png)
![Satellit_komplett](/images/thunderbirds/Bild_26.png)

### 19. Schritt:
Es wird das Glas einer Taschenlampe auf das erste Servo geklebt. Darauf kommt das zweite Servo. Zum Schluss wird die Laseriode auf das zweite Servo geklebt.

![Servo_unten](/images/thunderbirds/Bild_27.png)
![Servo_seite](/images/thunderbirds/Bild_28.png)
![Servo_laser](/images/thunderbirds/Bild_29.png)

### 20. Schritt:
Es werden 3 Plexiglas Platten (100cm x 7cm x 2mm) geschnitten. Diese müssen anschließend mit Heißkleber zusammen geklebt werden.

![Plexi](/images/thunderbirds/Bild_30.png)
![Plexi_kleben](/images/thunderbirds/Bild_31.png)
![Plexi_komplett](/images/thunderbirds/Bild_32.png)

### 21. Schritt:
Das Zusammengeklebte Plexiglas wird mit schwarzem transparenten Spray lackiert.

![Plexiglas schwarz](/images/thunderbirds/Bild_37.png)

### 22. Schritt:
Es wird ein Stück Holz an der Basis Holzplatte mit dem Kleber "kleben statt kleben" befestigt.

![kleines Holz](/images/thunderbirds/Bild_38.png)


### 23. Schritt:
Ein Holzstab wird an zwei Eckseiten abgefeilt, an das kleine Stück Holz mit zwei Schrauben befestigt und in das Plexiglas Dreieck geschoben.

![Holzstab](/images/thunderbirds/Bild_33.png)
![Holzstab geschraubt](/images/thunderbirds/Bild_39.png)
![Plexi_Holzstab](/images/thunderbirds/Bild_34.png)

### 24. Schritt:
Die Kabel werden durch das Plexiglas Dreieck gezogen und der Satellit mit dem Kleber "kleben statt bohren" an der Spitze befestigt.

![Satellit und Kabel](/images/thunderbirds/Bild_41.png)


### 24. Schritt:
Zum Schluss werden die Kabel auf eine Platine (10cm x 10cm) gelötet.
Die genaue Verlötung sieht man auf dem Schaltplan.

![Platine](/images/thunderbirds/Bild_35.png)
![Platine_löten](/images/thunderbirds/Bild_36.png)

### 25. Schritt:
Sollte keine Platine verwendet werden kann auch ein Board verwendet werden und nach folgendem Schaltplan gesteckt werden.

![Schaltplan Licht](/images/thunderbirds/Thunderbirds_Schaltplan_Board.png)
![Schaltplan Joystick](/images/thunderbirds/Thunderbirds_Schaltplan_Joystick_Board.png)

---

# 6. Ausblick
* LED Strip in die Halterung einbauen, als Sternenhimmel.
* Satellit mit einem 3D Drucker drucken lassen.


