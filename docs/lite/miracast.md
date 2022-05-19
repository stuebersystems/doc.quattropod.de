# Über Miracast verbinden

Mit Miracast haben Sie die Möglichkeit, Windows-Geräte (Windows 8.1 oder höher) oder Android-Geräte (Android 4.4 oder höher) mit dem QuattroPod ohne Hardware-Sender zu präsentieren. Der QuattroPod Lite unterstützt die Bildschirmübertragung eines Gerätes über das Miracast-Protokoll, ohne einen Sender zu benötigen.

## Miracast mit QuattroPod aktivieren

Aktivieren Sie die Funktion `Miracast Support` unter `Admineinstellungen` über die [Erweiterte Einstellungen](adv.settings.md#Miracast). Das Aktivieren von Miracast wird nach einem Neustart des Empfängers wirksam:

![](/assets/img/Miracast.png)

## Miracast auf Windows

Um Miracast mit dem QuattroPod zu verbinden, stellen Sie sicher, dass der Empfänger eingeschalten ist und die Startseite auf dem Bildschirm angezeigt ist.

![QuattroPod](/assets/img/quattropod.lite.landingpage.png)

Drücken Sie die Tastenkombination `[Windows]` + `[K]`, um das Dialogfenster `VERBINDEN` aufzurufen. Wählen Sie den QuattroPod aus:

![QuattroPod auswählen](/assets/img/QP-Windows_Miracast_Select_Device.png)

Der Aufbau der Miracast-Verbindung dauert 5 bis 10 Sekunden. Es wird dann `Verbunden` angezeigt:

![Miracast-Verbindung wird hergestellt](/assets/img/QP-Windows_Miracast_connected.png)

Eine zusätzliche Anzeige taucht in der Systemsteuerung auf. Anzeige-Einstellungen z.B. Auslösung und Skalierung können Sie anpassen, wie gewünscht.

![Miracast-Anzeige in der Systemsteuerung](/assets/img/Miracast_Display.jpg)

Um die Miracast-Anzeige zu trennen, rufen Sie das Dialogfenster erneut `VERBINDEN` auf, indem Sie die Tastenkombination `[Windows]` + `[K]` drücken und klicken Sie auf `Trennen`:

![Drahtlose Anzeige trennen](/assets/img/QP-Windows_Miracast_Disconnect.png)

## Miracast auf Android

Um Miracast mit dem QuattroPod zu verbinden, stellen Sie sicher, dass der Empfänger eingeschalten ist und die Startseite auf dem Bildschirm angezeigt ist.

![QuattroPod Startseite](/assets/img/quattropod.landingpage.direct.png)

Auf Ihrem Android-Gerät streichen Sie vom unteren Bildschirmrand nach oben, um das **Kontrollzentrum** aufzurufen und wählen Sie die Anwendung zur Bildschirmübertragung. Bei den meisten Geräten heißt es `Drahtlosprojektion`, `Smart View` oder auch `Screen Mirroring`. Wählen Sie anschließend Ihr QuattroPod Gerät aus. Um die Bildschirmübertragung zum beenden, wählen Sie `Trennen` in selben Bereich.

![Screen Mirroring](/assets/img/miracast.android.png)

## P2P vs. Infracast {#p2p_vs_infracast}

Es gibt zwei Arten von Miracast-Verbindungen, **P2P** und **Infracast**, die von Windows 10-Geräten aus möglich sind:

### P2P (Peer-to-Peer)

Der WiFi-Direct-Standard (Peer-to-Peer), der ein direktes Verbinden zweier WLAN-fähiger Geräte ohne zwischengeschalteten Access Point (AP) gestattet. Es gelten die folgenden Eigenschaften:

* Wird ab Windows 8.1 oder höher unterstützt.
* Keine WLAN-Infrastruktur erfolderlich.
* Maximalabstand von 30 Meter zwischen dem QuattroPod und dem Endbenutzer muss berücksichtigt werden.

Es ist möglich während der Bildschirmübertragung, mithilfe des Windows Task-Managers festzustellen, ob ein PC über P2P verbunden ist: 

* Öffnen Sie den Task-Manager und wählen Sie die Registerkarte `Leistung`. Wenn P2P in Verwendung ist, wird die SSID bzw. der Gerätename des QuattroPods Gerätes unter einem zusätzlichen Netzwerkadapter **Wi-Fi Direct** angezeigt und wird mit dem Präfix `DIRECT-` ergänzt:

![](/assets/img/D10.BF8E0C84.NGO-mode.Space-in-SSID.png)

### Infracast (Miracast über Infrastruktur)

Die Daten der Bildschirmübertragung werden über ein lokales Netzwerk anstatt über eine P2P-Verbindung gesendet. Weitere Informationen sind im [Microsoft-Artikel](https://docs.microsoft.com/de-de/surface-hub/miracast-over-infrastructure) zu finden.

Eine Miracast-Verbindung mit dem QuattroPod über Infrastruktur wird hergestellt, sofern folgende Voraussetzungen erfüllt sind:

* Wird ab Windows 10 Version 1703 und höher unterstützt.
* Die SSID bzw. der Gerätename des QuattroPods darf kein Leerzeichen enthalten:
    * RICHTIG: `Raum_001`
    * FALSCH: `Raum 001`
* Es werden auch Windows-Geräte über LAN-Kabel unterstützt.
* Es wird kein PIN bzw. kein Sicherheitscode unterstützt.
* Das Windows-Gerät und der QuattroPod müssen sich im gleichen Netzwerk befinden.
* Maximalabstand von 30 Meter zwischen dem QuattroPod und dem AccessPoint muss berücksichtigt werden.
	
Für den Endbenutzer ist der Prozess zur Initiierung einer Miracast-P2P oder Infracast-Verbindung gleich. Man drückt die Tastenkombination `[Windows]` + `[K]`, um das Dialogfenster `VERBINDEN` aufzurufen, dann wählt man den Empfänger aus der Liste der verfügbaren Geräte aus. 

Während der Bildschirmübertragung ist es mithilfe des Windows Task-Managers möglich festzustellen, ob ein PC über Infracast verbunden ist: 

* Öffnen Sie den Task-Manager und wählen Sie die Registerkarte `Leistung`.

Wenn Infracast in Verwendung ist, wird nur der bisherige Netzwerkadapter mit Angaben zu Ihrer Infrastruktur angezeigt:

![](/assets/img/D10_BF8E0C84.NGO-mode.No-Space-in-SSID.png)

