# ESP32_Whatsapp_Sensor

## Einführung

Dieser Code sorgt dafür, dass ein Ultraschallsensor nach Bewegungen überprüft und einer Telefonnummer die man selbst auswählen kann eine Nachricht auf Whatsapp schickt. Das Ziel ist es ein simples Bewachungssystem zu machen.

## CallMeBot API

https://api.callmebot.com/whatsapp.php?phone=[phone_number]&text=[message]&apikey=[your_apikey]

Man muss der Nummer +34 644 51 95 23 Auf Whatsapp die Nachricht: I allow callmebot to send me messages schicken. Dann bekommt man einen API Key.

## Aufbau

VIN zum VCC des Ultraschallsensor, da er 5V benötigt

Pin 18 vom ESP zum Trigger Pin des Ultraschallsensor

Pin 5 vom ESP zum Echo Pin des Ultraschallsensor

GND zum GND des Ultraschallsensor




![Schaltung](https://github.com/aaabdulkarim/ESP32_Whatsapp_Sensor/assets/117943034/d4ffe09c-ebd7-4e1d-90e5-27ea03de3410)

## Vorbedingungen:
Man benötigt:

- CallMeBot apikey
- ESP32
- HC-SR04 Ultraschallsensor
- UrlEncode Library 

https://api.callmebot.com/whatsapp.php?phone=[phone_number]&text=[message]&apikey=[your_apikey]

## Zusammenfassung
Der Code hat  nach den ersten Versuchen funktionert, jedoch gibt es manchmal Verbindungsprobleme am Anfang
