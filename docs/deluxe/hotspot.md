# Mit Hotspot verbinden

Sollte Sie Verbindungsprobleme bzw. Abbrüche mit dem QuattroPod über Ihre Infrastruktur haben, bitten wir Sie möglicherweise zu Support-Zwecken, dass Sie Ihr QuattroPod mit einem Hotspot verbinden und die Leistung vergleichen. Der Hotspot sollte die Bildschirmübertragung von bis zu vier Endgeräten mindestens 30 - 60 Minuten ohne Probleme leisten können. Zu diesem Test benötigen Sie folgende Geräte:

* ein Android Handy bzw. ein iPhone 11 (oder höher), das am Stromnetz angeschlossen ist.

## Hotspot einrichten

!!! tip "Bitte beachten" 
	Prüfen Sie vor Testbeginn, ob das Netzgerät am Android bzw. am iOS-Gerät angeschlossen ist, damit der Hotspot sich während des Tests nicht ausschaltet.
	
### iOS

* In den Einstellungen wählen Sie den Punkt `Persönlicher Hotspot`, anschließend aktiveren Sie `Zugriff für andere erlauben` und vergeben Sie ein `WLAN-Passwort`. Um die erforderliche **5Ghz Frequenzband** für den QuattroPod zu unterstützen, bitte deaktivieren Sie `Kompatibilität maximieren`:

![](/assets/img/iphone.enable-hotspot.png)

### Android

* In den Einstellungen wählen Sie den Punkt `Verbindungen` und tippen Sie auf `Mobile Hotspot und Tethering`. Aktivieren Sie die Funktion `Mobile Hotspot` und vergeben Sie ein `Hotspot-Passwort`. Um die erforderliche **5Ghz Frequenzband** für das QuattroPod zu unterstützen, bitte wählen Sie `5 GHz bevorzugt`:

![](/assets/img/android.enable-hotspot.png)

## QuattroPod mit Hotspot verbinden

!!! tip "Bitte beachten"
    
	Der QuattroPod unterstützt nur das 5Ghz WLAN-Frequenzband. Stellen Sie bitte sicher, dass Ihr Hotspot für die **5Ghz Frequenzband** eingestellt wurde.
	
### Erweiterte Einstellungen öffnen

* Verbinden Sie Ihr Endgerät mit der SSID des QuattroPods. Die Zugangsdaten werden oben auf der Startseite angezeigt:

![](/assets/img/quattropod.ssid.direct.connect.png)

* In die Adressleiste eines Webbrowsers geben Sie die IP-Adresse des QuattroPods mit der Bezeichnung `Direct Link IP` **192.168.168.1** ein. Die Einstellungsoberfläche des QuattroPods erscheint:

![](/assets/img/quattropod_direct.connect.png)

### Sich als Admin anmelden

* Geben Sie das Admin-Kennwort ein und klicken Sie auf `OK`, um sich anzumelden. Standardmäßig lautet das Kennwort `000000`. Wenn dieses Kennwort nicht akzeptiert wird setzen Sie das Gerät per [Reset-Schalter](reset.md#hardreset) zurück.

![](/assets/img/QuattroPod-Login.png)

### Netzwerkeinstellungen auswählen

* Aus dem Menü oben links wählen Sie `Netzwerkmanagement`.

![](/assets/img/quattropod.select.network.png)

* Wählen den Punkt `Mit 5GHz WLAN-Router/AP verbinden` aus.

![](/assets/img/quattropod.select.connect5ghz.png)

* Verbinden Sie den QuattroPod mit dem Hotspot.

![](/assets/img/Wifi_Internet.png)

Wenn der QuattroPod mit Ihrem Hotspot verbunden ist, wird eine von Ihrem Hotspot vergebenen IP-Adressen mit der Bezeichnung `Infrustructure IP` auf dem Bildschirm angezeigt, wie unten abgebildet:

![](/assets/img/QuattroPod_IP.png)

## Problembehandlung

### WLAN-Signalstärke

Der QuattroPod hat eine Funkreichweite (Sichtlinie) von bis zu 30m aber der Hotspot eines Handys kann bis zu höchstens 10m funkreichweite leisten. Eine geringe Signalanzeige bezieht sich auf eine schlechte Signalstärke zwischen dem QuattroPod und dem Hotspot. Dies kann zu einer abgehackten Wiedergabe von Videos und Inhalten führen, wenn die Inhalte vom Internet abhängig sind oder wenn Ihre Mobilgeräte mit dem Stick über Ihre Infrastruktur verbinden.

Dies kann verschiedene Ursachen und somit verschiedene Lösungen haben:

**1. Problem:** Der Abstand zwischen dem QuattroPod und dem Hotspot ist zu groß.

Lösung: Versuchen Sie den Abstand zu reduzieren.

**2. Problem:** Es liegen Wände oder andere Gegenstände zwischen dem QuattroPod und dem Hotsopt, welche die Signalstärke verschlechtern.

Lösung: Stellen Sie sicher, dass der QuattroPod keine Hindernisse zum Hotspot hat.

![](/assets/img/QP.Internet.Signal.png)