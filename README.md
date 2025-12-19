>🇺🇸🇬🇧🇫🇷🇪🇸🇮🇹🇪🇺🇺🇦🇦🇺🇫🇮🇨🇿🇧🇷🇨🇦🇰🇿🇨🇴🇲🇶🇳🇬🇸🇨🇪🇭🇺🇾🇺🇬🏳️🏴‍☠️
>
>_International users: Please use your Browsers translation feature. This Text is written in german language. A translation from german into other languages mainly generates better results then a translation from any language into german. Thanks for your compliance._
>

# Wetter•Freund

Der Wetter•Freund ist eine DIY-Wetterstation mit ESP und Arduino. Gebt nicht 150 € (oder mehr) auf Amazon aus – baut euch einfach eine eigene smarte Wetterstation mit WebUI und coolen Funktionen die keine kommerzielle Wetterstation bietet – für nur ein paar Euro. Ihr braucht lediglich ein paar elektronische Bauteile, die ihr problemlos auf AliExpress kaufen könnt (insgesamt etwa 5 €), sowie ein Gehäuse für rund 15 €. Nutzt gerne meinen Code wie er ist oder passt ihn an eure Bedürfnisse oder Sprachen an. Aber was das Wichtigste ist: Habt Spaß dabei!

❗️Diese Wetterstation ist **nur** für Temperatur, Luftdruck und Luftfeuchte sowie daraus errechnete/abgeleitete Werte. An Messgeräten für Wind und Regen arbeite ich noch.

### Hardware:
- ESP-02S (8285) - aber jeder ESP8266 sollte funktionieren! Für ESP32 muss man andere Bibliotheken einfügen. Aber ein ESP32 ist gar nicht nötig.
- BME280 Sensor
- Buck-Converter 5V/3,3V
- LED mit Farbwechsel (zur Vermeidung von Flugzeugkollisionen ... 😉)
- Notfalltaster für den AP-Modus

### Softwarefunktionen:
- Vorschau der Live-Werte
- Daraus errechnete/ermittelte Werte (Barometer, Taupunkt, Wetterwarnungen)
- Standort (manuelle Eingabe)
- MQTT
- Verschiedene Logs
- Anzeige von Systemdaten
- OTA(!)
- JSON
- RESET
- Automatisierte Anbindung an HomeAssistant über MQTT
- Integration für HomeAssistant ist in Arbeit ...

### Was er nicht kann:
- KEINE nutzlose oder unbenutzbare Spionageapp!
- KEINE Cloud irgendwo am Ende der Welt. Eure Daten bleiben in eurem Haus!
- KEIN schickes Wetter-Dashboard. Es ist eigentlich ein Admin-Tool. Aber wer behauptet, dass Admin-Tools langweilig aussehen müssen ...
  
Startet die Reise in meinem [WIKI](https://github.com/dummbold/Wetter-Freund/wiki)

‼️ ACHTUNG: neues GUI ist quasi schon fertig und befindet sich in der Testphase. Dazu muss der ESP aber komplett gelöscht werden (andere EEPROM-Struktur). Nehmt euch die Zeit die Hardware in aller Ruhe zu bauen. Bis ihr fertig seid gibt es dann hier auch den neuen Sketch mit der neuen Oberfläche – Stand: 19.12.2025‼️


