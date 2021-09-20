# QuattroPod auf Standardeinstellungen zurücksetzen

Es gibt mehrere Gründe für einen Reset des QuattroPods auf Werkseinstellungen:

* Sie haben das Admin-Kennwort für die [Erweiterten Einstellungen](adv.settings.md) vergessen.

* Sie haben Änderungen in Ihrer Netzwerkinfrastruktur, den LAN-TCP/IP-Einstellungen oder den SSID-Zugangsdaten des QuattroPods vorgenommen und Ihr QuattroPod ist nicht mehr erreichbar.

* Sie haben Probleme eine ungewollte Änderung auf dem QuattroPod rückgängig zu machen.

Mit einem Zurücksetzen werden alle Einstellungen zurückgesetzt, außer die [WLAN-SSID](adv.settings.md#SSID), das [Hintergrundbild](adv.settings.md#Mein-Bildschirm) der  Startseite, und die Firmware-Version.

## Zurücksetzen per Reset-Schalter {#hardreset}

Wenn Ihnen die Zugangsdaten zu der [Web-Oberfläche](adv.settings.md) nicht bekannt sind, haben Sie die Möglichkeit mit dem Reset-Schalter die Standardeinstellungen zurückzusetzen:

* Mit Hilfe eines kleinen "Stifts" halten Sie den Reset-Schalter ca. 10 Sekunden lang gedrückt. 

![Reset-Schalter befindet sich an der Rückseite des QuattroPods](/assets/img/Press-Reset-Button.jpg)

* Wenn die folgende Meldung erscheint, lassen Sie den Reset-Schalter los.

![](/assets/img/Reset_config_complete.png)

* Nach dem Zurücksetzen muss bei der ersten Anmeldung auf der Web-Oberfläche das Land des WLAN-Kanals ausgewählt werden. Für Geräte innerhalb Europa wählen Sie bitte `EUROPE` aus. Geben Sie anschließend ein neues Admin-Kennwort ein.

![](/assets/img/wifi.land.selection.EN.png)

## Zurücksetzen per Web-Oberfläche

Mit Hilfe der Funktion [Erweiterte Einstellungen](adv.settings.md) können Sie sich anmelden und mit einem beliebigen Webbrowser auf die Standardeinstellungen zurücksetzen.

**Anmeldung**

* Notieren Sie sich die IP-Adresse, die unten links auf der Startseite angezeigt wird.

![](/assets/img/QuattroPod_IP.png)

* Rufen Sie nun Ihren Web-Browser auf.

![](/assets/img/Google_Chrome.png)

* Klicken Sie mit der Maus in die Adressleiste des Browsers und geben Sie die IP-Adresse des QuattroPods ein.

![](/assets/img/IP-Address.png)

* Nachdem Sie die Eingabetaste gedrückt haben, erscheint die Einstellungsoberfläche des QuattroPods. Geben Sie das Kennwort ein. Standardmäßig lautet es `000000`. Wenn dieses Kennwort nicht akzeptiert wird, müssen Sie ein [Zurücksetzen per Reset-Schlater](#zurücksetzen-per-reset-schalter) durchführen.

![](/assets/img/QuattroPod-Login.png)

* Die folgenden Funktionen stehen zur Verfügung. Wählen Sie den Menüpunkt `Admineinstellungen`:

![](/assets/img/quattropod.select.admin.png)

* Führen Sie die Funktion `Auf Standardeinstellungen zurücksetzen` aus. Der Empfänger startet sich neu:

![](/assets/img/reset_option.png)

* Sie können auswählen, genau welche Geräte zurückgesetzt werden sollen. Dies beeinflusst weder das Hintergrundbild der Startseite, die SSID, noch die Firmware-Version. Klicken Sie auf `OK`, um das Gerät neu zu starten:

![Auf Standardeinstellungen zurücksetzen](/assets/img/reset_settings.png)

* Nach dem Zurücksetzen des Empfängers muss bei der ersten Anmeldung auf der Web-Oberfläche das Land des WLAN-Kanals ausgewählt werden. Für Geräte innerhalb Europa wählen Sie bitte `EUROPE` aus. Geben Sie ein neues Admin-Kennwort ein und klicken Sie anschließend auf `Apply and Reboot`, um das Gerät neu zu starten:

![](/assets/img/wifi.land.selection.EN.png)

!!! tip "Hinweis"
    
	Wenn Ihr Sender sich nach dem Zurücksetzen nicht freischalten lässt, überprüfen Sie den [Empfänger](quickstart.md#setup) und [koppeln](pairing.md) Sie den Sender mit dem Empfänger neu.
	
## Einstellungen nach dem Zurücksetzen {#recommendedsettings}

Wir empfehlen die folgenden Einstellungen:

Firmware-Version: [1.12412.42](whatsnew.md#20210712-11241242)

**Gerätemanagement**

* [Sprache](adv.settings.md#Sprache): `DEUTSCH`
* [Android Audioübertragung](adv.settings.md#Androidsoundstreaming): `EIN`
* [Zeitgesteuerter Neustart](adv.settings.md#timedrestart): `2 Stunden`

**Admineinstellungen**

* [WLAN-Modus](adv.settings.md#WiFi-Mode): `Land = EUROPE`, `Kanal = Auto`, `Bandbreite = 20MHz`
* [Zentrales Managementsystem](adv.settings.md#AirView): `EIN`
* [Mein Bildschirm](adv.settings.md#Mein-Bildschirm): unsere [Startseite](https://download.stueber.de/doc/de/quattropod/QuattroPod_StartseiteDE.png) in der deutschen Sprache
* [AirPlay](adv.settings.md#AirPlay): `EIN`
* [Castcode](adv.settings.md#castcode): `Zufällig`
* [Google Cast](adv.settings.md#google-cast): `EIN`

