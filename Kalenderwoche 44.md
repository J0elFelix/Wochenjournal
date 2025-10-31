## Montag:

##### Am Morgen wollte ich noch an meinem Umbraco Testing Projekt weiterarbeiten. Als ich das Projekt gestartet habe ist folgender Fehler gekommen: ==BootFailedException: Boot failed: Umbraco cannot run. See Umbraco's log file for more details==. Ich bin soweit gekommen das etwas bei meiner Datenbank nicht richtig ist denn, der Pfad zur Datenbank kann nicht gefunden werden. Beim Weekly mit Joel habe ich ihn bezüglich dem Fehler gefragt und als ich dann Die Datenbank refreshed habe hat es wider wie gewollt funktioniert. Beim Weekly habe ich auch noch einen neuen Task bekommen denn ich erledigen kann. Ich kann nun ein neuen teaser-namespace erstellen der ==plain-no-border== heisst. Ich soll es neu stylen nach dem Mockup. Nach dem Weekly habe ich das Repo geklont und einen neuen Branch erstellt um darauf zu arbeiten. Ich hatte noch keine Rechte um einen Branch zu Publishen und musste deshalb kurz nachfragen, damit ich die Rechte bekomme. Nach dem Mittag war das Team-Meeting, dort war nicht sehr viel los und danach bin ich kurz Zahnarzt gefahren weil ich noch etwas abholen musste. Danach habe ich an meinen Task weitergearbeitet.

##### Mockup:

![[Mockup.png]]

---

## Dienstag:

##### Am Morgen habe ich am Namespace weitergearbeitet und bin okay weit gekommen. Ich muss noch herausfinden wie ich den style richtig implementiere damit er auch zieht. Ich habe nun in etwa herausgefunden wie ich den style korrekt implementieren kann. Was sich sicherlich noch nachschauen muss ist wie ich den Text über das Bild bringe und auch wider mit einem Attribute machen kann damit je nach Attribut der Text oben oder unten ist. Ich muss auch noch nachfragen ob man die Farben vom Hintergrund ändern kann oder nicht. Nach dem Mittag habe ich mich angefangen auf die Präsentation vorzubereiten. Ich habe nochmal alles geprüft und es hat auch alles funktioniert. Die Präsentation hat auch gut funktioniert. Ich habe dann noch Rückmeldung bekommen, Der Text über der Zahl soll grösser sein und die Zahl selbst auch. Ausserdem sollen es nicht 2 Spalten sein sondern 3. Wenn es weniger sind dann werden nun mal nur 2 Spalten angezeigt. Wenn es mehr als 3 sind wird diese Tabelle eine Spalte weiter unten dargestellt usw. Die Anpassungen am Style habe ich schon gemacht und ich muss nun nur noch schauen das man nicht mehr als 3 Spalten auf eine Reihe machen kann.

##### Aktueller Stand Namespace:

![[Zwischenstand Teaser-Namespace.png]]

##### Aktueller Stand Yearbook Tabelle:

![[Yearbook Tabelle angepasst.png]]

---

## Mittwoch:

##### Schule

---

## Donnerstag:

##### Schule (Prüfung M320)

---

## Freitag:

##### Heute bin ich den ganzen Tag im Homeoffice und habe am morgen noch einen Zahnarzt Termin. Ich habe am Morgen noch an der Yearbook Tabelle weitergearbeitet und habe diese nun fertig. Ich musste nur noch das Layout ändern das der Umbruch nicht bei 3 sondern bei 4 Spalten gemacht wird das nur 3 Spalten auf einer Zeile sind und die vierte dann auf einer neuen Zeile darunter angelegt wird. Ich wusste nicht genau wie ich das lösen sollte und habe mal den Code genau durchgeschaut. Im Code wurde der Tabelle je 50% Breite gegeben, heisst das wenn 2 gemacht werden 100% ist und das Maximum erreicht ist. Ich musste somit nur die Breite auf 33.333% Stellen damit 3 Tabellenspalten auf einer Zeile platz haben. Danach habe ich einen Pull Request gemacht und dies auf Testadmin überprüft. Danach habe ich Joel noch gefragt ob ich auch noch ein Release bis auf Dev machen muss damit man es auch sieht wenn man auf die Testadmin URL geht. Ich konnte es dann Releasen bis auf Dev dies hat auch ohne jegliche Fehler funktioniert, jedoch wird auf der [Testadmin](https://testadmin.ibe.migros.ch/operations) Seite immer noch das andere Design von mir dargestellt. Ich hab Joel gefragt ob das so sein muss oder ob ich noch eine zusätzliche Änderung machen muss. Wie haben es dann zusammen im Call angeschaut um 11 Uhr. Das Problem war Caching. Wenn man es im Inkognito Modus Öffnet das funktioniert es. Somit konnte ich das Ticket schliessen und mit dem Teaser weitermachen. Davor habe ich aber noch von der neuen Version einen Screenshot an Sandra geschickt damit Sie weiss wie das neue Design nun aussieht. Beim Teaser bin ich gerade dabei das Attribut zu machen damit man dieses setzten kann ob das Bild oben sein soll und der Text unten oder das Bild ist unten und der Text ist oben. Nach dem Mittag habe ich noch ein bisschen am Teaser weitergearbeitet dort muss ich noch schauen das, dass CSS richtig funktioniert. Danach habe ich noch bisschen gelernt, weil wir nächste Woche Modul-Test haben. Ich habe beim Teaser noch den Abstand vom Texthintergrund zum Bild weggemacht damit es nun aussieht als gehöre es zusammen. Mit dem Parameter für Bild oben und Bild unten muss ich nochmal schauen weil ich sehr wahrscheinlich JavaScript brauche und schauen muss ob JavaScript funktioniert zum Verbinden.

##### Fertige Yearbook Tabelle:

![[Fertige Yearbook-Tabelle.png]]

##### Aktueller Stand Teaser:

![[Aktueller Stand Teaser.png]]

---
