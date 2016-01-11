---
title: 'Thunderbird/Lightning mit eGroupware verwenden'
author:
 - name: André Hagenbruch
date: 2015-12-10
...
[Übersicht](/)

#Thunderbird + Lightning mit eGroupware verwenden
0. Unter [http://egroupware.ruhr-uni-bochum.de/](http://egroupware.ruhr-uni-bochum.de/) finden sich detailierte Informationen zu eGroupware. Zunächst muss man für ein **Funktionskonto** einen Kalender beantragen, der dann innerhalb einiger Tage von IT.Services angelegt wird. Im Laufe dieses Prozesses bekommt man zwei Mails: In der ersten wird man darüber informiert, dass ein eGroupware-Konto eingerichtet wurde, in der zweiten folgt dann die eigentlich wichtige Information, dass der Kalender angelegt wurde.

1. Mit den Anmeldedaten des Funktionskontos an der mitgeteilten URL (in diesem Fall [https://bibliographie.egroupware.rub.de](https://bibliographie.egroupware.rub.de)) anmelden.

![Abb. 1: Anmeldung bei eGroupware](img/kalender1.png)

2. Auf "Admin" klicken, dann sieht man links neben "Offizielle EGroupware Nutzungsstatistik" einen blauen Punkt, auf den man klickt.

![Abb. 2: Admin-Menü aktivieren](img/kalender2.png)

3. Auf "Benutzerkonten" klicken.

![Abb. 3: Benutzerkonten auswählen](img/kalender3.png)

4. Auf "Hinzufügen" klicken, um einen neuen Benutzer anzulegen.

![Abb. 4: Neues Benutzerkonto anlegen](img/kalender4.png)

5. Login und Passwort vom eigenen RZ-Konto eintragen und die Haken wie unten gezeigt setzen. Zuletzt "Hinzufügen" klicken.

**Hinweis**: *Sollte der neue Benutzer danach nicht in der Übersicht auftauchen, muss man auf den Anfangsbuchstaben des Login-Namens in der Kopfzeile der Tabelle klicken*.

![Abb. 5: Benutzerkonto-Formular](img/kalender5.png)

6. In Thunderbird einen neuen Kalender im Netzwerk anlegen mit Protokoll "CalDAV" und der URL https://bibliographie.egroupware.rub.de/groupdav.php/**rzlogin**/calendar, wobei **rzlogin** durch den eigenen Anmeldenamen beim Rechenzentrum ersetzt werden muss.

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

13. Dies sollte man für den Bereich "Lesen" auch tun, um Terminabsprachen zu erleichtern.

![Abb. 13: Zugriffsrechte](img/kalender13.png)