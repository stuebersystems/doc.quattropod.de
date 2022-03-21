# Sender koppeln

Der QuattroPod-Empfänger kann mit bis zu 32 Sendern gleichzeitig gekoppelt werden. Die Sender sind mit dem mitgelieferten Empfänger standardmäßig gekoppelt. Sie können jedoch zusätzliche Sender erwerben bzw. Sender mit einem anderen Empfänger verwenden. Es gibt zwei Möglichkeiten, einen Sender mit einem Empfänger zu koppeln:

* [Sender an den Empfänger anschließen](#rx_usbport)

Der Sender wird an den USB-Anschluss des Empfänger anschlossen.

* [Sender per USB-Stick koppeln](#usbstick)

Eine Kopplungsdatei wird heruntergeladen und per USB-Stick auf den Sender kopiert.

## Sender an den Empfänger anschließen {#rx_usbport}

Der Sender wird an den USB-Anschluss des Empfänger anschlossen und die Geräte koppeln sich automatisch. Manche finden diese Option am einfachsten, wenn der Empfänger leicht zu erreichen ist. Falls der Empfänger an der Decke montiert ist oder einfach schwer zu erreichen ist, koppeln Sie den [Sender per USB-Stick](#sender-per-usb-stick-koppeln).

* Schalten Sie den Sender auf `PC` um. 

![Sender auf PC umschalten](/assets/img/quattropod.mini.tx.pc.png)

* Schließen Sie den Sender an den USB-Anschluss des Empfängers an und schalten Sie den Empfänger ein.

![](/assets/img/quattropod.mini.tx.pairing.png)

Die Meldung **"Pairing..."** erscheint automatisch auf der Startseite des QuattroPods. Während des Koppelns blinkt der Sender rot und der Empfänger blinkt weiß.

![Sender wird mit Empfänger gekoppelt](/assets/img/Pairing3.jpg)

Nach ein paar Sekunden ist der Sender mit dem QuattroPod gekoppelt. Der Empfänger und der Sender leuchten weiß. 

![Koppeln abgeschlossen. Sender leuchtet weiß](/assets/img/quattropod.mini.tx.paired.jpg)

Dies wird mit **"Pairing OK"** auf der Startseite bestätigt.

![Koppeln abgeschlossen](/assets/img/Pairing5.jpg)

Der Sender kann nun mit entsprechenden Empfänger benutzt werden. Schalten Sie zum Schluss den Sender auf den gewünschten Modus um und schließen Sie den Sender an das gewünschte Endgerät an: 

* `Mobile` = Smartgeräte

* `PC` = Windows/macOS


## Sender per USB-Stick koppeln {#usbstick}

Ist der Empfänger außerhalb der Reichweite und benötigt einen großen Aufwand, um zu erreichen, können Sie eine Kopplungsdatei herunterzuladen und mit einem USB-Stick auf den Sender zu kopieren. 

* Formatieren Sie den Stick `FAT32`.

Es gibt zwei Möglichkeiten, die Kopplungsdatei auf dem USB-Stick abzuspeichern:

* [Kopplungsdatei per Web-Oberfläche herunterladen](#pairingfile_download_web)

* [Kopplungsdatei per Empfänger herunterladen](#pairingfile_download_rx)

### Kopplungsdatei per Web-Oberfläche herunterladen {#pairingfile_download_web}

* Laden Sie die Kopplungsdatei `pairingInfo.json` aus dem Menüpunkt `Gerätemanagement` der [Web-Oberfläche](adv.settings.md) herunter: 

![Kopplungsdatei herunterladen](/assets/img/Pairing7.png)

* Kopieren Sie anschließend die Datei auf einen USB-Stick. Sie müssen keine anderen Dateien löschen.

**WICHTIG:** Die Kopplungsdatei muss unbedingt an der **Wurzel des USB-Sticks** gespeichert werden. 

![Kopplungsdatei auf einen USB-Stick kopieren](/assets/img/Pairing8.png)

### Kopplungsdatei per Empfänger herunterladen {#pairingfile_download_rx}

* Schließen Sie den USB-Stick an den USB-Anschluss des Empfängers an und drücken Sie den Kopplungsknopf auf der Oberseite des Empfängers. Nach ein Paar Sekunden ist die Kopplungsdatei auf den USB-Stick kopiert und der Kopplungsknopf des Empfängers leuchtet weiß.

![Kopplungsdatei vom Empfänger auf USB-Stick kopieren](/assets/img/Pairing9.png)

### USB-Stick an den Sender anschließen

!!! tip "Hinweis"

     Dieser Schritt muss im selben Raum bzw. innerhalb Funkreichweite des Empfängers vorgenommen werden.

* Um die Kopplung per USB-Stick zu beginnen, schalten Sie den Sender auf `Mobile` um.

![Sender auf Mobile umschalten](/assets/img/quattropod.mini.tx.mobile.png)

* Schließen Sie das USB-Kabel des Senders mit einer USB-Stromversorgung (5V1A) an und stecken Sie den USB-Stick in den USB-Anschluss des Senders ein. Die Kopplung beginnt automatisch. 

![Sender blinkt rot](/assets/img/quattropod.mini.usb.pairing.png)

Der Sender blinkt rot, weiß, und grün mehrfach in Folge während des Koppelns. Nach ca. 30 Sekunden ist der Sender mit dem QuattroPod-Empfänger gekoppelt. Wenn díe Kopplung fertig ist, leuchtet  der Sender weiß.

![Kopplung abgeschlossen. Sender leuchtet weiß](/assets/img/quattropod.mini.usb.paired.png)

Der Sender kann nun mit entsprechenden Empfänger benutzt werden. Schalten Sie zum Schluss den Sender auf den gewünschten Modus um und schließen Sie den Sender an das gewünschte Endgerät an: 

* `Mobile` = Smartgeräte

* `PC` = Windows/macOS





