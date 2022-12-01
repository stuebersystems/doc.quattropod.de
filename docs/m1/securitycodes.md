# Sicherheitscodes aktivieren

## Was ist ein Sicherheitscode?

Ein Sicherheitscode gewährleistet zusätzliche Sicherheit gegen unberechtigte Bildschirmübertragung, indem jeder Teilnehmer einen Code eingeben muss, bevor die Bildschirmübertagung beginnen darf. So können Sie sicherstellen, dass nur die im Raum anwesenden Personen ihre Inhalte anzeigen können. 

![Der Castcode](/assets/img/enter.castcode.png)

Der QuattroPod integriert verschiedene Streamingprotokolle (Miracast/AirPlay/Google Cast), um alle Endgeräte nach dem Prinzip Bring Your Own Device (BYOD) unterstützen zu können. Jedes Streamingprotokoll enthält seine eigene entwickelte Funktionalität.

## Welche Streamingprotokolle unterstützen einen Sicherheitscode?

Ein Sicherheitscode wird mit den folgenden Streamingprotokollen unterstützt:

* Die `QuattroPod` App unter Android
* `AirPlay` unter iOS und macOS
* `Miracast` unter Windows und Android

## Wie unterscheiden sich die Sicherheitscodes der Streamingprotokolle?

### Castcode

Der Castcode wurde vom QuattroPod entwickelt und unterstützt das Protokoll `AirPlay` für Apple-Geräte sowie die `QuattroPod` App unter Android. Es handelt sich um einen vierstelligen Code, der oben mitten der Startseite ständig angezeigt wird:

![Der Castcode](/assets/img/QuattroPod_Castcode.png)

Die Funktion `Castcode-Kontrolle` ist in der Weboberfläche unter [Admineinstellungen -> Castcode-Kontrolle](adv.settings.md#castcode) zu finden und bietet folgende Einstellungen:

* `AUS` - Kein Castcode wird benötigt bzw. angezeigt.
* `Zufällig` - Erneut sich regelmäßig
* `Fest` - Einen festen Castcode angeben

### Miracast PIN 

Der Miracast-PIN erscheint erst als zufälliger vier-  bzw. achtstelliger Code in gelb unten auf der Startseite, wenn ein Miracast-Gerät dem QuattroPod einen Antrag zum Spiegeln sendet und bietet folgende Einstellungen:

![Miracast PIN ](/assets/img/Miracast.pin.png)
 
Aktivieren Sie den Miracast-PIN in der Weboberfläche unter [Admineinstellungen -> Miracast](adv.settings.md#Miracast):

![Miracast PIN ](/assets/img/Miracast.png)

### AirPlay PIN

Viele Organisationen, Schulen und Unternehmen nutzen [Mobile Device Management](https://support.apple.com/de-de/guide/deployment-education/edu1c1be3511/web) (MDM), um ihre Geräte zu verwalten. Je nach den Richtlinien Ihrer Organisation kann es erfordlich sein, den AirPlay-PIN zu aktivieren, um den Bildschirm Ihres Apple-Gerätes übertragen zu können.

Der AirPlay-PIN-Code erscheint erst als zufälliger vierstelliger Code unten auf der Startseite, wenn ein Apple-Gerät dem QuattroPod einen Antrag zum Spiegeln sendet:

![AirPlay PIN](/assets/img/airplay.pin.png)
 
Aktivieren Sie den AirPlay-PIN-Code in der Weboberfläche unter [Admineinstellungen -> AirPlay-Modus](adv.settings.md#AirPlay):

![AirPlay PIN](/assets/img/AirPlay.png)

## Welche Streamingprotokolle unterstützen keinen Sicherheitscode?

Aufgrund einer Limitierung des Protokolls unterstützt `Google Cast` aktuell keinen Sicherheitscode. Sie können dennoch gegen unberechtigte Bildschirmübertragung schützen:

### Google Cast

Derzeit gibt es innerhalb des Protokolls `Google Cast` keinen Sicherheitscode. Sie haben jedoch die Möglichkeit mit Hilfe des Senders und der Funktion Host-Kontrolle gegen unberechtigte Bildschirmübertragung zu schützen.

Das Endgerät sendet dem QuattroPod einen Antrag zum Spiegeln. Das grüne Symbol der Funktion Host-Kontrolle erscheint auf der Startseite, um anzuzeigen, dass der Antrag eine Antwort vom Moderator (Host) erwartet:

![Host Control](/assets/img/host.control2.png)

Der Sender blinkt Grün und der Moderator drückt einmal zum Genehmigen oder zweimal zum Ablehnen:

![Host Control](/assets/img/screen.mirror.approve.png)
 
Wenn Sie nur Streamingprotokolle zulassen möchten, die einen Sicherheitscode unterstützen, können Sie das Protokoll Google Cast unter [Admineinstellungen -> Google Cast](adv.settings.md#googlecast) deaktivieren:

![Google Cast deaktivieren](/assets/img/googlecast.deactivate.png)

## Wie genau aktiviert man einen Sicherheitscode?

### Erweiterte Einstellungen öffnen

* Verbinden Sie Ihr Endgerät mit dem QuattroPod, entweder mit der SSID des QuattroPods oder mit derselben WLAN- bzw. LAN-Infrastruktur, mit welcher der QuattroPod verbunden ist:

![](/assets/img/quattropod.ssid.connect.png)

* In die Adressleiste eines Webbrowsers geben Sie die IP-Adresse des QuattroPods ein, entweder die `Direct Link IP` oder die `Infrastructure IP`, je nachdem, mit welcher Ihr Gerät verbunden ist. Die Einstellungsoberfläche des QuattroPods erscheint:

![](/assets/img/quattropod_directIP.connect.png)

### Sich als Admin anmelden

* Geben Sie das Admin-Kennwort ein und klicken Sie auf `OK`, um sich anzumelden. Standardmäßig lautet das Kennwort `000000`. Wenn dieses Kennwort nicht akzeptiert wird setzen Sie das Gerät per [Reset-Schalter](reset.md#hardreset) zurück.

![](/assets/img/QuattroPod-Login.png)

### Einen Sicherheitscode aktivieren

* Aus dem Menü wählen Sie `Admineinstellungen` aus:

![](/assets/img/quattropod.select.admin.png)

* Zum Aktivieren des **Castcodes**, wählen Sie [Admineinstellungen -> Castcode-Kontrolle](adv.settings.md#castcode):

![](/assets/img/QP.castcode.png)

* Wählen Sie die gewünschte Einstellung aus:

![](/assets/img/qp.select.castcode.png)

* Zum Aktivieren des **Miracast-PINs**, wählen Sie [Admineinstellungen -> Miracast-Unterstützung](adv.settings.md#Miracast):

![Miracast PIN ](/assets/img/Miracast.select.pin.png)

* Zum Aktivieren des **AirPlay-PINs** wählen Sie [Admineinstellungen -> AirPlay](adv.settings.md#AirPlay):

![AirPlay PIN](/assets/img/airplay.select.pin.png)

* Die Einstellungen werden erst nach einem Neustart wirksam:

![](/assets/img/restart.png)

