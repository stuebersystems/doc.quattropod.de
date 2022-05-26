# Über Miracast verbinden

Mit Miracast haben Sie die Möglichkeit, Windows-Geräte (Windows 8.1 oder höher) oder Android-Geräte (Android 4.4 oder höher) mit dem QuattroPod ohne Hardware-Sender zu präsentieren. Der QuattroPod ermöglicht es bis zu vier Geräte inkl. Geräte über das Miracast-Protokoll auf einem aufgeteilten Bildschirm gemeinsam zu übertragen, ohne einen Sender zu benötigen.

## Miracast mit QuattroPod aktivieren

Aktivieren Sie die Funktion `Miracast Support` unter `Admineinstellungen` über die [Erweiterte Einstellungen](adv.settings.md#Miracast). Das Aktivieren von Miracast wird nach einem Neustart des Empfängers wirksam:

![](/assets/img/Miracast.png)

Nach dem Neustart wird der Gerätename bzw. die auf der Startseite angezeigte SSID mit dem Präfix `DIRECT-` ergänzt. Dies gilt für die SSID des QuattroPods, die in Ihren WLAN-Einstellungen zu finden ist, sowie der angezeigte Gerätename unter den Streamingprotokollen AirView und Chromecast:

![](/assets/img/direct_prefix.png)

Der angezeigte Gerätename bei der Suche nach verfügbaren Geräten unter Miracast wird allerdings **nicht** mit dem Präfix ergänzt. Dies ist erforderlich, um alle Streamingprotokolle inkl. Miracast sowie die Hardware-Sender gemeinsam zu unterstützen:

![](/assets/img/QP-Windows_Miracast_Select_Device.png)

## Miracast auf Windows

Um Miracast mit dem QuattroPod zu verbinden, stellen Sie sicher, dass der Empfänger eingeschalten ist und die Startseite auf dem Bildschirm angezeigt ist.

![QuattroPod](/assets/img/quattropod.landingpage.direct.png)

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

## Weitere Informationen zur Funktion Miracast Support (AGO-Modus) {#ago-mode}

Mit der Firmware [1.14366.62](whatsnew.md#20220111-11436662) wurde die Unterstützung fürs Streamingprotokoll Miracast, auch bekannt als AGO-Modus (Autonomous Group Owner in englischer Sprache), eingeführt, um eine Bildschirmübertragung nativ, also ohne Sender bzw. zusätzliche App/Software, von bis zu 4 Geräten einschließlich Miracast-Geräten auf einem geteilten Bildschirm zu ermöglichen. In diesem Modus gelten die folgenden Eigenschaften:

* Der geteilte Bildschirm unterstützt alle Streamingprotokolle mit bis zu 4 Geräten einschließlich Miracast-Geräten. 
* Die SSID bzw. der Gerätename kann geändert werden, aber enthält immer vorne den Präfix "DIRECT-", beispielsweise `DIRECT-Raum_001`. 
* Das Kennwort kann nicht ausgeblendet werden. Um das Kennwort auszublenden, [deaktivieren](adv.settings.md#Miracast) Sie bitte zuerst die Funktion `Miracast Support`, dann stellen Sie das Ausblenden des Kennworts ein, anschließend [aktivieren](adv.settings.md#Miracast) Sie wieder die Funktion `Miracast Support`.
* [Infracast](https://docs.microsoft.com/de-de/surface-hub/miracast-over-infrastructure) wird nicht unterstützt.
* Das Kennwort kann nicht in diesem Modus geändert werden. Um das Kennwort zu ändern, [deaktivieren](adv.settings.md#Miracast) Sie bitte zuerst die Funktion `Miracast Support`, dann nehmen Sie die Änderung des Kennworts vor, anschließend [aktivieren](adv.settings.md#Miracast) Sie wieder die Funktion `Miracast Support`.
* Während der Bildschirmübertragung eines Miracast-Gerätes bleiben alle Netzwerkschnittstellen erreichbar und alle Funktionen stehen weiterhin zur Verfügung.

## P2P (Peer-to-Peer)

Der QuattroPod-M1 verwendet den WiFi-Direct-Standard P2P (Peer-to-Peer), der ein direktes Verbinden zweier WLAN-fähiger Geräte ohne zwischengeschalteten Access Point (AP) gestattet. Es gelten die folgenden Eigenschaften:

* Wird ab Windows 8.1 oder höher unterstützt.
* Keine WLAN-Infrastruktur erfolderlich.
* Maximalabstand von 30 Meter zwischen dem QuattroPod und dem Endbenutzer muss berücksichtigt werden.

Es ist möglich während der Bildschirmübertragung, mithilfe des Windows Task-Managers festzustellen, ob ein PC über P2P verbunden ist: 

* Öffnen Sie den Task-Manager und wählen Sie die Registerkarte `Leistung`. Wenn P2P in Verwendung ist, wird die SSID bzw. der Gerätename des QuattroPods unter einem zusätzlichen Netzwerkadapter **Wi-Fi Direct** angezeigt und wird mit dem Präfix `DIRECT-` ergänzt:

![](/assets/img/p2p_direct_quattropod.png)