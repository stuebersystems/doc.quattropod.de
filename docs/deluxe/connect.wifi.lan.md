# Mit WLAN/LAN verbinden

Sie haben die Möglichkeit den QuattroPod mit Ihrer Netzwerkinfrastruktur entweder drahtlos per WLAN oder per LAN-Kabel zu verbinden.

## Warum soll man den QuattroPod mit WLAN/LAN verbinden?

Es gibt mehrere Gründe, warum Sie den QuattroPod mit Ihrer Netzwerkinfrastruktur verbinden sollen:

* Sie sind mit dem QuattroPod per [Apple AirPlay](airplay.md), [Chromecast](googlecast.md) oder die [Android App](quickstart.md#b-die-quattropod-app-unter-android) verbunden und möchten Inhalte vom Internet präsentieren.

* Sie möchten den QuattroPod auf die neueste Firmware-Version [aktualisieren](firmware-upgrade.md).

* Sie möchten per Fernzugriff auf die Funktion [Erweiterte Einstellungen](adv.settings.md) zugreifen, um den QuattroPod zu verwalten.
  
* Integriertes Netzwerk: Wenn alle Ihre Endgeräte und QuattroPod-Geräte im gleichen Netzwerk sind, entfällt die Notwendigkeit, jedes Mal zur SSID des QuattroPods zu wechseln, um ein Mobilgerät in unterschiedlichen Räumen zu übertragen.

## QuattroPod mit WLAN verbinden

!!! tip "Bitte beachten"
    
	Der QuattroPod unterstützt nur die 5Ghz WLAN Frequenzband. Außerdem ist es empfohlen, den QuattroPod mit keiner Dual-Band 2,4Ghz/5Ghz SSID zu verbinden, sondern mit einer dedizierten SSID, die auf die 5Ghz-Band eingeschränkt ist.
	
### Erweiterte Einstellungen öffnen

* Verbinden Sie Ihr Endgerät mit der SSID des QuattroPods. Die Zugangsdaten werden oben auf der Startseite angezeigt:

![](/assets/img/quattropod.ssid.direct.connect.png)

* In die Adressleiste eines Webbrowsers geben Sie die IP-Adresse des QuattroPods mit der Bezeichnung `Direct Link IP` **192.168.168.1** ein. Die Einstellungsoberfläche des QuattroPods erscheint:

![](/assets/img/quattropod_directIP.connect.png)

### Sich als Admin anmelden

* Geben Sie das Admin-Kennwort ein und klicken Sie auf `OK`, um sich anzumelden. Standardmäßig lautet das Kennwort `000000`. Wenn dieses Kennwort nicht akzeptiert wird setzen Sie das Gerät per [Reset-Schalter](reset.md#hardreset) zurück.

![](/assets/img/QuattroPod-Login.png)

### Netzwerkeinstellungen auswählen

* Aus dem Menü oben links wählen Sie `Netzwerkmanagement`.

![](/assets/img/quattropod.select.network.png)

* Wählen den Punkt `Mit 5GHz WLAN-Router/AP verbinden` aus.

![](/assets/img/quattropod.select.connect5ghz.png)

* Verbinden Sie den QuattroPod mit Ihrem WLAN-Router.

![](/assets/img/Wifi_Internet.png)

Wenn der QuattroPod mit Ihrem WLAN verbunden ist, wird eine von Ihrem Netzwerk vergebenen IP-Adressen mit der Bezeichnung `Infrustructure IP` auf dem Bildschirm angezeigt, wie unten abgebildet:

![](/assets/img/QuattroPod_IP.png)

## QuattroPod mit LAN verbinden

Schließen Sie dazu ein Netzwerkkabel in den `ETHERNET` Anschluss an der Rückseite des QuattroPods an und verbinden Sie das Kabel mit Ihrem Netzwerk bzw. mit Ihrem Router.

![](/assets/img/QuattroPod_ports.png)

!!! tip "Bitte beachten"
    
	Wenn ein LAN-Kabel an der Box angeschlossen ist, wird der Internetzugang per WLAN automatisch deaktiviert.

Wenn der QuattroPod mit Ihrem WLAN verbunden ist, wird eine von Ihrem Netzwerk vergebenen IP-Adressen mit der Bezeichnung `Infrustructure IP` auf dem Bildschirm angezeigt, wie unten abgebildet:

![](/assets/img/QuattroPod_IP.png)

## Problembehandlung

### Internet-Router-Signalstärke

Der QuattroPod hat eine Funkreichweite (Sichtlinie) von bis zu 30m. Eine geringe Signalanzeige bezieht sich auf eine schlechte Signalstärke zwischen der Box und Ihrem Router bzw. Ihrem Access-Point. Dies kann zu einer abgehackten Wiedergabe von Videos und Inhalten führen, wenn die Inhalte vom Internet abhängig sind oder wenn Ihre Mobilgeräte mit dem Stick über Ihre Infrastruktur verbinden.

Dies kann verschiedene Ursachen und somit verschiedene Lösungen haben:

**1. Problem:** Der Abstand zwischen dem QuattroPod und dem Router bzw. Wireless-Access-Point ist zu groß.

Lösung: Versuchen Sie den Abstand zu reduzieren oder installieren Sie einen zusätzlichen Wireless-Access-Point.

**2. Problem:** Es liegen Wände oder andere Gegenstände zwischen dem QuattroPod und dem Router bzw. dem Wireless-Access-Point, welche die Signalstärke verschlechtern.

Lösung: Stellen Sie sicher, dass der QuattroPod keine Hindernisse zum Router bzw. zum Access-Point hat. Wenn notwendig, installieren Sie einen zusätzlichen Access-Point.

![](/assets/img/QP.Internet.Signal.png)