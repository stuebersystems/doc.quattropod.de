# Was ist Multicast?

Die Funktion Multicast erlaubt es Ihnen die Bildschirminhalte eines Gerätes mit Hilfe eines gekoppelten Senders auf mehrere Displays gleichzeitig zu übertragen. 

Mehrere Teilnehmer haben die Möglichkeit, per Knopfdruck ihren Bildschirminhalt auf mehrere Displays zu übertragen. Dabei kann nur ein Teilnehmer auf einmal diese Funktion ausführen.

!!! tip "Hinweis"
    
	Bitte beachten Sie, dass die Funktion Multicast auf dem [QuattroPod Lite](/lite/intro) nicht unterstützt wird. Jeder QuatroPod Empfänger (Standard, Deluxe, oder Mini), der über Multicast betrieben werden soll, muss entsprechend konfiguriert werden.
	
![](/assets/img/Multicast.png)

## Voraussetzungen

* Unterstützte Empfänger: QuattroPod Standard, QuattroPod Deluxe, oder QuattroPod Mini.

* Sie benötigen einen WLAN Access Point.

* Ihr Router muss die `QuattroPod Sender / Empfänger` [Broadcast-Pakete](/ports.md) annehmen.

* Alle QuattroPod-Empfänger müssen sich im gleichen Netzwerk befinden.

![](/assets/img/Broadcast_Pakete.png) 

!!! tip "Hinweis"
    
	Um eine bessere Leistung von Multicast zu erreichen, verbinden Sie den QuattroPod-Empfänger mit dem [Router per LAN-Kabel](internet.md).
	
## Firmware-Version prüfen

* Schalten Sie den QuattroPod-Empfänger ein. Wenn die Startseite erscheint, prüfen Sie, ob die erfolderliche Mindestversion `1.8529.10` angezeigt wird, wie unten abgebildet. Wenn nötig, aktualisieren Sie bitte Ihre [Firmware](firmware-upgrade.md).

![Die Funktion Multicast steht ab der Firmware-Version 1.8529.10 zur Verfügung](/assets/img/quattropod.landingpage.fw.png)

## Erweiterte Einstellungen öffnen

* Um die Web-Oberfläche zu erreichen, verbinden Sie Ihr Endgerät mit der SSID des QuattroPods. Die Zugangsdaten werden oben auf dem Bildschirm angezeigt:

![](/assets/img/quattropod.ssid.connect.png)

* In die Adressleiste eines Webbrowsers geben Sie die `Direct Link IP` des QuattroPods ein. Die Einstellungsoberfläche des QuattroPods erscheint:

![](/assets/img/quattropod_directIP.connect.png)

### Sich als Admin anmelden

* Geben Sie das Admin-Kennwort ein und klicken Sie auf `OK`, um sich anzumelden. Standardmäßig lautet das Kennwort `000000`. Wenn dieses Kennwort nicht akzeptiert wird setzen Sie das Gerät per [Reset-Schalter](reset.md#hardreset) zurück.

![](/assets/img/QuattroPod-Login.png)

## Multicast aktivieren

* Wählen Sie den Menüpunkt `Admineinstellungen`:

![](/assets/img/quattropod.select.admin.png)

* Wählen Sie den Menüpunkt `Multicast`aus:

![](/assets/img/multicast_option.png)

* Aktivieren Sie die Option `Multicast`. Anschließend geben Sie einen Namen für die Cast-Gruppe im Feld `Besetzungsgruppe` ein. Schließlich geben Sie die SSID und das Kennwort eines WLANs ein z.B. das WLAN Ihrer Schule, über das die Multicast-Daten gesendet werden sollen:

![](/assets/img/Cast-Gruppe.png)

* Die Einstellungen werden erst nach einem Neustart wirksam:

![](/assets/img/restart.png)

* Nach dem Neustart startet der Empfänger im Multicast-Modus. Die angegebene Cast-Gruppe und das verbundene WLAN werden oben angezeigt:

![](/assets/img/Multicast_activated.png)

## Sender koppeln

* Schalten Sie den Standard-Sender  bzw. den Mini-Sender auf `PC` um:

![](/assets/img/Sender_koppeln.png)

* Schließen Sie den Sender an den USB-Anschluss des Empfängers an und schalten Sie den Empfänger ein:

![](/assets/img/Sender_koppeln2.png)

Die Meldung **"Pairing..."** erscheint automatisch auf der Startseite des QuattroPods.

![](/assets/img/pairing.png)

Wenn das Koppeln abgeschlossen ist, erscheint die Meldung **"Pairing OK"**.

![](/assets/img/pairing_ok.png)

## Sendertaste drücken und Inhalte zeigen

* Schließen Sie den Sender an Ihr Endgerät an und drücken Sie einfach die rote Sendertaste. 

![](/assets/img/QSG-Mini.Transmitter.png)

!!! tip "Hinweis"
    
	Eine umfassende Anleitung wie Sie den Sender an Ihr spezifisches Endgerät anschließen finden Sie in der [Schnellstartanleitung](quickstart.md#Sender).