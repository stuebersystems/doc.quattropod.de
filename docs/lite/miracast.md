# Über Miracast verbinden

Mit Miracast haben Sie die Möglichkeit, Windows-Geräte (Windows 8.1 oder höher) oder Android-Geräte (Android 4.4 oder höher) mit dem QuattroPod ohne Hardware-Sender zu präsentieren.

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

![QuattroPod](/assets/img/quattropod.lite.landingpage.png)

Auf Ihrem Android-Gerät streichen Sie vom unteren Bildschirmrand nach oben, um das **Kontrollzentrum** aufzurufen und wählen Sie die Anwendung zur Bildschirmübertragung. Bei den meisten Geräten heißt es `Drahtlosprojektion`, `Smart View` oder auch `Screen Mirroring`. Wählen Sie anschließend Ihr QuattroPod Gerät aus. Um die Bildschirmübertragung zum beenden, wählen Sie `Trennen` in selben Bereich.

![Screen Mirroring](/assets/img/miracast.android.png)

## Weitere Informationen zur Funktion Miracast Support (NGO-Modus) {#ngo-mode}

Mit der Firmware [1.14366.90](whatsnew.md#20220302-11436690) wurde die Unterstützung fürs Streamingprotokoll Miracast, auch bekannt als NGO-Modus (Negotiated Group Owner in englischer Sprache), eingeführt, um eine Bildschirmübertragung nativ, also ohne Sender bzw. zusätzliche App/Software, von einem Miracast-Gerät auf den großen Bildschirm/Beamer zu ermöglichen. In diesem Modus gelten die folgenden Eigenschaften:

* Mit dem QuattroPod Lite wird die Bildschirmübertragung von nur einem Gerät unterstützt. Gleichzeitiges Senden (Splitscreen mit bis zu 4 Geräten) wird mit QuattroPod [USB](https://www.quattropod.de/usb.php), [Mini](https://www.quattropod.de/mini.php), [Standard](https://www.quattropod.de/standard.php), [Deluxe](https://www.quattropod.de/deluxe.php) und [M1](https://www.quattropod.de/m1.php) unterstützt.
* [Infracast](https://docs.microsoft.com/de-de/surface-hub/miracast-over-infrastructure) wird nicht unterstützt.
* Während der Bildschirmübertragung eines Miracast-Gerätes werden alle Netzwerkschnittstellen belegt, kein weiteres Endgerät kann gespiegelt werden und die folgenden Funktionen **stehen nicht zur Verfügung**:
	* [CMS (Central Management System)](cms.md).
    * [AirView](airview.md).
    * [Konferenzsteuerung](conference-control.md).
    * Die Web-Oberfläche der [Einstellungen](adv.settings.md).

## P2P (Peer-to-Peer)

Der QuattroPod-Lite verwendet den WiFi-Direct-Standard P2P (Peer-to-Peer), der ein direktes Verbinden zweier WLAN-fähiger Geräte ohne zwischengeschalteten Access Point (AP) gestattet. Es gelten die folgenden Eigenschaften:

* Wird ab Windows 8.1 oder höher unterstützt.
* Keine WLAN-Infrastruktur erfolderlich.
* Maximalabstand von 30 Meter zwischen dem QuattroPod und dem Endbenutzer muss berücksichtigt werden.

Es ist möglich während der Bildschirmübertragung, mithilfe des Windows Task-Managers festzustellen, ob ein PC über P2P verbunden ist: 

* Öffnen Sie den Task-Manager und wählen Sie die Registerkarte `Leistung`. Wenn P2P in Verwendung ist, wird eine SSID unter einem zusätzlichen Netzwerkadapter **Wi-Fi Direct** angezeigt und wird mit dem Präfix `DIRECT-` ergänzt:

![](/assets/img/ngo_quattropod_lite.png)

## Problembehandlung

### Es konnte keine Verbindung hergestellt werden

Wenn Miracast-Einstellungen bzw. der Gerätename des EZCast Pro Gerätes geändert werden, kann es dazu führen, dass Miracast sich nicht verbinden lässt. Um das Problem zu lösen, löschen Sie bitte den Eintrag der Miracast-Verbindung in den Windows-Einstellungen, anschließend verbinden Sie Ihr Endgerät erneut:

![](/assets/img/Miracast.failed-to-connect.png)

#### Windows 11 Miracast-Eintrag löschen

* Im Startmenü öffenen Sie die `Einstellungen`: 

![](/assets/img/Miracast.win11.delete.record1.png)

* Unter `Bluetooth und Geräte` klicken Sie auf `Geräte`:

![](/assets/img/Miracast.win11.delete.record2.png)

* Scrollen Sie runter bis auf `Drahtlose Bildschirme und Docking-Stationen`. Neben Ihrem EZCast Pro Gerät wählen Sie `Gerät entfernen` aus:

![](/assets/img/Miracast.win11.delete.record3.png)

#### Windows 10 Miracast-Eintrag löschen

* Im Startmenü öffenen Sie die `Einstellungen` und klicken Sie auf `Geräte`: 

![](/assets/img/Miracast.win10.delete.record1.png)

* Unter `Bluetooth und Geräte` scrollen Sie runter bis auf `Drahtlose Bildschirme und Docking-Stationen`. Neben Ihrem EZCast Pro Gerät wählen Sie `Gerät entfernen` aus:

![](/assets/img/Miracast.win10.delete.record2.png)