# Iriserkennung

### Ziele
- Auge/Iris wird erkannt
- Unterschied erkennen zwischen Auge und Objekt
- schönes Design mit js Elementen 
- strukturiete Programmierung 

### Nichtziele
- merken von Augenpaaren


# 
### Präzise Themenbeschreibung 
Zuerst wird programmiert und eine Schaltung erstellt.<br>
Ein wichtiges Bautteil ist die Kamera, welche für das Erkennen des Auges zuständig ist. <br>
Zusätzlich tragen Soft und Hardware einen Teil dazu bei. 

#

### Verwendete Technologien

#### SW
- [OpenCV](https://opencv.org/)
- Java Framework: highChart oder chartJS
- [Docker](www.docker.com)
 
#### HW
- [Raspberry PI Webcam](https://at.rs-online.com/web/p/raspberry-pi-kameras/9132664/)
- [Raspberry PI IR Cam](https://at.rs-online.com/web/p/raspberry-pi-kameras/9132673/)
- Raspberry Pi Noir Camera Module V2

#

### Teamzusammensetzung (Projektleiter muss definiert werden)
**Projektleiter:** David Thaller <br>
**Teammitglieder:** Mona Angerer, Julian Jaklitsch

#

### Zeitplan 
| Was?                                                     | Wann?         |
| -------------                                            |-------------  | 
| Planung                                                  | 25.02.2021    |
| Anfang des Projektes, Einteilung                         | 11.03.2021    |   
| Erweiterung und Verbesserung                             | 25.03.2021    |  
| Python wurde installiert & Pluginsliste (OpenCV)         | 15.04.2021    |  
| Kamera wurde aktiviert                                   | 22.04.2021    |   
| beschädigte Ordnerstruktur                               | 29.04.2021    |
| neuer und besserer Raspberry                             | 06.05.2021    |  
| Iriserkennung funtioniert                                | 13.05.2021    |  
| recherche zu ChartJS                                     | 20.05.2021    |  
| Iriserkennung erfolgreich mit neuem Raspberry            | 27.05.2021    |  
| Frei                                                     | 03.06.2021    |  
| Server und darauf ChartJS zum Laufen gebracht            | 10.06.2021    |  





#

### Protokolle
#### PDF: 
[cpr (2) (2).pdf](https://github.com/ThallerDavid/cpr.team2/files/6669024/cpr.2.2.pdf)


#### 11.03.21 
1. Raspberry anschließen
2. Starten
3. Kamera anschließen
4. In Terminal ein Update laden mit der Zeile: "SUDO APT-GET UPDATE && SUDO APT-GET UPGRADE" und anschließend die Rasberrykonfiguration öffnen mit "SUDO RASPI-CONFIG" 
5. Kamera ausgewählt
6. neu gebooted
7. im Terminal überprüft, ob die Kamera funktioniert, mit dem Befehl "VCENCMD_CAMERA"
8. es wurde mit dem Befehl "RASPISTILL -F" die Kamera gestartet und mit "RASPISTILL -T -O IMGNAME.jpg" ein Bild gemacht, mit entsprechender Zeitverzögerung 
-> Es wurde erfolgreich gesteckt und mithilfe dem Terminal wurde die Kamera aktiviert. Zusätzlich wurde ein Foto geschossen.


#### 15.04.21 
- Es wurde Python installiert mit dem Befehl "sudo apt-get install python3"
- Die Liste der Plugins von OpenCV: "sudo apt-cache search opencv"


#### 22.04.21 
- Kamera wurde aktiviert


#### 29.04.21 
- Ordnerstruktur wurde beschädigt 
- Es wurde von vorne begonnen

#### 06.05.21 
- Arbeiten mit neuem und besseren Raspberry 
- Raspberry wurde neu aufgesetzt
- nun können wir effektiver arbeiten


#### 13.05.21 
- Iriserkennung wurde erfolgreich programmiert


#### 20.05.21 
- recherche zu ChartJS


#### 27.05.21 
- aktuell: Iriserkennung funktioniert mit neuem Raspberry

![WhatsApp Image 2021-05-27 at 12 50 23](https://user-images.githubusercontent.com/74356324/119813980-3245ec00-beea-11eb-9ce8-f9c13b78149e.jpeg)



### Link zu Github Repo
https://github.com/ThallerDavid/cpr.team2/edit/main/Description.md
