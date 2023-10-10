## Was ist der SoftAP?

Der QuattroPod verfügt über zwei Netzwerkschnittstellen: 

* den [SoftAP](https://en.wikipedia.org/wiki/SoftAP), auch als **Direkte Verbindung** bekannt.
* die [Netzwerkinfrastruktur](connect.wifi.lan.md), auch als **Über Router** bekannt.

Der SoftAP dient als intergrierter WLAN-AccessPoint des QuattroPods. Bei der Ersteinrichtung verbinden Sie Ihr Endgerät mit dem SoftAP. Die Standard-SSID des SoftAP lautet normalerweise etwas in der Art von `QuattroR01_BF9019B5`. Anschließend verbinden Sie die EZCast Pro Box II entweder drahtlos per WLAN oder per LAN-Kabel mit Ihrer [Netzwerkinfrastruktur](connect.wifi.lan.md). Der QuattroPod ist dann standardmäßig über beide Netzwerkschnittstellen erreichbar:

![](/assets/img/softap.enabled.qp.png)

## Was genau wird deaktiviert?

Wenn Sie den SoftAP des EZCast Pro Stick II deaktiveren, wird der Stick nur über die Netzwerkinfrastruktur erreichbar:

![](/assets/img/softap.disabled.stick.png)

### Betroffene Streamingprotokolle

Die folgenden Streamingprotokolle benötigen entweder eine Verbindung mit dem SoftAP oder mit der Netzwerkinfrastruktur:

* [AirPlay](airplay.md)
* [Google Cast](googlecast.md)

Da das Streamingprotokoll Miracast kann nicht unterstützt werden, ohne Aktivierung des SoftAP:

* [Miracast](miracast.md)

Wenn Sie die SSID bzw. das Kennwort des SoftAP lediglich ausblenden werden keine Streamingprotokolle betroffen.

### Betroffene Sender

Wenn Sie den SoftAP deaktivieren, kann kein Sender mehr mit dem Emfänger drahtlos verbinden. Wenn Sie die SSID bzw. das Kennwort des SoftAP lediglich ausblenden, sind die Sender nicht betroffen.

## Warum deaktiviert man den SoftAP?

* Sie möchten keine Bildschirmübertragung mehr drahtlos mit dem Sender zulassen, sondern nur die Streamingprotokolle über Ihre Netzwerkinfrastruktur.

* Sie möchten verhindern, dass Endgeräte unbeabsichtigt mit der falschen SSID erneut verbunden werden. Stattdessen sollten sie immer im Schul-WLAN verbleiben und über die Netzwerkinfrastruktur auf die EZCast Pro-Geräte zugreifen können.

* Sie möchten sicherstellen, dass alle Endgeräte sich zuerst über Ihre Netzwerkinfrastruktur authentifizieren, bevor sie auf das Internet oder andere Gerätedienste zugreifen können.

* Sie möchten die Anzahl der ausgestrahlten SSIDs in Ihrer Umgebung minimieren.

## Mit Miracast-Unterstützung

Mithilfe der Funktion [Erweiterte Einstellungen](adv.settings.md) deaktivieren Sie `Admineinstellungen` -> `Miracast-Unterstützung` und starten Sie den QuattroPod neu:

![](/assets/img/Miracast.NGO.mode.png)

Nach Deaktivierung des Vollbildmodus (NGO-Modus) stehen Ihnen folgende Optionen zur Verfügung:

#### SoftAP deaktivieren

* Mit der Einstellung `Admineinstellungen` -> `Verbindung` -> `Nur über Router` wird der SoftAP des EZCast Pro Gerätes vollständig deaktiviert:

![](/assets/img/connection.only-router.png)

Die SSID des SoftAP auf der Startseite wird ausgegraut. Das Kennwort und die IP-Adresse des SoftAP werden ausgeblendet. Die SSID des SoftAP wird nicht mehr ausgestrahlt und ist auf den Endgeräten nicht mehr sichtbar. Das EZCast Pro Gerät ist dann nur über Ihre Infrastruktur erreichbar:

![](/assets/img/ezcastpro.II.via.Router.only.png)

#### SSID ausblenden

Sie möchten den SoftAP nicht deaktivieren, sondern nur die SSID ausblenden? 

* Mit der Einstellung `Admineinstellungen` -> `Verbindung` -> `Über Router oder direkte Verbindung` wird der SoftAP aktiviert:

![](/assets/img/Connection_EZCastProII.png)

* Aktiveren Sie anschließend die Funktion `Gerätemanagement` -> `Gerätename` -> `SSID verstecken`:

![](/assets/img/hide.ssid.png)

Die SSID bzw. der Gerätename wird auf der Startseite ausgeblendet:

![](/assets/img/ssid.hidden.ngo-mode.png)

Eine Verbindung mit dem SoftAP muss auf dem Endgerät manuell eingestellt werden:

![](/assets/img/connect.hidden.ssid.png)

#### Kennwort ausblenden

Sie möchten den SoftAP nicht deaktivieren, sondern nur das Kennwort ausblenden? 

* Mit der Einstellung `Admineinstellungen` -> `Verbindung` -> `Über Router oder direkte Verbindung` wird der SoftAP aktiviert:

![](/assets/img/Connection_EZCastProII.png)

* Aktiveren Sie anschließend die Funktion `Netzwerkmanagement` -> `WLAN-Kennwort` -> `Kennwort verstecken`:

![](/assets/img/hide.password.png)

Das Kennwort wird auf der Startseite ausgeblendet:

![](/assets/img/password.hidden.ngo-mode.png)

### Geteilter Bildschirm (AGO-Modus)

Im AGO-Modus ist der SoftAP für den geteilten Bildschirm mit bis zu 4 Geräten, einschließlich Miracast, erforderlich. Die SSID des SoftAP kann weder deaktiviert noch ausgeblendet werden. Sie können lediglich das Kennwort ausblenden:

#### Kennwort ausblenden

Da das Ausblenden des Kennworts nur im Vollbildmodus (NGO-Modus) aktiviert werden kann, schalten Sie zunächst auf diesen Modus um, indem Sie mithilfe der Funktion [Erweiterte Einstellungen](adv.settings.md) `Gerätemanagement` -> `Miracast` -> `Nur im Vollbildmodus` auswählen und das EZCast Pro Gerät neu starten:

![](/assets/img/Miracast.NGO.mode.png)

* Aktiveren Sie anschließend die Funktion `Netzwerkmanagement` -> `WLAN-Kennwort` -> `Kennwort verstecken`:

![](/assets/img/hide.password.png)

Wählen Sie zuletzt `Gerätemanagement` -> `Miracast` -> `Geteilter Bildschirm unterstützt` aus und starten Sie das EZCast Pro Gerät neu:

![](/assets/img/Miracast.AGO.mode2.png)

Das Kennwort wird auf der Startseite ausgeblendet und die angezeigte SSID bzw. der Gerätename enthält das Präfix `DIRECT-`:

![](/assets/img/password.hidden.ago-mode.png)

Eine umfassende Anleitung zu den beiden Schnittstellen finden Sie [hier](adv.settings.md#networkinterfaces).



