# Firmware aktualisieren

## Warum aktualisiert man die Firmware? 

Um von den neuesten Funktionen des QuattroPods zu profitieren, können Sie das neueste Firmware-Update schnell und bequem über das Internet installieren. Bei der Installation einer neuen Firmware werden die bisherigen Einstellungen mitgekommen.

Dabei benötigen Sie einen [Internetzugang](internet.md) zum Internet bzw. mit Ihrem Router.  Wenn der QuattroPod mit Ihrem LAN bzw. mit Ihrem WLAN verbunden ist, wird eine von Ihrem Netzwerk vergebenen IP-Adressen mit der Bezeichnung `Infrustructure IP` auf dem Bildschirm angezeigt, wie unten abgebildet:

![](/assets/img/QuattroPod_IP.png)

## Sender anschließen und einschalten

Bei einer Firmware-Aktualisierung ist es wichtig, die Sender nicht zu übersehen. Achten Sie bitte darauf, den Empfänger und alle Sender auf dem selben Stand zu halten.

![](/assets/img/QuattroPod_RX_TXs_PoweredON_Mini.jpg)

## In der Web-Oberfläche anmelden

Die Aktualisierung wird über die Web-Oberfläche in einem beliebigen Web-Browser durchgeführt.

* Notieren Sie sich die IP-Adresse, die unten links auf der Startseite angezeigt wird.

![](/assets/img/QuattroPod_IP.png)

* Rufen Sie nun Ihren Web-Browser auf.

![](/assets/img/Google_Chrome.png)

* Klicken Sie mit der Maus in die Adressleiste des Browsers und geben Sie die IP-Adresse des QuattroPods ein.

![](/assets/img/IP-Address.png)

* Nachdem Sie die Eingabetaste gedrückt haben, sollte nun die Einstellungsoberfläche des QuattroPods erscheinen. Geben Sie das Kennwort ein. Standardmäßig lautet es `000000`. Wenn dieses Kennwort nicht akzeptiert wird, müssen die Sie die [Standardeinstellungen zurücksetzen](reset.md).

![](/assets/img/QuattroPod-Login.png)

* Während der ersten Anmeldung, müssen Sie das Admin-Kennwort ändern. Danach müssen Sie sich noch einmal anmelden.

![](/assets/img/new_password.jpg)


## Aktualisierung starten

* Klicken Sie auf `Admineinstellungen`:

![](/assets/img/quattropod.select.admin.png)

* Klicken Sie auf `Update`:

![](/assets/img/Admineinstellungen_Update.png)

* Um die Aktualisierung zu starten, setzen Sie ein Häkchen bei `Alle auswählen`, anschließend klicken Sie auf `Upgrade`.

![Firmware-Version aktualisieren](/assets/img/Update.jpg)

!!! tip "Hinweis"
    
	Sollten die Sender nach der Firmware-Aktualisierung nicht mit dem Empfänger verbinden können, müssen sie neu [gekoppelt](pairing.md) werden.

## Firmware mit dem CMS installieren

Mit dem CMS ([Central Management System](cms.md)) kann man die neueste Firmware vom Internet auf mehreren EZCast Pro II bzw. QuattroPod Geräten installieren.

* Wenn eine neue Firmware für den Empfänger bzw. für den Sender zur Verfügung steht, taucht die Meldung ![](/assets/img/CMS-firmware.available.png) neben dem Gerät auf:

![Die Firmware wird installiert](/assets/img/CMS-firmware.OTA.select.devices.png)

* Wählen Sie die gewünschten Geräte aus, anschließend klicken Sie auf die Schaltfläche `Remote` -> und wählen Sie die Funktion `Device firmware upgrade`.

![Die Firmware wird installiert](/assets/img/CMS-firmware.install.latest.firmware.png)

* Unter der Registerkarte `OTA`, klicken Sie einfach auf die Schaltfläche `Apply`, um die Aktualisierung durchzuführen:

![Die Firmware wird installiert](/assets/img/CMS-firmware.upgrade.OTA.png)

Die neue Firmware wird heruntergeladen und automatisch installiert. 

* Während der Aktualisierung des Senders erscheint folgende Meldung:

![Firmware-Version aktualisieren](/assets/img/Update.U01c.png)

* Während der Aktualisierung des Empfängers erscheint folgende Meldung:

![Firmware-Version aktualisieren](/assets/img/Update.R01.png)

!!! warning "Achtung"
    
	Unterbrechen Sie während des Updates nicht die Stromversorgung.

![](/assets/img/ProIIStick_Firmware_installing.png)

!!! tip "Hinweis"

     Sollten die Sender nach der Firmware-Aktualisierung nicht mit dem Empfänger verbinden können, müssen sie neu [gekoppelt](pairing.md) werden.


