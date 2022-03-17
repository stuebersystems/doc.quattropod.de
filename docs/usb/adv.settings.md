# Erweiterte Einstellungen

Mit der Funktion `Erweiterte Einstellungen` können Sie die Firmware aktualisieren und viele Einstellungen des QuattroPods bequem per Fernzugriff anpassen.

## Erweiterte Einstellungen öffnen

* Um die Web-Oberfläche zu erreichen, verbinden Sie Ihr Endgerät mit der SSID des QuattroPods. Die Zugangsdaten werden oben auf dem Bildschirm angezeigt:

![](/assets/img/quattropod.ssid.connect.png)

* In die Adressleiste eines Webbrowsers geben Sie die `Direct Link IP` des QuattroPods ein. Die Einstellungsoberfläche des QuattroPods erscheint:

![](/assets/img/quattropod_directIP.connect.png)

### Sich als Admin anmelden

* Geben Sie das Admin-Kennwort ein und klicken Sie auf `OK`, um sich anzumelden. Standardmäßig lautet das Kennwort `000000`. Wenn dieses Kennwort nicht akzeptiert wird setzen Sie das Gerät per [Reset-Schalter](reset.md#hardreset) zurück.

![](/assets/img/QuattroPod-Login.png)

Die folgenden Funktionen stehen zur Verfügung:

![](/assets/img/Mainmenu.png)

## Android APK herunterladen {#Android_APK_herunterladen}

Nutzen Sie diese Option, um die Android-APK-Datei vom Empfänger herunterzuladen und die QuattroPod-App auf einem Android-Gerät "per Hand" zu installieren. Bei der Ausführung einer APK-Datei könnte eine Genehmigung aus Sicherheitsgründen in z.B. `Einstellungen | Sicherheit` benötigt werden.

![Android APK herunterladen](/assets/img/Android_download.png)

## Netzwerkmanagement {#Netzwerkmanagement}

![](/assets/img/Network_Management.png)

### Mit 5Ghz WLAN-Router/AP verbinden {#Wireless_Access_Point}

Wenn Sie den QuattroPod lieber per Wireless Access Point verbinden, um auf das Internet zuzugreifen, finden Sie die Möglichkeit dazu hier.

![](/assets/img/Wifi_Internet.png)

### WLAN merken

Legt fest, ob der QuattroPod mit dem [Wireless Access Point](#Wireless_Access_Point) nach einem Neustart automatisch verbunden werden soll.

![](/assets/img/Remember_Wifi.png)

## Gerätemanagement {#Geraetemanagement}

Dieser Bereich hilft Ihnen, die [Sprache](#Sprache) der Benutzeroberfläche, die [Auflösung](#Auflösung) oder die Angabe [Max. Verbindungen](#MaxVerbindungen) zu wechseln. Außerdem können Sie für Empfänger und Sender die [Kopplungsdatei herunterladen](#Kopplungsdatei_herunterladen).

### Sprache {#Sprache}

Unter Sprache wählen die gewünschte Anzeigesprache der Web-Oberfläche aus.

![](/assets/img/Select_language.jpg)

### Auflösung {#Auflösung}

Hier wählen Sie die Ausgabeauflösung des QuattroPods aus. Sie können entweder eine bestimmte Auflösung auswählen oder wählen Sie einfach `Auto` und der QuattroPod stellt die optimale Auslösung für Ihren Bildschirm automatisch ein.

| Standard | Auflösung|
| :------------- |:-----:|
| HD | 1280 × 720 |
| Full-HD | 1920 × 1080 |
| 4K UHD | 3840 × 2160 |
| DCI 4K | 4096 × 2160 |


![](/assets/img/resolution.png)

### Max. Verbindungen {#MaxVerbindungen}

Hier geben Sie die maximale Benutzeranzahl des Empfängers an.

![](/assets/img/Max_connections.png)

### Android Audioübertragung {#Androidsoundstreaming}

Hier aktivieren Sie Android Sound Streaming über die Android App.

![](/assets/img/Android-Audio-Streaming.png)

### Anzeigemodus {#Anzeigemodus}

Hier legen Sie fest, ob die Anzeige Ihres Endgeräts auf dem externen Bildschirm bzw. auf dem Beamer im `Original` oder im `Vollbild` angezeigt werden soll.

![](/assets/img/QuattroPod.display.mode.jpg)

#### Original

Mit Original-Modus wird das ursprüngliche Seitenverhältnis des Endgeräts z.B. eines iPads auf dem externen Bildschirm bzw. auf dem Beamer angezeigt:

![Das iPad wird im Original angezeigt](/assets/img/NEC_E506_Original.png)

#### Vollbild

Mit Vollbild-Modus wird die Eingabe des Endgeräts automatisch angepasst, um das gleiche Seitenverhältnis wie der externe Bildschirm bzw. der Beamer zu haben:

![Das iPad wird im Vollbild angezeigt](/assets/img/NEC_E506_Vollbild.png)

### Zeitgesteuerter Neustart {#timedrestart}

Um die Leistung des QuattroPods zu optimieren, insbesondere bei Geräten, die dauerhaft im Betrieb sind, aktivieren Sie die Funktion `Zeitgesteurter Neustart`. Der Empfänger startet sich automatisch neu, wenn die folgenden Bedingungen zutreffen:

* Der QuattroPod war war 2/4/8 Stunden nicht im Betrieb. 
* Alle Sender sind mind. 2/4/8 Stunden ausgeschaltet.
* Weder AirPlay noch die Android App wurden seit 2/4/8 Stunden verwendet.
* Die Web-Oberfläche der Einstellungen wurde 2/4/8 Stunden nicht verwendet.

![Zeitgesteuerter Neustart einschalten](/assets/img/timed.restart.png)

## Admineinstellungen {#Admineinstellungen}

In diesem Bereich können Sie den QuattroPod auf die neueste Firmware aktualisieren, auf Standardeinstellungen zurücksetzen und andere erweiterten Einstellungen setzen.

### WLAN-Kanal {#WiFi-Mode}

Um störende WLAN-Signale zu vermeiden, können Sie den WLAN-Modus anpassen.

![](/assets/img/Wifi-Modus.png)

### LAN IP-Einstellungen {#LAN-IP-Einstellungen}

Eine statische IP-Adresse für den LAN-Anschuss des Empfängers vergeben.

![](/assets/img/LAN_IP_Settings.jpg)

### SSID-Name {#SSID}

Hier können Sie die SSID des Empfängers umbenennen, verstecken, oder ausschalten.

![](/assets/img/SSID.jpg)

### Kennwort (fürs WLAN) {#WLAN-Kennwort}

Aus Sicherheitsgründen kann das Kennwort geändert oder versteckt werden.

![](/assets/img/Password.jpg)

### Zentrales Managementsystem {#cms}

Hier können die Unterstüztung für das zentrale Managementsystem (CMS) aktivieren.

![](/assets/img/cms.png)

### Konferenzsteuerung {#Konferenzsteuerung}

Mit der Konferenzensteuerung können Sie die folgenden Aufgaben durchführen:

* Alle Geräte trennen
* Die Role als Host bzw. als Moderator einem Gast zuordnen
* Geräte auf dem Bildschirm neu positionieren

![](/assets/img/Conference_Control.png)

Eine umfassende Information zu diesem Thema finden Sie [hier](conference-control.md). 

### Mein Bildschirm {#Mein-Bildschirm}

Das Hintergrundbild des Startbildschirm können Sie mit bis zu zwei eigenen Hintergrundbildern ersetzen. Bei zwei Hintergrundbildern blättern diese automatisch alle 10 Sekunden.

Einen Download der von uns mitgelieferten Hintergrundsbildern finden Sie auf unseren [empfohlenen Einstellungen](reset.md#recommendedsettings).

![](/assets/img/My_Screen.png)

### Dynamisches Hintergrundbild {#Dynamicwallpaper}

Das dynamische Hintergrundbild, ist eine Funktion, die nach einer einstellbaren Zeit der Inaktivität automatisch gestartet wird und eine Sammlung von Bildern bzw. Videos auf dem Bildschirm anzeigt.

Eine umfassende Anleitung zur Verwendung von Dynamisches Hintergrundbild finden Sie [hier](dynamicwallpaper.md).

### Host-Kontrolle {#Host-Control}

**Antrag automatisch genehmigen**

Der erste sich verbindende Benutzer wird als Gastgeber (Host) bezeichnet und die anderen als Gäste. Standardmäßig muss jeder Antrag zum Senden vom Host genehmigt werden, im dem er die Kontrolltaste seines Senders drückt. Wenn `Antrag automatisch genehmigen` auf `On` eingestellt ist, wird der Antrag zum Senden automatisch genehmigt. Mehr zu diesem Thema finden Sie im Kapitel [Sender bedienen](TX-controls.md).

**Bildschirm teilen**

Standardmäßig ist diese Funktion freigeschaltet. Dies bedeutet, dass der Bildschirm geteilt wird, um bis zu vier Geräte gleichzeitig zu zeigen, auch bekannt als Splitscreen-Modus. Wenn `Bildschirm teilen` aus ist, übernimmt der nächste genehmigte Sender im Vollbildmodus.

![](/assets/img/host_control.jpg)

### AirPlay {#AirPlay}

Mit einem iOS/macOS Gerät können Sie Ihren Bildschirminhalt auch direkt per Apple AirPlay übertragen. Das bedeutet, Sie benötigen in diesem Fall keinen QuattroPod-Sender.

![](/assets/img/AirPlay.png)

#### Miracast {#Miracast}

Die Übertragung von Miracast-Geräten unterstützen. Eine umfassende Anleitung zur Verwendung von Miracast finden Sie [hier](miracast.md).

![](/assets/img/Miracast.png)

### Admin-Kennwort {#AdminKennwort}

Das Admin-Kennwort des Empfängers ändern.

![](/assets/img/admin_password.png)

### Bildschirmschoner {#Bildschirmschoner}

Bildschirm bzw. die HDMI-Ausgabe des Empfängers nach einer bestimmten Zeit der Inaktivität ausschalten. Standardmäßig ist diese Funktion deaktiviert.

![](/assets/img/screensaver.jpg)

Inaktivität bedeutet, dass die Startseite auf dem Bildschirm angezeigt wird und keine Sender  Inhalte übertragen.

![Inaktivität beginnt, wenn die Startseite angezeigt wird](/assets/img/QuattroPod_Startseite.png)

Während der Bildschirmschoner läuft, bleibt der Empfänger im Betrieb. Die Web-Oberfläche ist erreichbar und die Sender können noch verbunden werden.

Sie können den Empfänger aufwecken bzw. die HDMI-Ausgabe wiederherstellen, indem Sie Inhalte vom Sender erneut übertragen.

### Enterprise-WLAN

Ein digitales Zertifikat hochladen.

![](/assets/img/quattropod.digital_certificate.png)

### Festgelegter Host

Legen Sie einen bestimmten Benutzer bzw. einen Sender fest, dass sich immer als Host der Präsentation bezeichnet wird. Eine umfassende Anleitung zu diesem Thema finden Sie [hier](fixedhost.md).

![](/assets/img/QuattroPod_Fixedhost.Select.jpg)

### Google Cast

Die Übertragung von ChromeCast-Geräten unterstützen. Eine umfassende Anleitung zur Verwendung von Chromecast finden Sie [hier](chromecast.md).

![](/assets/img/Chromecast-support.png)

### Castcode

Legen Sie fest, ob jeder Gast per die Android-App bzw. per AirPlay einen vierstelligen Code eingeben muss, um Inhalte übertragen zu dürfen.

* `AUS` - Kein Passcode wird benötigt
* `Zufällig` - Zufällig (erneut sich automatisch beim Einschalten bzw. beim Neustart)
* `Fest` - Einen festen Castcode angeben

Der Castcode wird hier angezeigt:

![Der Castcode](/assets/img/QuattroPod_Castcode.png)

### Upgrade

Sie können die Firmware der Empfänger und Sender aktualisieren, um die neuesten Erweiterungen und Funktionen nutzen zu können. Eine umfassende Anleitung zur Aktualisierung finden Sie [hier](firmware-upgrade.md).

### Kopplungsdatei herunterladen {#Kopplungsdatei_herunterladen}

Laden Sie die Kopplungsdatei herunter, um einen Sender mit dem Empfänger per USB-Stick zu koppeln, wenn der Empfänger an der Decke montiert ist oder einfach schwer zu erreichen ist. Weitere Informationen hierzu finden Sie im Abschnitt [Sender koppeln](pairing.md).

![](/assets/img/pairing_file.jpg)

### Multicast {#Multicast}

Nutzen Sie diese Funktion, um den Empfänger im Multicast-Modus zu starten. Eine umfassende Anleitung zu diesem Thema finden Sie [hier](multicast.md).

![Neustarten](/assets/img/Multicast-Gruppe.png)

### Neustarten {#Neustarten}

Nutzen Sie diese Funktion, um den Empfänger neu zu starten.

![Neustarten](/assets/img/restart.jpg)

### Auf Standardeinstellungen zurücksetzen {#zuruecksetzen}

Nutzen Sie diese Funktion, um den Empfänger und die Sender auf die Standardeinstellungen zurückzusetzen. Dies beeinflusst weder das [Hintergrundbild](#Mein-Bildschirm) der Startseite, die [SSID](#SSID), noch die Firmware-Version.

Wenn Ihr Sender sich nach dem Zurücksetzen nicht freischalten lässt, überprüfen Sie den [Empfänger](quickstart.md#setup) und [koppeln](pairing.md) Sie den Sender mit dem Empfänger neu.

![Auf Standardeinstellungen zurücksetzen](/assets/img/reset_settings.png)

## Über das Gerät {#Ueber}

Nutzen Sie diese Option, um eine Übersicht des QuattroPods, aller verbundenen Sender und Netzwerkinformationen dazu zu erhalten.

![Über](/assets/img/About.jpg)





