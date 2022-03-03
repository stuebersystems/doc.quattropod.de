# Logdatei herunterladen

Zu Support-Zwecken bitten wir Sie möglicherweise, dass Sie uns eine Logdatei Ihres Gerätes zukommen lassen. Es gibt zwei Arten von Logdateien:

!!! tip "Hinweis"
    
	Eine Supportleistung bieten wir nur Kunden an, die bei uns bestellt haben. Bitte wenden Sie sich an Ihren Händler.
	
* [Debug Logdatei](#download.logfile)

Mit der Funktion **Debug Logdatei herunterladen** handelt sich um die Logdatei, die direkt vom QuattroPod Gerät heruntergeladen wird.

* [Debug Over IP](#debug.over.ip)

Mit dem Verfahren **Debug Over IP** werden die Debug-Informationen über Ihre Netzwerkinfrastruktur mittels einer Terminal-Software eingelesen und in eine Logdatei abgespeichert.

## Debug Logdatei herunterladen {#download.logfile}

Dabei müssen Sie die `Developer Options` aktivieren und die Funktion `Download Debug Log` wählen. Mit Hilfe der Funktion **Erweiterte Einstellungen** können Sie sich anmelden und mit einem beliebigen Webbrowser die Logdatei herunterladen.

### Erweiterte Einstellungen öffnen 

* Notieren Sie sich die IP-Adresse, die unten links auf der Startseite angezeigt wird.

![](/assets/img/QuattroPod_IP.png)

* Rufen Sie nun Ihren Web-Browser auf.

![](/assets/img/Google_Chrome.png)

* Klicken Sie mit der Maus in die Adressleiste des Browsers und geben Sie die IP-Adresse des QuattroPod Gerätes ein.

![](/assets/img/IP-Address.png)

### Sich als Admin anmelden

* Geben Sie das Admin-Kennwort ein und klicken Sie auf OK, um sich anzumelden. Standardmäßig lautet das Kennwort `000000`. Wenn dieses Kennwort nicht akzeptiert wird setzen Sie das Gerät per [Reset-Schalter](reset.md#hardreset) zurück.

![](/assets/img/QuattroPod-Login.png)

### Debug Logdatei herunterladen

* Aus dem Hauptmenü wählen Sie `Admineinstellungen`:

![](/assets/img/quattropod.select.admin.png)

* Klicken Sie neun Mal hinereinander auf dem Text `Admineinstellungen`:

![](/assets/img/click.adminsettings.png)

* Klicken Sie auf `Zurück`, wählen Sie anschließend den Menüpunkt `Developer Options`:

![](/assets/img/qp.select.developermode.png)

* Klicken Sie auf die Funktion `Download Debug Log`. Eine Logdatei wird heruntergeladen:

![](/assets/img/proII.select.debuglog.png)

* Lassen Sie uns bitte die Logdatei über unser [Ticketsystem](https://support.stueber.de) zukommen. 

![](/assets/img/logfile.ticket.png)


## Debug Over IP durchführen {#debug.over.ip}

Dabei müssen Sie die Funktion `Debug Over IP` aktivieren und die Prozessinformationen des QuattroPod Gerätes ablesen. Die Daten werden anschließend in eine Logdatei abgespeichert.

Mit Hilfe der Funktion **Erweiterte Einstellungen** können Sie sich anmelden und mit einem beliebigen Webbrowser die Logdatei herunterladen.

### Erweiterte Einstellungen öffnen

* Notieren Sie sich die IP-Adresse, die unten links auf der Startseite angezeigt wird.

![](/assets/img/QuattroPod_IP.png)

* Rufen Sie nun Ihren Web-Browser auf.

![](/assets/img/Google_Chrome.png)

* Klicken Sie mit der Maus in die Adressleiste des Browsers und geben Sie die IP-Adresse des QuattroPod Gerätes ein.

![](/assets/img/IP-Address.png)

### Sich als Admin anmelden

* Geben Sie das Admin-Kennwort ein und klicken Sie auf OK, um sich anzumelden. Standardmäßig lautet das Kennwort `000000`. Wenn dieses Kennwort nicht akzeptiert wird setzen Sie das Gerät per [Reset-Schalter](reset.md#hardreset) zurück.

![](/assets/img/QuattroPod-Login.png)

### Debug Over IP aktivieren

* Aus dem Hauptmenü wählen Sie `Admineinstellungen`:

![](/assets/img/quattropod.select.admin.png)

* Klicken Sie neun Mal hinereinander auf dem Text `Admineinstellungen`:

![](/assets/img/click.adminsettings.png)

* Klicken Sie auf `Zurück`, wählen Sie anschließend den Menüpunkt `Developer Options`:

![](/assets/img/qp.select.developermode.png)

* Klicken Sie auf die Funktion `Debug Over IP`, um den Netzwerkdienst zu aktivieren. Eine Logdatei wird heruntergeladen:

![](/assets/img/proII.select.debugviaip.on.png)

* Um die Einstellung freizuschalten, müssen Sie den QuattroPod neu starten. Im Menü `Admineinstellungen` wählen Sie `Neustarten`.

![](/assets/img/restart.png)

* Dann wählen Sie erneut die Schaltfläche `Neustarten`.

![](/assets/img/restart.jpg)

Laden Sie die Terminal-Software [Tera Term](https://osdn.net/projects/ttssh2/releases/) herunter und führen Sie das Installationspaket aus:

[![teraterm.png](/assets/img/teraterm.png)](https://osdn.net/projects/ttssh2/releases/)

* Sie können die vorgegebenen Einstellungen übernehmen:

![](/assets/img/teraterm.components.png)

* Wählen Sie Ihre bevorzugte Sprache aus:

![](/assets/img/teraterm.language.png)

* Am Ende der Installation setzen Sie ein Häkchen neben `Launch Tera Term` ein und klicken Sie auf `Finish`:

![](/assets/img/teraterm.launch.png)

* Notieren Sie sich die IP-Adresse, die unten links auf der Startseite angezeigt wird.

![](/assets/img/QuattroPod_IP.png)

* Im Dialogfenster `Neue Verbindung` geben Sie die IP-Adresse Ihres QuattroPod Gerätes sowie den TCP-Port `8700` ein und wählen Sie den Dienst `Telnet` aus. Ihr Rechner muss sich im gleichen Netzwerk wie das QuattroPod Gerät befinden:

![](/assets/img/teraterm.new.connection.png)

* Wurde die Verbindung erfolgreich aufgebaut, werden die Prozessinformationen im Tera-Term-Fenster angezeigt:

![](/assets/img/teraterm.data.png)

* Unter `Datei` -> `Log...` speichern Sie die Logdatei im Ordner `Dokumente` ab:

![](/assets/img/Logfile.save.png)

![](/assets/img/Logfile.save.documents.png)

!!! tip "Hinweis"
    
	Zu diesem Zeitpunkt werden alle Aktivitäten des QuattroPod Geräts in die Protokolldatei eingelesen. An dieser Stelle müssen Sie die Ereignisse reproduzieren, die das Problem verursacht haben z.B. die Berührungsgesten auf dem Bildschirm, sollten Sie diese jetzt ausführen, bis das Problem wieder auftritt und in der Protokolldatei aufgezeichnet wird.


* Lassen Sie uns bitte die Logdatei über unser [Ticketsystem](https://support.stueber.de) zukommen. 

![](/assets/img/logfile.ticket.png)

### Debug Over IP deaktivieren

* Schließlich am Ende des Verfahrens können Sie die Funktion **Debug Over IP** wieder deaktivieren:

![](/assets/img/proII.select.debugviaip.off.png)

* Um die `Developer Options` wieder auszublenden, klicken Sie auf die Funktion `Debug Mode`. Sie kehren zurück auf das Hauptmenü:

![](/assets/img/quattropod.select.developeroptions.off.png)