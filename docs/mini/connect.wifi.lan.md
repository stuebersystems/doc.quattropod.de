# Mit WLAN/LAN verbinden

Sie haben die Möglichkeit den QuattroPod mit Ihrer Netzwerkinfrastruktur entweder drahtlos per WLAN oder per LAN-Kabel zu verbinden.

## Warum soll man den QuattroPod mit WLAN/LAN verbinden?

Es gibt mehrere Gründe, warum Sie den QuattroPod mit Ihrer Netzwerkinfrastruktur verbinden sollen:

* Sie sind mit dem QuattroPod per [Apple AirPlay](airplay.md), [Chromecast](googlecast.md) oder die [Android App](quickstart.md#b-die-quattropod-app-unter-android) verbunden und möchten **Inhalte vom Internet** präsentieren.

* Sie möchten den QuattroPod auf die **neueste Firmware-Version** [aktualisieren](firmware-upgrade.md).

* Sie möchten per **Fernzugriff** auf die Funktion [Erweiterte Einstellungen](adv.settings.md) zugreifen, um den QuattroPod zu verwalten.
  
* **Integriertes Netzwerk**: Wenn alle Ihre Endgeräte und QuattroPod-Geräte im gleichen Netzwerk sind, entfällt die Notwendigkeit, jedes Mal zur SSID des QuattroPods zu wechseln, um ein Mobilgerät in unterschiedlichen Räumen zu übertragen.

## Mit WLAN verbinden {#wifi}

!!! tip "Bitte beachten"
    
	Der QuattroPod unterstützt nur das 5Ghz WLAN Frequenzband. Außerdem empfehlen wir, den QuattroPod nicht mit einer Dual-Band 2,4Ghz/5Ghz SSID zu verbinden, sondern mit einer dedizierten SSID, die auf die 5Ghz-Band eingeschränkt ist.

### Voraussetzungen

Bevor Sie den QuattroPod mit Ihrem WLAN verbinden, prüfen Sie bitte die empfohlenen Voraussetzungen:

* **Access Point unterstützt** WLAN-Standard **802.11ac**.
* **Nicht mit einer Dual-Band 2,4Ghz/5Ghz SSID verbinden**, sondern mit einer dedizierten SSID, die auf den [5GHz-Bereich](https://en.wikipedia.org/wiki/List_of_WLAN_channels#5_GHz_(802.11a/h/j/n/ac/ax)) (20Mhz-Kanäle 36,40,44,48) eingeschränkt ist. Benutzen Sie bitte nicht [DFS-Kanäle](https://en.wikipedia.org/wiki/Dynamic_frequency_selection), um Abbrüche durch plötzlichen Kanalwechsel während der Bildschirmübertragung zu vermeiden.
* Eine **dedizierte SSID für den QuattroPod** z.B. `QuattroPod_5Ghz` auf **Kanal 48** und im gleichen Netzwerk eine **andere SSID für die Benutzer** bzw. die Endgeräte z.B. `Benutzer_5Ghz` auf **Kanal 40** anlegen, damit die verfügbare WLAN-Kanalbandbreite für den QuattroPod mit anderen Clients nicht geteilt werden muss. 
* Max. 30 Meter **Abstand** vom **QuattroPod zum Access Point** sowie vom **QuattroPod zu den Endgeräten**. Beim Einrichten bitte die [Signalstärke](wifi.environment.md) prüfen. Zwischen -40 dBm und -50 dBm ist optimal.
* **Access Point liegt im selben Raum** wie der QuattroPod. Dies ist für das 5 GHz-Frequenzband besonders wichtig.
* Eine sogenannte **Sichtlinie** vom QuattroPod zum Access Point und zu den Endgeräten mit möglichst wenigen Hindernissen. **Vermeiden Sie Gegenstände direkt neben dem QuattroPod**, die WLAN-Signale schlucken bzw. reflektieren, beispielsweise: Wände, Metallflächen, reflektierende Flächen und andere elektronische Geräte, etc.

![](/assets/img/setup.wifi.box.png)

Wir empfehlen die Verwendung eines WLAN-Analyzers, um Ihre  [WLAN-Umgebung zu scannen](wifi.environment.md) und eine saubere Frequenznutzung fürs kabellose Präsentieren zu planen.

### Erweiterte Einstellungen öffnen

* Verbinden Sie Ihr Endgerät mit der SSID des QuattroPods. Die Zugangsdaten werden oben auf der Startseite angezeigt:

![](/assets/img/quattropod.ssid.direct.connect.png)

* In die Adressleiste eines Webbrowsers geben Sie die IP-Adresse des QuattroPods mit der Bezeichnung `Direct Link IP` **192.168.168.1** ein. Die Einstellungsoberfläche des QuattroPods erscheint:

![](/assets/img/quattropod_directIP.connect.png)

### Sich als Admin anmelden

* Geben Sie das Admin-Kennwort ein und klicken Sie auf `OK`, um sich anzumelden. Standardmäßig lautet das Kennwort `000000`. Wenn dieses Kennwort nicht akzeptiert wird setzen Sie das Gerät per [Reset-Schalter](reset.md#hardreset) zurück.

![](/assets/img/QuattroPod-Login.png)

### Networkeinstellungen auswählen

* Aus dem Menü oben links wählen Sie `Networkeinstellungen`.

![](/assets/img/quattropod.select.network.png)

* Wählen den Punkt `Mit 5GHz WLAN-Router/AP verbinden` aus.

![](/assets/img/quattropod.select.connect5ghz.png)

* Verbinden Sie den QuattroPod mit Ihrem WLAN-Router.

![](/assets/img/Wifi_Internet.png)

Wenn den QuattroPod mit Ihrem Netzwerk bzw. Ihrem Router verbunden ist, wird eine von Ihrem Netzwerk vergebenen IP-Adressen mit der Bezeichnung `Infrastructure IP` auf dem Bildschirm angezeigt, wie unten abgebildet:

![](/assets/img/ProDongleII_connected_to_router.png)

!!! info "Hinweis"

    Eine Miracast-Verbindung mit dem QuattroPod wird als zusätzliche WLAN-Verbindung nur zur Übertragung des Bildschirms ausgebaut. Für die Internetinhalte verwendet das Endgerät die bisherige bzw. die zuletzt verbundene WLAN/LAN Internetverbindung oder es nutzt den mobilen Datenzugang eines Providers. Weitere Informationen zu Miracast [finden Sie hier](miracast.md).

## Mit LAN verbinden {#ethernet} {#ethernet}

Schließen Sie dazu ein Netzwerkkabel in den `ETHERNET` Anschluss an der Rückseite des QuattroPods an und verbinden Sie das Kabel mit Ihrem Netzwerk bzw. mit Ihrem Router.

![](/assets/img/QuattroPod_ports.png)

!!! tip "Bitte beachten"
    
	Wenn ein LAN-Kabel an dem QuattroPod angeschlossen ist, wird der Internetzugang per WLAN automatisch deaktiviert.

Wenn den QuattroPod mit Ihrem Netzwerk bzw. Ihrem Router verbunden ist, wird eine von Ihrem Netzwerk vergebenen IP-Adressen mit der Bezeichnung `Infrustructure IP` auf dem Bildschirm angezeigt, wie unten abgebildet:

![](/assets/img/QuattroPod_IP.png)

!!! info "Hinweis"

    Eine Miracast-Verbindung mit dem QuattroPod wird als zusätzliche WLAN-Verbindung nur zur Übertragung des Bildschirms ausgebaut. Für die Internetinhalte verwendet das Endgerät die bisherige bzw. die zuletzt verbundene WLAN/LAN Internetverbindung oder es nutzt den mobilen Datenzugang eines Providers. Weitere Informationen zu Miracast [finden Sie hier](miracast.md).
	
## Problembehandlung

### Internet-Router-Signalstärke

Der QuattroPod hat eine Funkreichweite (Sichtlinie) von bis zu 30m. Eine geringe Signalanzeige bezieht sich auf eine schlechte Signalstärke zwischen dem QuattroPod und Ihrem Router bzw. Ihrem Access-Point. Dies kann zu einer abgehackten Wiedergabe von Videos und Inhalten führen, wenn die Inhalte vom Internet abhängig sind oder wenn Ihre Mobilgeräte mit dem QuattroPod über Ihre Infrastruktur verbinden.

Dies kann verschiedene Ursachen und somit verschiedene Lösungen haben:

**1. Problem:** Der Abstand zwischen dem QuattroPod und dem Router bzw. Wireless-Access-Point ist zu groß.

Lösung: Versuchen Sie den Abstand zu reduzieren oder installieren Sie einen zusätzlichen Wireless-Access-Point.

**2. Problem:** Es liegen Wände oder andere Gegenstände zwischen dem QuattroPod und dem Router bzw. dem Wireless-Access-Point, welche die Signalstärke verschlechtern.

Lösung: Stellen Sie sicher, dass der QuattroPod keine Hindernisse zum Router bzw. zum Access-Point hat. Wenn notwendig, installieren Sie einen zusätzlichen Access-Point.

![](/assets/img/QP.Internet.Signal.png)