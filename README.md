# DCC-Einmesser
Geschwindigkeit von DCC Loks automatisch einmessen

Diese Verzeichnis enthält 2 Dinge:

1. Arduino-Programm

Software zur Ansteuerung der Lok auf dem Rollenprüfstand und Detektion der Geschwindigkeit
Die Software basiert auf der Command-Station-EX (https://github.com/DCC-EX/CommandStation-EX) und wurde um die Funktionalität zur Geschwindigkeitsermittlung über eine Gabellichtschranke mittels Lochscheibe erweitert.
Die Software (in CommandStation-EX_Speed.zip) wird einfach über die Arduino IDE auf einen Arduino Mega 2560 (ein UNO/Nano geht nicht!) aufgespielt. (Alternativ einfach das Hex-file CommandStation-EX_Speed.hex in einen Arduino Mega 2560 einspielen.) Alle Optionen der CommandStation-EX können zusätzlich aktiviert werden. Hierzu die dortige Beschreibung zu Rate ziehen. Die Gabellichtschranke wird an einen der Pins A8 - A15 des Arduino Mega angeschlossen. Dieser Pin ist daher für andere Ein-/Ausgänge nicht mehr verfügbar.


2. DecoderAutoSpeed.jar

JAVA-Programm zu Ansteuerung der CommandStationEX_Speed. Einfach die Datei ausführen. Es muss JRE (mind. Version 8) installiert sein.

Viel Spaß
