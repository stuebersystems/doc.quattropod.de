# Firmware aktualisieren

## Warum aktualisiert man die Firmware? 

Um von den neusten Funktionen des QuattroPods zu profitieren, können Sie das neuste Firmware-Update schnell und bequem über das Internet installieren. Bei der Installation einer neuen Firmware werden die bisherigen Einstellungen mitgenommen.

Dabei benötigen Sie einen [Internetzugang](internet.md) zum Internet bzw. mit Ihrem Router.  Wenn der QuattroPod mit Ihrem LAN bzw. mit Ihrem WLAN verbunden ist, wird eine von Ihrem Netzwerk vergebenen IP-Adressen mit der Bezeichnung `Infrustructure IP` auf dem Bildschirm angezeigt, wie unten abgebildet:

![](/assets/img/QuattroPod_IP.png)

!!! tip "Hinweis"

	Die Firmware des USB-Senders muss sowohl unter Type-A als auch unter Type-C Modus aktualisiert werden. Dies ist erforderlich, weil der Sender aus zwei separaten Chipsätzen besteht.


## Empfänger und Sender Type-C aktualisieren

* Schließen Sie den USB-A-Adapter an den Sender an und schalten Sie den Sender auf `Type-C` um. Schließen Sie den Sender an den USB-A-Port des Empfängers an:

![Sender auf PC umschalten](/assets/img/Pairing.USBC.jpg)


### In der Web-Oberfläche anmelden

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

* Um die Aktualisierung zu starten, setzen Sie ein Häkchen bei `Alle auswählen` ein, anschließend klicken Sie auf `Upgrade`.

![Firmware-Version aktualisieren](/assets/img/Update.R01.U01c.png)

* Während der Aktualisierung des Empfängers erscheint folgende Meldung:

![Firmware-Version aktualisieren](/assets/img/Update.R01.png)

* Während der Aktualisierung des Senders (Type-C) erscheint folgende Meldung:

![Firmware-Version aktualisieren](/assets/img/Update.U01c.png)

* Am Ende der Aktualiserung startet sich der Empfänger neu und koppelt sich mit dem Sender neu.

![Koppeln abgeschlossen](/assets/img/Pairing5.jpg)


## Sender Type-A aktualisieren

* Schließen Sie den USB-A-Adapter an den Sender an und schalten Sie den Sender auf `Type-A` um. Schließen Sie den Sender an den USB-A-Port des Empfängers an:

![Sender auf PC umschalten](/assets/img/Pairing.USBA.jpg)


### In der Web-Oberfläche anmelden

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

* Um die Aktualisierung zu starten, setzen Sie ein Häkchen bei `U01-TypeA` ein, anschließend klicken Sie auf `Upgrade`.

![Firmware-Version aktualisieren](/assets/img/Update.U01a.png)

* Während der Aktualisierung des Senders (Type-A) blinkt der Sender grün und rot. Der Aktualisierungsvorgang dauert 2-3 Minuten. Am Ende der Aktualiserung leuchtet der Sender weiß:

![Koppeln abgeschlossen](/assets/img/type.a.ready.png)

!!! tip "Hinweis"
    
	Sollten der Sender nach der Firmware-Aktualisierung nicht mit dem Empfänger verbinden können, müssen sie neu [gekoppelt](pairing.md) werden.


