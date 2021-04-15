# Firmware neu installieren

Sie können den QuattroPod wiederherstellen, indem Sie die Firmware manuell neu installieren. Es gibt mehrere Gründe dafür:

* Der QuattroPod lässt sich nicht einschalten. Die Stromversorgung wurde bereits kontrolliert. In diesem Fall kann es an einem unterbrochenen Upgrade der Firmware liegen.

* Der QuattroPod läuft unstabil und ein [Reset](reset.md) hat nicht geholfen.

* Sie haben die Wahl: Installieren Sie entweder einfach die neuste Firmware oder eine andere Firmware

!!! tip "Hinweis"
    
	Bei einer Neuinstallation der Firmware werden **alle** Einstellungen zurückgesetzt. 

## Voraussetzung

* Die Firmware-Update-Software wird nur unter Microsoft Windows unterstützt 

* Der Empfänger muss mit Ihrem Windows-PC per [USB-Kabel (A/A)](https://www.amazon.de/deleyCON-Super-Speed-Kabel-Stecker/dp/B00WHZ746E/ref=sr_1_3?ie=UTF8&qid=1531928442&sr=8-3&keywords=usb+kabel+male+to+male) angeschlossen werden

![USB-Kabel-AA](/assets/img/USB-Kabel-AA.jpg)

## Empfänger - Firmware neu installieren

### Empfänger (R01) Repair Tool herunterladen

* Laden Sie das [QuattroPod-Empfänger (R01) Repair Tool](https://download.stueber.de/doc/de/quattropod/repair_tools/QuattroPod.R01.Repair.Tool.zip) herunter.

* Extrahieren Sie die Datei **QuattroPod.R01.Repair.Tool.zip**.

![Empfänger Repair Tool extrahieren](/assets/img/R01.Repair_Tool_Extract.png)

* Installieren Sie **die Treiber**, indem Sie die Batchdatei **QuattroPod.R01.Repair.Tool\usb_driver\install.bat** als Administrator ausführen. 

![install.bat als Administrator ausführen](/assets/img/R01.install.bat.png)

* Wenn die folgende Sicherheitsmeldung erscheint, wählen Sie `Installieren`:

![Klicken Sie auf Installieren, um die Treiber zu installieren](/assets/img/install_drivers.jpg)

### Empfänger in den **Update-Modus** versetzen

Um den Empfänger in den **Update-Modus** zu versetzen, führen Sie bitte die folgenden Schritte der Reihe nach aus:

* Schalten Sie das Gerät per die Power-Taste aus
* Mit Hilfe eines kleinen "Stifts" halten Sie den Reset-Schalter gedrückt
* Schalten Sie das Gerät per die Power-Taste ein
* Lassen Sie anschließend den Reset-Schalter los

![Empfänger in den Update-Modus versetzen](/assets/img/QuattroPod_press_reset.jpg)

* Schließen Sie nun das [USB-Kabel (A/A)](https://www.amazon.de/deleyCON-Super-Speed-Kabel-Stecker/dp/B00WHZ746E/ref=sr_1_3?ie=UTF8&qid=1531928442&sr=8-3&keywords=usb+kabel+male+to+male) an den USB-Port des Empfängers und an einen USB-Port Ihres Rechners unter Microsoft Windows an.

![Empfänger mit Ihrem PC per USB-Kabel (A/A) anschließen](/assets/img/QuattroPod_rear.jpg)

Wenn der Treiber richtig installiert ist und der Empfänger angeschlossen ist, sollte das Gerät **Realtek generic USB Device** im Geräte-Manager erscheinen. Wenn nicht, überprüfen Sie die Treiber-Installation, Kabel-Konfiguration, und den Update-Modus, wie im vorherigen Schritt beschrieben.

!["Realtek generic USB Device“ erscheint im Geräte-Manager](/assets/img/device_manager.jpg)

### Neuste Firmware installieren {#R01_install_latest_fw}

* Im Ordner `QuattroPod.R01.Repair.Tool` führen Sie die Datei **EZCastUpdate.exe** aus.
 
![EZCastUpdate.exe ausführen](/assets/img/R01.Repair_Tool_Update.exe.png)

Das folgende Fenster erscheint. Wenn der QuattroPod-Empfänger erfolgreich im Update-Modus ist, wird im Tool der Status `Device connected`  angezeigt:

* Wählen Sie `Download`, um die neuste Firmware herunterzuladen.
 
![Die Schaltfläche Download wählen](/assets/img/EZCastUpdate.DeviceConnected.jpg)
 
Das Downloaden der Firmware wird durchgeführt:

!!! tip "Hinweis"

    Sie dürfen den Strom während der Aktualisierung nicht unterbrechen.
	
![QuattroPod Firmware wird heruntergefahren](/assets/img/EZCastUpdate.Firmware.Downloading.jpg)

* Um die Installation der Firmware zu starten, wählen Sie `Upgrade`:

![Wählen Sie Upgrade, um die Installation zu starten](/assets/img/EZCastUpdate.Upgrade.jpg)

Die Firmware wird installiert:

![Die Firmware wird installiert](/assets/img/EZCastUpdate.Firmware.Updating.jpg)

Am Ende der Aktualisierung wird der Status „Upgrade Success“ angezeigt:

* Sie können das USB-Kabel nun herausziehen und den Empfänger neustarten, indem Sie ihn über die Power-Taste aus- und einschalten.

![Die Installation war erfolgreich](/assets/img/EZCastUpdate_Upgrade.Success.jpg)

Schalten Sie den Empfänger aus und wieder ein. Der Empfänger ist wieder einsatzbereit.

### Andere Firmware installieren {#R01_install_other_fw}

Um eine vorherige bzw. eine Betafirmware zu installieren, laden Sie eine der folgenden Dateien herunter:

Firmware                       | Herunterladen
------------------------- | ------------
1.9598.72 | [Herunterladen](https://download.stueber.de/doc/de/quattropod/firmwares/R01/R01_1.9598.72.gz)
1.8529.10 | [Herunterladen](https://download.stueber.de/doc/de/quattropod/firmwares/R01/R01_1.8529.10.gz)
1.6468.5 | [Herunterladen](https://download.stueber.de/doc/de/quattropod/firmwares/R01/R01_1.6468.5.gz)


* Im Ordner `QuattroPod.R01.Repair.Tool` führen Sie die Datei **Update_for_localfile.exe** aus.

![Update_for_localfile.exe ausführen](/assets/img/R01.localfile.exe.png)

Das folgende Fenster erscheint. Wenn der QuattroPod im Update-Modus ist, wird im Tool **Device connected** angezeigt.

* Mit Hilfe der Schaltfläche `Firmware` wählen Sie die gewünschte Firmwaredatei aus.

![Firmware auswählen](/assets/img/EZCastUpdate.SelectFirmware.jpg)

* Um die Installation der Firmware zu starten, wählen Sie `Upgrade`.

![Wählen Sie Upgrade, um die Installation zu starten](/assets/img/EZCastUpdate.Upgrade.jpg)

Die Firmware wird installiert.

![Die Firmware wird installiert](/assets/img/EZCastUpdate.Firmware.localfile.Updating.jpg)

Wenn die Installation erfolgreich durchgeführt wurde, erscheint die folgende Meldung:

![Die Installation war erfolgreich](/assets/img/EZCastUpdate_localfile.Upgrade.Success.jpg)

Schalten Sie den Empfänger aus und wieder ein. Der Empfänger ist wieder einsatzbereit.

## Sender - Firmware neu installieren

### Sender (T01) Repair Tool herunterladen

* Laden Sie das [QuattroPod Sender (T01) Repair Tool](https://download.stueber.de/doc/de/quattropod/repair_tools/QuattroPod.T01.Repair.Tool.zip) herunter.

* Extrahieren Sie die Datei **QuattroPod.T01.Repair.Tool.zip**.

![Sender Repair Tool extrahieren](/assets/img/T01.Repair_Tool_Extract.png)

* Installieren Sie **die Treiber**, indem Sie die Batchdatei **QuattroPod.T01.Repair.Tool\usb_driver\install.bat** als Administrator ausführen. 

![install.bat als Administrator ausführen](/assets/img/T01.install.bat.png)

* Wenn die folgende Sicherheitsmeldung erscheint, wählen Sie `Installieren`:

![Klicken Sie auf Installieren, um die Treiber zu installieren](/assets/img/install_drivers.jpg)

### Sender in den **Update-Modus** versetzen

* Um den Sender in den **Update-Modus** zu versetzen, drücken und halten Sie einfach die `Seitetaste` (1), anschließend schließen Sie das USB-Kabel des Senders an einen USB-Port Ihres `Rechners` (2) an. Nach einer Sekunde können Sie die Seitetaste loslassen.

![Sender in den Update-Modus versetzen](/assets/img/QuattroPod_TX_Update-Mode.jpg)

### Neuste Firmware installieren  {#T01_install_latest_fw}

* Im Ordner `QuattroPod.T01.Repair.Tool` führen Sie die Datei **EZCastUpdate.exe** aus.
 
![EZCastUpdate.exe ausführen](/assets/img/T01.Repair_Tool_Update.exe.png)

Das folgende Fenster erscheint. Wenn der QuattroPod-Empfänger erfolgreich im Update-Modus ist, wird im Tool der Status `Device connected`  angezeigt:

* Wählen Sie `Download`, um die neuste Firmware herunterzuladen.
 
![Die Schaltfläche Download wählen](/assets/img/EZCastUpdate.DeviceConnected.jpg)
 
Das Downloaden der Firmware wird durchgeführt:

!!! tip "Hinweis"

    Sie dürfen den Strom während der Aktualisierung nicht unterbrechen.

![QuattroPod Firmware wird heruntergefahren](/assets/img/EZCastUpdate.Firmware.Downloading.jpg)

* Um die Installation der Firmware zu starten, wählen Sie `Upgrade`:

![Wählen Sie Upgrade, um die Installation zu starten](/assets/img/EZCastUpdate.Upgrade.jpg)

Die Firmware wird installiert:

![Die Firmware wird installiert](/assets/img/EZCastUpdate.Firmware.Updating.jpg)

Am Ende der Aktualisierung wird der Status „Upgrade Success“ angezeigt:

* Sie können das USB-Kabel nun herausziehen und den Empfänger neustarten, indem Sie ihn über die Power-Taste aus- und einschalten.

![Die Installation war erfolgreich](/assets/img/EZCastUpdate_Upgrade.Success.jpg)

Schalten Sie den Sender aus und wieder ein. Der Sender ist wieder einsatzbereit.

### Andere Firmware installieren  {#T01_install_other_fw}

Um eine vorherige bzw. eine Betafirmware zu installieren, laden Sie eine der folgenden Dateien herunter:

Firmware                       | Herunterladen
------------------------- | ------------
1.9598.72 | [Herunterladen](https://download.stueber.de/doc/de/quattropod/firmwares/T01/T01_1.9598.72.gz)
1.8529.10 | [Herunterladen](https://download.stueber.de/doc/de/quattropod/firmwares/T01/T01_1.8529.10.gz)
1.6468.5 | [Herunterladen](https://download.stueber.de/doc/de/quattropod/firmwares/T01/T01_1.6468.5.gz)

* Im Ordner `QuattroPod.T01.Repair.Tool` führen Sie die Datei **Update_for_localfile.exe** aus.

![Update_for_localfile.exe ausführen](/assets/img/T01.localfile.exe.png)

Das folgende Fenster erscheint. Wenn der QuattroPod im Update-Modus ist, wird im Tool **Device connected** angezeigt.

* Mit Hilfe der Schaltfläche `Firmware` wählen Sie die gewünschte Firmwaredatei aus.

![Firmware auswählen](/assets/img/EZCastUpdate.SelectFirmware.jpg)

* Um die Installation der Firmware zu starten, wählen Sie `Upgrade`.

![Wählen Sie Upgrade, um die Installation zu starten](/assets/img/EZCastUpdate.Upgrade.jpg)

Die Firmware wird installiert.

![Die Firmware wird installiert](/assets/img/EZCastUpdate.Firmware.localfile.Updating.jpg)

Wenn die Installation erfolgreich durchgeführt wurde, erscheint die folgende Meldung:

![Die Installation war erfolgreich](/assets/img/EZCastUpdate_localfile.Upgrade.Success.jpg)

Schalten Sie den Sender aus und wieder ein. Der Sender ist wieder einsatzbereit.

!!! tip "Hinweis"

     Nach der Firmware-Aktualisierung muss jeder Sender mit dem Empfänger [neu gekoppelt](pairing.md) werden.
	 
## Problembehandlung

### Fehlermeldung: Tool must be in a directory where there are no spaces

* Das Repair Tool muss sich in einem Dateipfad ohne Leerzeichen befinden z.B. `C:\Repair_Tool\EZCastUpdate.exe`. Um diese Fehlermeldung zu vermeiden, verschieben Sie die Software auf einen Pfad ohne Leerzeichen.

![Vermeiden Sie Leerzeichen im Daeipfad vorm Start](/assets/img/no_spaces.jpg)