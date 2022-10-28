# Touch-Back-Funktion

Die Touch-Back-Funktion des QuattroPods erlaubt Ihnen Gesten mit bis zu 10-Fingern eines Multitouch-fähigen Bildschirms drahtlos an Ihr Endgerät zurückzusenden.

Wenn auf einen anderen Teilnehmer gewechselt wird, steht ihm auch die Touch-Back-Funktionalität zur Verfügung. Dies ermöglicht die Interaktivität und Kreativität von mehreren Teilnehmern an einem Bildschirm.

Die Touch-Back Funktion wird nur bei der 1:1- Übertragung eines Bildschirms unterstützt.

!!! hint "Umfangreiche Touch-Back-Unterstützung mit QuattroPod USB und Multicast"

    [![QuattroPod Touch-Back-Funktion][1]{: align=left }][2]
	
	Demonstration: Umfangreiche Touch-Back-Unterstützung mit QuattroPod USB und Multicast
	
	[Video ansehen][2]

  [1]: /assets/img/thumbnail.video.advancedtouch.png
  [2]: https://assets.stueber.de/videos/touchback.win-android.mp4
  
!!! hint "Touch-Back-Funktion mit QuattroPod"

    [![QuattroPod Touch-Back-Funktion][3]{: align=left }][4]
	
	Anleitung: Touch-Back-Funktion mit QuattroPod.
	
	[Zum YouTube-Video][4]

  [1]: /assets/img/thumbnail.video.advancedtouch.png
  [2]: https://assets.stueber.de/videos/touchback.win-android.mp4
  [3]: /assets/img/thumbnail.video.touch.png
  [4]: https://youtu.be/Qky7XQR1rrE
  

## Voraussetzungen

* Das neueste [Firmwareupdate](firmware-upgrade.md) für den QuattroPod.

* Für Windows Geräte mit dem Sender ist Windows 7 / 8 / 10 erforderlich. Für die Verwendung ohne Sender ist ein [Miracast-fähiger Windows 10/11 PC](#touchviamiracast) erforderlich.

* Für macOS Geräte mit dem Sender ist macOS 10.14.6 oder höher erforderlich. Es werden keine Multitouch-Gesten unterstützt.

* Ein Android Gerät, das die Videoübertragung per USB-C-Anschluss [DP Alt Mode](https://en.everybodywiki.com/List_of_devices_with_video_output_over_USB-C) unterstützen.


## Einrichtung

* Schließen Sie das USB-Kabel Ihres touchfähigen Bildschirms an den USB-Anschluss des Empfängers an.

![](/assets/img/RX_Touch-USB-cable.png)

* Wenn der Empfänger die Touch-Funktionalität Ihres Bildschirms erfolgreich entdeckt hat, erscheint das Maus-Symbol oben rechts auf der Startseite.

![Die Touch-Back-Funktion ist aktiviert](/assets/img/quattropod.touch.icon.png)

* Bei einigen Displays müssen Sie möglicherweise die Funktion `Reverse Control` aktivieren:

![](/assets/img/reverse.control.png)

## Touch-Back unter Windows/macOS im Type-C Sendermodus
  
!!! tip "Hinweis"

     Stellen Sie sicher, dass Ihr Gerät die Videoübertragung per USB-C-Anschluss [DP Alt Mode](https://en.everybodywiki.com/List_of_devices_with_video_output_over_USB-C) unterstützt.
	 
* Ziehen Sie den USB-A-Adapter vom Sender ab und schalten Sie den Sender auf `Type-C` um. Schließen Sie den Sender an einen USB-C-Port Ihres Windows/macOS-Rechners an:
	 
	 ![](/assets/img/QSG-TypeC.Windows.png) 

* Wenn die Touch-Back-Funktion erfolgreich aktiviert wurde, erscheint die Meldung `"Hid Driver loading ..."` für einige Sekunden auf dem Bildschirm.

![Die Touch-Back-Funktion wurde erfolgreich freigeschaltet](/assets/img/Hid_Driver_loading.jpg)

* Die Touch-Gesten Ihres Displays werden an den Rechner zurückgesendet.

![Touch-Gesten werden an den Rechner zurückgesendet](/assets/img/Using.TouchBack.png)

* Unter Windows empfehlen wir die Aktivierung der Bildschirmtastatur an der Tastleiste. Die Tastatur steht dann an der Taskleiste zur Verfügung:

![](/assets/img/windows.activate.onscreen.keyboard.png)

![](/assets/img/windows.open.windows.onscreen.keyboard.png)

* Unter macOS aktivieren Sie die Bildschirmtastatur in den Systeneinstellungen unter `Tastatur`:

![](/assets/img/macOS.activate.onscreen.keyboard.png)

* Die Tastatur steht dann an der Taskleiste zur Verfügung:

![](/assets/img/macOS.open.onscreen.keyboard.png)


## Touch-Back unter Android im Type-C Sendermodus {#touchback_android}
	
!!! tip "Hinweis"

     Stellen Sie sicher, dass Ihr Gerät die Videoübertragung per USB-C-Anschluss [DP Alt Mode](https://en.everybodywiki.com/List_of_devices_with_video_output_over_USB-C) unterstützt.
	 
* Ziehen Sie den USB-A-Adapter vom Sender ab und schalten Sie den Sender auf `Type-C` um. Schließen Sie den Sender an den USB-C-Port Ihres Android Rechners an:

  ![](/assets/img/QSG-QP.USBC.Android.png) 
  
* Wenn die Touch-Back-Funktion erfolgreich aktiviert wurde, erscheint die Meldung `"Hid Driver loading ..."` für einige Sekunden auf dem Bildschirm.

![Die Touch-Back-Funktion wurde erfolgreich freigeschaltet](/assets/img/Hid_Driver_loading.jpg)

* Die Touch-Gesten Ihres Displays werden an Ihr Androi-Gerät zurückgesendet:

![Touch-Gesten werden an den Rechner zurückgesendet](/assets/img/Using.TouchBack.png)

## Touch-Back unter Windows mit Miracast {#touchviamiracast}

!!! tip "Hinweis"

     Mit der Firmware-Version 1.16163.38 und höher unterstützt der QuattroPod Touchback mit Miracast, auch im Englischen als **User Input Back Channel (UIBC)** bekannt. 
	 
* Auf einem Windows-Gerät drücken Sie die Tastenkombination `[Windows]` + `[K]`, um das Dialogfenster `VERBINDEN` aufzurufen. Wählen Sie Ihr QuattroPod Pro Gerät aus, auf das Sie übertragen möchten:

![](/assets/img/Windows_Miracast_Select_QP_Device.png)

* Setzen Sie ein Häkchen ein, um die Touchfunktionalität per Miracast zu aktivieren:

![](/assets/img/Windows_Miracast_connect.png)

* Die Touch-Gesten mit bis zu 6-Fingern Ihres Displays werden an den Rechner zurückgesendet.

![](/assets/img/Using.TouchBack.png)