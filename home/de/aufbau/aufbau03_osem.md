# Online Aktivierung
Hier wird die Einbindung der senseBox in unser Sensornetzwerk durch die Registrierung auf der openSenseMap beschrieben.

## Registrierung auf der openSenseMap
Ein Software-Programm für einen Arduino Mikrocontroller könnt ihr an der Dateiendung `.ino` erkennen. Eine solche Datei benötigt ihr, um eure senseBox mit der openSenseMap im Internet zu verbinden. Den passenden Sketch bekommt ihr zusammen mit einer E-Mail zugeschickt, wenn ihr eure Station bei auf der [openSenseMap registriert](http://www.opensensemap.org/register).

Bei Schritt 2 der Registrierung wirst du nach einem Hardware Setup gefragt. Wähle dort die „senseBox:home“ aus und setze danach je nach Ausgabe den Haken bei „senseBox:home (Ethernet)“ oder „senseBox:home (WLAN)“.

## Programm auf die Station laden
Nachdem ihr den Anhang der Email heruntergeladen habt, müsst ihr dieses Programm auf eure senseBox laden. Wie man genau ein Programm auf den Mikrocontroller lädt, ist bereits in Abschnitt 2 der Anleitung ausführlich erklärt worden. Hier die Schritte in der Übersicht:

- Arduino Anwendung öffnen
- In der Menüleiste `Datei` → `Öffnen` auswählen und die `sensebox.ino` Datei auswählen
- Dialog mit "Ja" bestätigen
- Das Programm über das **Pfeil** Icon auf den Mikrocontroller laden
- Warten bis das Programm übertragen wurde

Wenn alles richtig gelaufen ist, könnt ihr nun auf der openSenseMap eure Station auswählen und verfolgen wie Messungen kontinuierlich übertragen werden. Probiert es aus und sucht dort eure senseBox!
