---
title: 'Thunderbird/Lightning mit eGroupware verwenden'
author:
 - name: André Hagenbruch
date: 2015-12-10
...

#Thunderbird + Lightning mit eGroupware verwenden
1. Mit dem biblixm7-Passwort bei [https://bibliographie.egroupware.rub.de](https://bibliographie.egroupware.rub.de) anmelden.

![Abb. 1: Anmeldung bei eGroupware](img/kalender1.png)

2. Auf "Admin" klicken, dann sieht man links neben "Offizielle EGroupware Nutzungsstatistik" einen blauen Punkt, auf den man klickt.

![Abb. 2: Admin-Menü aktivieren](img/kalender2.png)

3. Auf "Benutzerkonten" klicken.

![Abb. 3: Benutzerkonten auswählen](img/kalender3.png)

4. Auf "Hinzufügen" klicken, um einen neuen Benutzer anzulegen.

![Abb. 4: Neues Benutzerkonto anlegen](img/kalender4.png)

5. Login und Passwort vom RZ-Konto eintragen und die Haken wie unten gezeigt setzen. Zuletzt "Hinzufügen" klicken.

![Abb. 5: Benutzerkonto-Formular](img/kalender5.png)

6. In Thunderbird einen neuen Kalender im Netzwerk anlegen mit Protokoll "CalDAV" und der URL https://bibliographie.egroupware.rub.de/groupdav.php/**rzlogin**/calendar, wobei "rzlogin" durch das entsprechende Login beim Rechenzentrum ersetzt werden muss.

![Abb. 6: Neuer Kalender in Thunderbird](img/kalender6.png)

7. Alten Kalender exportieren.

![Abb. 7: Kalenderexport](img/kalender7.png)

8. Im nachfolgenden Dialog als Exportformat "iCalendar (*.ics)" auswählen.

![Abb. 8: iCal-Exportformat](img/kalender8.png)

9. Aus eGroupware abmelden und mit dem eigenen Anmeldedaten wieder anmelden. Dann auf "Kalender" klicken.

![Abb. 9: eGroupware-Startbildschirm](img/kalender9.png)

10. In der linken Spalte beim Punkt "Importieren: iCal & CSV" auf iCal klicken.

![Abb. 10: Kalender importieren](img/kalender10.png)
 
11. Im folgenden Dialog die vorher gespeicherte Datei auswählen.

![Abb. 11: Kalender-Datei auswählen](img/kalender11.png)

12. Optional kann man nun noch anderen Gruppenmitgliedern Zugriff auf den eigenen Kalender gewähren.

![Abb. 12: ZUgriff gewähren](img/kalender12.png)

13. Dies sollte man für den Bereich "frei / belegt" auch tun, damit man beim Verschicken von Einladungen sofort sieht, ob jemand zu diesem Zeitpunkt verfügbar ist.

![Abb. 13: Zugriffsrechte](img/kalender13.png)