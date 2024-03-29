# Firmware aktualisieren

## Warum aktualisiert man die Firmware? 

Um von den neuesten Funktionen des QuattroPods zu profitieren, können Sie das neueste Firmware-Update schnell und bequem über das Internet installieren. Bei der Installation einer neuen Firmware werden die bisherigen Einstellungen übernommen.

Dabei benötigen Sie einen [Internetzugang](connect.wifi.lan.md) zum Internet bzw. mit Ihrem Router.  Wenn der QuattroPod mit Ihrem LAN bzw. mit Ihrem WLAN verbunden ist, wird eine von Ihrem Netzwerk vergebenen IP-Adressen mit der Bezeichnung `Infrustructure IP` auf dem Bildschirm angezeigt, wie unten abgebildet:

![](/assets/img/QuattroPod_IP.png)

!!! tip "Hinweis"

	Die Firmware des USB-Senders muss sowohl unter Type-A als auch unter Type-C Modus aktualisiert werden. Dies ist erforderlich, weil der Sender zwei separate Chipsätze besitzt.


## Empfänger und Sender Type-C aktualisieren

* Ziehen Sie den USB-A-Adapter vom Sender ab und schalten Sie den Sender auf `Type-C` um. Schließen Sie den Sender an einen USB-C-Port Ihres Windows/macOS-Rechners an:
	 
![](/assets/img/QSG-TypeC.Windows.png) 


### Sich in der Web-Oberfläche anmelden

Die Aktualisierung wird über die Web-Oberfläche in einem beliebigen Web-Browser durchgeführt.

* Notieren Sie sich die `Infrastruktur-IP-Adresse`, die unten links auf der Startseite angezeigt wird.

![](/assets/img/QuattroPod_IP.png)

* Rufen Sie nun Ihren Web-Browser auf.

![](/assets/img/Google_Chrome.png)

* Klicken Sie mit der Maus in die Adressleiste des Browsers und geben Sie die `Infrastruktur-IP-Adresse` des QuattroPods ein.

![](/assets/img/IP-Address.png)

* Nachdem Sie die Eingabetaste gedrückt haben, sollte nun die Einstellungsoberfläche des QuattroPods erscheinen. Geben Sie das Kennwort ein. Standardmäßig lautet es `000000`. Wenn dieses Kennwort nicht akzeptiert wird, müssen die Sie die [Standardeinstellungen zurücksetzen](reset.md).

![](/assets/img/QuattroPod-Login.png)

### Aktualisierung starten

* Klicken Sie auf `Admineinstellungen`:

![](/assets/img/quattropod.select.admin.png)

* Klicken Sie auf `Update`:

![](/assets/img/Admineinstellungen_Update.png)

* Um die Aktualisierung zu starten, setzen Sie ein Häkchen bei `Alle auswählen`, anschließend klicken Sie auf `Upgrade`.

![Firmware-Version aktualisieren](/assets/img/Update.R01.U01c.png)

* Während der Aktualisierung des Empfängers erscheint folgende Meldung:

![Firmware-Version aktualisieren](/assets/img/Update.R01.png)

* Während der Aktualisierung des Senders (Type-C) erscheint folgende Meldung:

![Firmware-Version aktualisieren](/assets/img/Update.U01c.png)

* Am Ende der Aktualiserung startet sich der Empfänger neu und koppelt sich mit dem Sender neu.

![Koppeln abgeschlossen](/assets/img/Pairing5.jpg)

## Sender Type-A aktualisieren

* Schließen Sie den USB-A-Adapter an den Sender an und schalten Sie den Sender auf `Type-A` um. Schließen Sie den Sender an den USB-A-Port des Empfängers an:

![Sender auf PC umschalten](/assets/img/Pairing.USBA.png)

### Sich in der Web-Oberfläche anmelden

Die Aktualisierung wird über die Web-Oberfläche in einem beliebigen Web-Browser durchgeführt.

* Notieren Sie sich die `Infrastruktur-IP-Adresse`, die unten links auf der Startseite angezeigt wird.

![](/assets/img/QuattroPod_IP.png)

* Rufen Sie nun Ihren Web-Browser auf.

![](/assets/img/Google_Chrome.png)

* Klicken Sie mit der Maus in die Adressleiste des Browsers und geben Sie die `Infrastruktur-IP-Adresse` des QuattroPods ein.

![](/assets/img/IP-Address.png)

* Nachdem Sie die Eingabetaste gedrückt haben, sollte nun die Einstellungsoberfläche des QuattroPods erscheinen. Geben Sie das Kennwort ein. Standardmäßig lautet es `000000`. Wenn dieses Kennwort nicht akzeptiert wird, müssen die Sie die [Standardeinstellungen zurücksetzen](reset.md).

![](/assets/img/QuattroPod-Login.png)

### Firmware-Aktualisierung starten

* Klicken Sie auf `Admineinstellungen`:

![](/assets/img/quattropod.select.admin.png)

* Klicken Sie auf `Update`:

![](/assets/img/Admineinstellungen_Update.png)

* Um die Aktualisierung zu starten, setzen Sie ein Häkchen bei `U01-TypeA`, anschließend klicken Sie auf `Upgrade`.

![Firmware-Version aktualisieren](/assets/img/Update.U01a.png)

* Während der Aktualisierung des Senders (Type-A) blinkt der Sender grün und rot. Der Aktualisierungsvorgang dauert 2-3 Minuten. Am Ende der Aktualisierung leuchtet der Sender weiß:

![Koppeln abgeschlossen](/assets/img/type.a.ready.png)

!!! tip "Hinweis"
    
	Sollte der Sender nach der Firmware-Aktualisierung nicht mit dem Empfänger verbinden können, müssen sie neu [gekoppelt](pairing.md) werden.

### Software USB WiFi Cast aktualisieren

* Nach der Aktualisierung der Firmware steht ein Update der Software **USB WiFi Cast** zur Verfügung. Beim Anschließen des Senders im Type-A-Modus öffnet sich ein CD-Laufwerk. Unter macOS führen Sie die `USB WiFi Cast` .pkg-Datei aus. Unter Windows führen Sie die `USB Launcher` .exe-Datei als Administrator aus:

![](/assets/img/QSG-QP.USB.Launcher.runasadministrator.png)

* Nach der Installation der Software starten Sie den Computer neu.

## Firmware über Internet mit dem CMS installieren

!!! tip "Hinweis"

	Aktuell wird die Aktualisierung der Firmware mit dem CMS nur unter Type-C Modus unterstützt.
	
Mit dem CMS ([Central Management System](cms.md)) kann man die neueste Firmware vom Internet auf mehreren EZCast Pro II bzw. QuattroPod Geräten installieren.

* Wenn eine neue Firmware für den Empfänger bzw. für den Sender zur Verfügung steht, taucht die Meldung ![](/assets/img/CMS-firmware.available.png) neben dem Gerät auf:

![Die Firmware wird installiert](/assets/img/CMS-firmware.OTA.select.devices.png)

* Wählen Sie die gewünschten Geräte aus, anschließend klicken Sie auf die Schaltfläche `Remote` -> und wählen Sie die Funktion `Device firmware upgrade`.

![Die Firmware wird installiert](/assets/img/CMS-firmware.install.latest.firmware.png)

* Unter der Registerkarte `OTA`, klicken Sie einfach auf die Schaltfläche `Apply`, um die Aktualisierung durchzuführen:

![Die Firmware wird installiert](/assets/img/CMS-firmware.upgrade.OTA.png)

Die neue Firmware wird heruntergeladen und automatisch installiert. 

* Während der Aktualisierung des Senders (Type-C) erscheint folgende Meldung:

![Firmware-Version aktualisieren](/assets/img/Update.U01c.png)

* Während der Aktualisierung des Empfängers erscheint folgende Meldung:

![Firmware-Version aktualisieren](/assets/img/Update.R01.png)

!!! warning "Achtung"
    
	Unterbrechen Sie während des Updates nicht die Stromversorgung.

![](/assets/img/ProIIStick_Firmware_installing.png)

!!! tip "Hinweis"

     Sollten die Sender nach der Firmware-Aktualisierung nicht mit dem Empfänger verbinden können, müssen sie neu [gekoppelt](pairing.md) werden.


## Firmware ohne Internet mit dem CMS installieren

!!! tip "Hinweis"

	Aktuell wird die Aktualisierung der Firmware mit dem CMS nur unter Type-C Modus unterstützt.
	
Mit dem CMS ([Central Management System](cms.md)) ermöglicht es Ihnen auch, die neueste Firmware auf Geräten zu installieren, die nicht mit dem Internet verbunden sind. Bitte nutzen Sie die untenstehenden Links, um die Firmware für Ihre Geräte vorab herunterzuladen:

Geräte               | Herunterladen      |
------------------------- | ------------------------- | 
QuattroPod Standard-Empfänger (R01) | [Herunterladen](firmware-reinstall.md#R01_install_other_fw)
QuattroPod Standard-Sender (U01) | [Herunterladen](firmware-reinstall.md#U01-TypeC_install_other_fw)

* Wählen Sie die gewünschten Geräte aus, klicken Sie dann auf die Schaltfläche `Remote` und wählen Sie die Option `Device firmware upgrade`.

![](/assets/img/CMS-firmware.install.latest.firmware.png)

* Unter Registerkarte `FILE`, wählen Sie die Firmware-Datei aus, die Sie zuvor heruntergeladen haben:

![](/assets/img/CMS-firmware.upgrade.FILE.png)

* Klicken Sie auf die Schaltfläche `Apply`, um die Aktualisierung durchzuführen:

![](/assets/img/CMS-firmware.upgrade.FILE.apply.png)

* Während der Aktualisierung des Senders erscheint folgende Meldung:

![](/assets/img/Update.U01c.png)

* Während der Aktualisierung des Empfängers erscheint folgende Meldung:

!!! warning "Achtung"
    
	Unterbrechen Sie während des Updates nicht die Stromversorgung.

![](/assets/img/ProIIStick_Firmware_installing.png)

!!! tip "Hinweis"

     Sollten die Sender nach der Firmware-Aktualisierung nicht mit dem Empfänger verbinden können, müssen sie neu [gekoppelt](pairing.md) werden.