# Fernweh · Landstraße 100

Ein früher Roadtrip-Prototyp für Windows, gebaut mit Unity. Eine prozedurale Strecke von 100 Kilometern, ein alter Pickup und bis zu drei Reisende: allein fahren oder gemeinsam an Tankstellen, Rastplätzen und Dörfern anhalten.

[English](README.en.md) · [Asset-Credits](CREDITS.md)

## Starten

Den gesamten Download entpacken und `Fernweh.exe` starten. Der Datenordner und die mitgelieferten Unity-Dateien müssen neben der Anwendung bleiben. Im Menü Namen und Figur wählen, dann **Allein aufbrechen** oder einen Raum erstellen.

## Zusammen spielen

- **Internet:** Der Gastgeber wählt **Raum erstellen** und teilt den Raumcode. Freunde geben ihn bei **Beitreten** ein. Die Verbindung verwendet Unity Relay; dieser experimentelle Modus benötigt Internet und einen verfügbaren Relay-Dienst.
- **LAN:** Im selben lokalen Netzwerk wählt der Gastgeber **LAN Host**. Freunde tragen seine lokale IP-Adresse ein und wählen **LAN Beitreten**. Standardport: UDP 7777. `127.0.0.1` funktioniert nur auf demselben Computer.
- Ein Raum hat **drei Plätze: ein Gastgeber am Steuer und zwei Mitfahrer**. Alle können bei Stillstand aussteigen und die Umgebung erkunden.
- **F1** öffnet das Raummenü. Verlässt der Gastgeber den Raum, endet die gemeinsame Sitzung. Es gibt noch keinen Gastgeberwechsel und keinen eingebauten Sprachchat.

## Steuerung

| Taste | Aktion |
|---|---|
| WASD / Pfeile | Fahren; S bremst und fährt anschließend rückwärts |
| Maus / C | Umsehen / Fahrerblick zentrieren |
| Leertaste | Handbremse; zu Fuß springen |
| F | Bei Stillstand aussteigen / am Pickup einsteigen |
| WASD / Umschalt | Zu Fuß gehen / rennen |
| E | Gespräch oder Shop; an der Zapfsäule zum Tanken halten |
| Q / G | Gegenstand nehmen oder benutzen / ablegen |
| P | Rucksack öffnen |
| I / B / L | Motor / Innenlicht / Scheinwerfer bzw. Taschenlampe |
| H | Verfügbaren Anhalter mitnehmen oder am Ziel absetzen |
| T / V | Nächsten Halt markieren / hupen |
| Tab | Navi vergrößern |
| N | Tageszeit-Vorschau wechseln |
| R | Pannenhilfe: Pickup auf die Straße zurücksetzen |
| Esc / F1 | Pause bzw. Dialog schließen / Raum- und Hauptmenü |
| F8 | Als Gastgeber den Crew-Auftrag ohne Prämie überspringen |

## Proviant gemeinsam benutzen

Im geöffneten Shop an die Kasse gehen, **E** drücken und kaufen. Jeder Reisende startet mit eigenem Bargeld von 75 €. Der gekaufte Gegenstand erscheint an der Ausgabe. Hinsehen und **Q** einmal drücken nimmt ihn in die Hand; ein weiteres **Q** benutzt oder verbraucht ihn. **G** legt ihn ab. Ein anderer Reisender kann einen abgelegten Gegenstand aufnehmen. Man hält jeweils einen Gegenstand; insgesamt können 24 unbenutzte Gegenstände in der Welt liegen. Mit **P** öffnet man den Rucksack, für Gegenstände in der Welt muss man trotzdem in Reichweite sein. Der Fahrer muss zum Hantieren anhalten, Mitfahrer können auch unterwegs etwas benutzen.

## Sechs Crew-Aufträge

Die gemeinsamen Aufgaben starten automatisch mit mindestens zwei Personen im Raum. Fortschritt und Prämien werden gemeinsam abgeglichen; der Gastgeber kann mit **F8** ohne Belohnung weiterschalten.

| Auftrag | Was ihr macht |
|---|---|
| Kaffeepause zu zweit | Pickup abstellen. Zwei verschiedene Reisende halten gleichzeitig je einen gekauften Kaffee zwei Sekunden lang. Q zum Aufnehmen drücken, noch nicht zum Trinken. |
| Alle mal die Beine vertreten | Zum angezeigten Halt fahren; alle steigen aus und bleiben dort gemeinsam drei Sekunden. |
| Der Beifahrer weiß den Weg | Ein Mitfahrer markiert mit T den nächsten Halt. Gemeinsam hinfahren und dort zwei Sekunden anhalten. |
| Das schlechteste Hupkonzert | Pickup abstellen. Alle drücken innerhalb derselben acht Sekunden einmal V; draußen höchstens 18 Meter vom Auto entfernt bleiben. |
| Der rollende Kiosk | Drei verschiedene Sorten aus Kaffee, Wasser, Brot und Nüssen in Händen oder auf der Ladefläche mitnehmen. Mehr als 100 Meter zum angezeigten nächsten Halt fahren und dort parken. |
| Fahrer hat Pause | Ein Mitfahrer steigt an der Tankstelle aus und hält E zum Tanken, bis insgesamt fünf Liter eingefüllt sind. Bei zu vollem Tank wird die Aufgabe übersprungen. |

Nach Erfolg bekommt jeder eine Prämie. Derselbe Auftrag am selben Ort zahlt in einem Raum nicht mehrfach.

## Was enthalten ist

35 benannte Stopps, begehbare Tankstellenshops, Proviant, kurze Textgespräche, vier Reisenden-Modelle, Verkehr und Anhalter. Die Route führt durch Ebenen, Waldvorland und Gebirgspässe mit zwei befahrbaren Tunneln. Tag und Nacht verändern Licht, Straßenleben und Atmosphäre.

Die Regionennamen Hessen, Bayern und Thüringen sind Kapitel einer **fiktiven** Route. Dörfer und Straßen bilden keine echte Deutschlandkarte ab.

## Stand des Prototyps

Das Spiel ist noch in Entwicklung. Beleuchtung, Fototexturen und detailliertere Figuren treffen auf weiterhin prozedurale Gebäude, Fahrzeuge und Landschaft. Es ist keine fertige fotorealistische Produktion. Multiplayer, Physik und Darstellung können noch Fehler zeigen.

Fortschritt gehört zur aktuellen Sitzung; es gibt noch keinen vollständigen Spielstand zum späteren Fortsetzen. Zu Fuß bleibt man ungefähr 210 Meter beim Pickup. Busse sind Verkehr, kein nutzbarer Linienbetrieb. Gespräche sind unvertont, das Radio ist Dekoration und die Temperaturanzeige dient der Atmosphäre.

Bei einer Fehlermeldung helfen Ort bzw. Kilometer, Spielmodus und eine kurze Beschreibung. Die Unity-Protokolldatei dieses Builds liegt unter `%USERPROFILE%\AppData\LocalLow\Luis Studios\Fernweh\Player.log`.

Quellen und mitgelieferte Drittanbieter-Hinweise stehen in [CREDITS.md](CREDITS.md) und [THIRD-PARTY-NOTICES.md](THIRD-PARTY-NOTICES.md).
