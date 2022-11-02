# Was ist Multicast?

Die Funktion Multicast erlaubt es Ihnen die Bildschirminhalte eines Gerätes mit Hilfe eines gekoppelten Senders auf mehrere Displays gleichzeitig zu übertragen. 

!!! hint "Umfangreiche Touch-Back-Unterstützung mit QuattroPod USB und Multicast"

    [![QuattroPod Touch-Back-Funktion][1]{: align=left }][2]
	
	Demonstration: Umfangreiche Touch-Back-Unterstützung mit QuattroPod USB und Multicast
	
	[Video ansehen][2]

  [1]: /assets/img/thumbnail.video.advancedtouch.png
  [2]: https://assets.stueber.de/videos/touchback.win-android.mp4
  
Mehrere Teilnehmer haben die Möglichkeit, per Knopfdruck ihre Bildschirminhalte auf mehrere Displays zu übertragen. Dabei kann nur ein Teilnehmer auf einmal diese Funktion ausführen.

!!! warning "Hinweis"
    
	Bitte beachten Sie, dass die Funktion Multicast weder mit dem QuattroPod USB-Sender unter Type-A noch mit dem [QuattroPod Lite](/lite/intro) unterstützt wird. Jeder QuattroPod Empfänger, der über Multicast betrieben werden soll, muss entsprechend konfiguriert werden.
	
![](/assets/img/Multicast.png)

## Voraussetzungen

* Unterstützte Geräte: QuattroPod USB unter der Funktion Type-C oder Mobile, QuattroPod Standard/Deluxe, oder QuattroPod Mini.

* Sie benötigen einen WLAN Access Point.

* Ihr Router muss die `QuattroPod Sender / Empfänger` [Broadcast-Pakete](/ports.md) annehmen.

* Alle QuattroPod-Empfänger müssen sich im gleichen Netzwerk befinden.

![](/assets/img/Broadcast_Pakete.png) 

!!! tip "Hinweis"
    
	Um eine bessere Leistung von Multicast zu erreichen, verbinden Sie den QuattroPod-Empfänger mit dem [Router per LAN-Kabel](internet.md).

## Firmware-Version prüfen

* Für eine optimale Leistung und Stabilität des Systems, stellen Sie bitte sicher, dass die [Gerätefirmware](firmware-upgrade.md) auf dem neuesten Stand ist.

![Stellen Sie sicher, dass die Gerätefirmware auf dem neuesten Stand ist](/assets/img/quattropod.landingpage.fw.png)

## Konfigurationsschutz aktivieren {#config.restore}

Wenn Sie die Funktion Multicast aktivieren, stellt der QuattroPod folgende Einstellungen automatisch ein:

**Admineinstellungen**

* [AirPlay](airplay.md): `AUS`
* [AirPlay PIN code](airplay.md): `AUS`
* [Miracast Support](miracast.md): `AUS`
* [Miracast PIN](miracast.md): `AUS`
* [Google Cast](googlecast.md): `AUS`
* [Antrag automatisch genehmigen](adv.settings.md#Host-Control): `EIN`
* [Bildschirm teilen](adv.settings.md#Host-Control): `AUS`

Damit Ihre vorherigen Einstellungen beim Deaktivieren von Multicast wiederhergestellt werden, aktivieren Sie den Konfigurationschutz:

![](/assets/img/quattropod.select.admin.png)

* Klicken Sie neun Mal hinereinander auf dem Text `Admineinstellungen`:

![](/assets/img/click.adminsettings.png)

* Klicken Sie auf die Schaltfläche `Zurück`, um ins Hauptmenü zurückzukehren:

![](/assets/img/admin.back.png)

* Wählen Sie anschließend den Menüpunkt `Developer Options`:

![](/assets/img/qp.select.developermode.png)

* Aktivieren Sie die Funktion `Multicast Configuration Recover`:

![](/assets/img/multicast.config.recover.png)

## Multicast mit Web-Oberfläche einstellen

!!! tip "Hinweis"
    
	Wenn Sie die Funktion Multicast zum ersten Mal aktivieren, vergewissern Sie sich zunächst den [Konfigurationsschutz](#config.restore) zu aktivieren.
	
Mit der Web-Oberfläche kann man die Funktion Multicast auf einem QuattroPod einstellen. Anschließend muss man das Verfahren auf jedem QuattroPod-Gerät wiederholen, das in der selben Multicast-Gruppe verwendet werden soll.

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

* Aktivieren Sie die Option `Multicast`. Anschließend geben Sie einen Namen für die Multicast-Gruppe im Feld `Cast-Gruppe` ein. Schließlich geben Sie die `SSID` und das `Kennwort` eines WLANs ein z.B. das WLAN Ihrer Schule, über das die Multicast-Daten gesendet werden sollen:

![](/assets/img/multicast.websetting.on.png)

* Die Einstellungen werden erst nach einem Neustart wirksam:

![](/assets/img/restart.png)

* Nach dem Neustart startet der Empfänger im Multicast-Modus. Die angegebene Multicast-Gruppe und das verbundene WLAN werden oben angezeigt:

![](/assets/img/Multicast_activated.png)

### Sender unter Type-C koppeln

Nachdem Sie die Funktion Multicast auf Ihren QuattroPod-Empfängern eingestellt haben, muss einer Sender mit der selben Multicast-Gruppe gekoppelt werden:

* Schließen Sie den USB-A-Adapter an den Sender an und schalten Sie den Sender auf `Type-C` um. Schließen Sie den Sender an den USB-A-Port des Empfängers an:

![Sender auf PC umschalten](/assets/img/Pairing.USBC.png)

Die Meldung **"Pairing..."** erscheint automatisch auf der Startseite des QuattroPods. Während des Kopplungsvorgangs blinkt der Sender rot und der Empfänger blinkt weiß.

![Sender wird mit Empfänger gekoppelt](/assets/img/Pairing3.jpg)

Nach ein paar Sekunden erscheint die Meldung **"Pairing OK"** auf der Startseite. Der Empfänger und der Sender leuchten weiß:

![Koppeln abgeschlossen](/assets/img/Pairing5.jpg)

### Sender anschließen und Inhalte zeigen

* Ziehen Sie den USB-A-Adapter vom Sender ab und schalten Sie den Sender auf `Type-C` um. Schließen Sie den Sender an einen USB-C-Port Ihres Windows/macOS-Rechners an:
	 
	 ![](/assets/img/QSG-TypeC.Windows.png)

Ihr Bildschirm wird auf mehrere Monitore übertragen.

### Multicast deaktivieren

Um Ihre QuattroPod-Geräte wieder in den Standardmodus zurückzukehren, muss die Funktion Multicast deaktiviert werden:

* Wählen Sie den Menüpunkt `Admineinstellungen`:

![](/assets/img/quattropod.select.admin.png)

* Wählen Sie den Menüpunkt `Multicast`aus:

![](/assets/img/multicast_option.png)

* Schalten Sie die Funktion `Multicast` aus:

![](/assets/img/multicast.websetting.off.png)

* Die Einstellungen werden erst nach einem Neustart wirksam:

![](/assets/img/restart.png)

* Nach dem Neustart kehrt der QuattroPod in den normalen Betriebsmodus zurück. Die SSID und das Kennwort werden oben angezeigt:

![](/assets/img/quattropod.landing.normalmode.png)

!!! tip "Hinweis"
    
	Nachdem Sie Multicast deaktiviert haben, muss der Sender mit dem Empfänger neu [gekoppelt](pairing.md) werden.

## Multicast mit CMS einstellen

!!! tip "Hinweis"
    
	Wenn Sie die Funktion Multicast zum ersten Mal aktivieren, vergewissern Sie sich zunächst den [Konfigurationsschutz](#config.restore) zu aktivieren.
	
Mit dem CMS ([Central Management System](cms.md)) kann man Multicast auf mehreren QuattroPod-Geräten gleichzeitig einstellen.

* Wählen Sie alle QuattroPod-Empfänger aus, die eingestellt werden sollen:

![](/assets/img/multicast.select.all.png)

* Klicken Sie auf die Schaltfläche `Device` -> und wählen Sie die Funktion `Multicast setup` aus.

![](/assets/img/multicast.select.multicastsetup.png)

### Multicast aktivieren

* Schalten Sie die Funktion `Multicast` ein:

![](/assets/img/multicast.enable.multicastsetup.png)

* Geben Sie einen Namen für die Multicast-Gruppe im Feld `Group ID` ein. Schließlich geben Sie die `SSID` und das `Kennwort` eines WLANs ein z.B. das WLAN Ihrer Schule, über das die Multicast-Daten gesendet werden sollen. Zum Übernehmen der Einstellungen klicken Sie auf `Apply`:

![](/assets/img/multicast.settings.png)

* Die Einstellungen werden erst nach einem Neustart wirksam:

![](/assets/img/multicast.reboot.png)

* Nach dem Neustart startet der Empfänger im Multicast-Modus. Die angegebene Multicast-Gruppe und das verbundene WLAN werden oben angezeigt:

![](/assets/img/Multicast_activated.png)

### Sender unter Type-C koppeln

Nachdem Sie die Funktion Multicast auf Ihren QuattroPod-Empfängern eingestellt haben, muss einer Sender mit der selben Multicast-Gruppe gekoppelt werden:

* Schließen Sie den USB-A-Adapter an den Sender an und schalten Sie den Sender auf `Type-C` um. Schließen Sie den Sender an den USB-A-Port des Empfängers an:

![Sender auf PC umschalten](/assets/img/Pairing.USBC.png)

Die Meldung **"Pairing..."** erscheint automatisch auf der Startseite des QuattroPods. Während des Kopplungsvorgangs blinkt der Sender rot und der Empfänger blinkt weiß.

![Sender wird mit Empfänger gekoppelt](/assets/img/Pairing3.jpg)

Nach ein paar Sekunden erscheint die Meldung **"Pairing OK"** auf der Startseite. Der Empfänger und der Sender leuchten weiß:

![Koppeln abgeschlossen](/assets/img/Pairing5.jpg)

### Sender anschließen und Inhalte zeigen

* Ziehen Sie den USB-A-Adapter vom Sender ab und schalten Sie den Sender auf `Type-C` um. Schließen Sie den Sender an einen USB-C-Port Ihres Windows/macOS-Rechners an:
	 
	 ![](/assets/img/QSG-TypeC.Windows.png)

Ihr Bildschirm wird auf mehrere Monitore übertragen.

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

* Nach dem Neustart kehrt der QuattroPod in den normalen Betriebsmodus zurück. Die SSID und das Kennwort werden oben angezeigt:

![](/assets/img/quattropod.landing.normalmode.png)

!!! tip "Hinweis"
    
	Nachdem Sie Multicast deaktiviert haben, muss der Sender mit dem Empfänger neu [gekoppelt](pairing.md) werden.
