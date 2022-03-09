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

## Multicast per Web-Oberfläche einstellen

Mit der Web-Oberfläche kann man die Funktion Multicast auf einem QuattroPod einstellen. Anschließend muss man das Verfahren auf jedem QuattroPod-Gerät wiederholen, das in derselben Multicast-Gruppe verwendet werden soll.

* Um die Web-Oberfläche zu erreichen, notieren Sie sich die `Infrastruktur-IP-Adresse`, die unten links auf der Startseite angezeigt wird.

![](/assets/img/QuattroPod_IP.png)

* Rufen Sie nun Ihren Web-Browser auf.

![](/assets/img/Google_Chrome.png)

* Klicken Sie mit der Maus in die Adressleiste des Browsers und geben Sie die IP-Adresse des QuattroPod Gerätes ein.

![](/assets/img/IP-Address.png)

### Sich als Admin anmelden

* Geben Sie das Admin-Kennwort ein und klicken Sie auf `OK`, um sich anzumelden. Standardmäßig lautet das Kennwort `000000`. Wenn dieses Kennwort nicht akzeptiert wird setzen Sie das Gerät per [Reset-Schalter](reset.md#hardreset) zurück.

![](/assets/img/QuattroPod-Login.png)

### Multicast aktivieren

* Wählen Sie den Menüpunkt `Admineinstellungen`:

![](/assets/img/quattropod.select.admin.png)

* Wählen Sie den Menüpunkt `Multicast`aus:

![](/assets/img/multicast_option.png)

* Aktivieren Sie die Option `Multicast`. Anschließend geben Sie einen Namen für die Cast-Gruppe im Feld `Besetzungsgruppe` ein. Schließlich geben Sie die `SSID` und das `Kennwort` eines WLANs ein z.B. das WLAN Ihrer Schule, über das die Multicast-Daten gesendet werden sollen:

![](/assets/img/multicast.websetting.on.png)

* Die Einstellungen werden erst nach einem Neustart wirksam:

![](/assets/img/restart.png)

* Nach dem Neustart startet der Empfänger im Multicast-Modus. Die angegebene Cast-Gruppe und das verbundene WLAN werden oben angezeigt:

![](/assets/img/Multicast_activated.png)

### Multicast deaktivieren

* Wählen Sie den Menüpunkt `Admineinstellungen`:

![](/assets/img/quattropod.select.admin.png)

* Wählen Sie den Menüpunkt `Multicast`aus:

![](/assets/img/multicast_option.png)

* Schalten Sie die Funktion `Multicast` aus:

![](/assets/img/multicast.websetting.off.png)

* Die Einstellungen werden erst nach einem Neustart wirksam:

![](/assets/img/restart.png)

* Nach dem Neustart startet der Empfänger im Multicast-Modus. Die angegebene Cast-Gruppe und das verbundene WLAN werden oben angezeigt:

![](/assets/img/Multicast_activated.png)

#### Host/Casting Einstellungen überprüfen

Nach der Deaktivierung der Funktion Multicast müssen vier Einstellungen zur Host-Kontrolle und zu den Streamingprotokollen überprüft werden. 

* In der Web-Oberfläche wählen Sie den Menüpunkt `Admineinstellungen` aus:

![](/assets/img/quattropod.select.admin.png)

Überprüfen Sie die folgenden empfohlenen Einstellungen:

* [Antrag automatisch genehmigen](adv.settings.md#Host-Control): `AUS`
* [Bildschim teilen](adv.settings.md#Host-Control): `EIN`
* [AirPlay](adv.settings.md#AirPlay): `EIN`
* [Google Cast](adv.settings.md#google-cast): `EIN`

## Multicast per CMS einstellen

Mit dem CMS ([Central Management System](cms.md)) kann man Multicast auf mehreren QuattroPod-Geräten gleichzeitig einstellen.

* Wählen Sie alle QuattroPod-Empfänger aus, die einstellt werden sollen:

![](/assets/img/multicast.select.all.png)

* Klicken Sie auf die Schaltfläche `Device` -> und wählen Sie die Funktion `Multicast setup` aus.

![](/assets/img/multicast.select.multicastsetup.png)

### Multicast aktivieren

* Schalten Sie die Funktion `Multicast` ein:

![](/assets/img/multicast.enable.multicastsetup.png)

* Geben Sie einen Namen für die Cast-Gruppe im Feld `Group ID` ein. Schließlich geben Sie die `SSID` und das `Kennwort` eines WLANs ein z.B. das WLAN Ihrer Schule, über das die Multicast-Daten gesendet werden sollen. Zum Übernehmen der Einstellungen klicken Sie auf `Apply`:

![](/assets/img/multicast.settings.png)

* Die Einstellungen werden erst nach einem Neustart wirksam:

![](/assets/img/multicast.reboot.png)

* Nach dem Neustart startet der Empfänger im Multicast-Modus. Die angegebene Cast-Gruppe und das verbundene WLAN werden oben angezeigt:

![](/assets/img/Multicast_activated.png)

### Multicast deaktivieren

* Wählen Sie alle QuattroPod-Empfänger aus, auf denen die Funktion Multicast deaktiviert werden sollen:

![](/assets/img/multicast.select.all2.png)

* Klicken Sie auf die Schaltfläche `Device` -> und wählen Sie die Funktion `Multicast setup` aus.

![](/assets/img/multicast.select.multicastsetup.png)

* Schalten Sie oben die Funktion `Multicast` aus:

![](/assets/img/multicast.settings2.png)

+ Zum Bestätigen klicken Sie auf `Apply`:

![](/assets/img/multicast.apply.deactivate.png)

* Die Einstellungen werden erst nach einem Neustart wirksam. Bestätigen Sie mit `Confirm`:

![](/assets/img/multicast.reboot.png)

* Nach dem Neustart startet der Empfänger im Standard-Modus. Die SSID des QuatroPod-Empfängers wird wieder angezeigt:

![](/assets/img/quattropod.landingpage.ssid.png)

#### Host/Casting Einstellungen überprüfen

Nach der Deaktivierung der Funktion Multicast müssen vier Einstellungen zur Host-Kontrolle und zu den Streamingprotokollen überprüft werden. 

* Wählen Sie Ihre Geräte noch einmal aus:

![](/assets/img/multicast.select.all.png)

* Klicken Sie auf die Schaltfläche `Device` -> und wählen Sie die Funktion `Host/Casting` aus.

![](/assets/img/multicast.select.hostcasting.png)

Überprüfen Sie die folgenden empfohlenen Einstellungen:

![](/assets/img/multicast.settings.hostcasting.png)

## Sender koppeln

* Schalten Sie den Sender auf `PC` um:

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