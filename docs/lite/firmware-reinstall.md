# Firmware neu installieren

Sie können den QuattroPod wiederherstellen, indem Sie die Firmware manuell neu installieren. Es gibt mehrere Gründe dafür:

* Der QuattroPod lässt sich nicht einschalten. Die Stromversorgung wurde bereits kontrolliert. In diesem Fall kann es an einem unterbrochenen Upgrade der Firmware liegen.

* Der QuattroPod läuft nicht stabil und ein [Reset](reset.md) hat nicht geholfen.

* Sie haben die Wahl: Installieren Sie entweder einfach die neueste Firmware oder eine andere Firmware

!!! tip "Hinweis"

    Bei einer Neuinstallation der Firmware werden **alle** Einstellungen zurückgesetzt.
	
## Voraussetzung

* Die Firmware-Update-Software wird nur unter Microsoft Windows unterstützt 

* Der Empfänger muss an einen Windows-PC mit einem [USB-Kabel (A/A)](https://www.amazon.de/deleyCON-Super-Speed-Kabel-Stecker/dp/B00WHZ746E/ref=sr_1_3?ie=UTF8&qid=1531928442&sr=8-3&keywords=usb+kabel+male+to+male) angeschlossen werden

![USB-Kabel-AA](/assets/img/USB-Kabel-AA.jpg)

 
## Empfänger (LR01) - Firmware neu installieren

### Repair Tool herunterladen 

* Laden Sie das [QuattroPod-Empfänger (LR01) Repair Tool](https://download.stueber.de/doc/de/quattropod/repair_tools/QuattroPod.LR01.Repair.Tool.zip) herunter.

* Extrahieren Sie die Datei **QuattroPod.LR01.Repair.Tool.zip**.

![Empfänger Repair Tool extrahieren](/assets/img/LR01.Repair_Tool_Extract.png) 

* Installieren Sie **die Treiber**, indem Sie die Batchdatei **QuattroPod.LR01.Repair.Tool\usb_driver\install.bat** als Administrator ausführen. 

![install.bat als Administrator ausführen](/assets/img/LR01.install.bat.png) 

* Wenn die folgende Sicherheitsmeldung erscheint, wählen Sie `Installieren`:

![Klicken Sie auf Installieren, um die Treiber zu installieren](/assets/img/install_drivers.jpg)

### Empfänger in den **Update-Modus** versetzen

Um den Empfänger in den **Update-Modus** zu versetzen, führen Sie bitte die folgenden Schritte der Reihe nach aus:

* Schalten Sie das Gerät per die Power-Taste aus
* Mit Hilfe eines kleinen "Stifts" halten Sie den Reset-Schalter gedrückt
* Schalten Sie das Gerät per die Power-Taste ein
* Lassen Sie anschließend den Reset-Schalter los

![Empfänger in den Update-Modus versetzen](/assets/img/QuattroPod_press_reset_lite.png)

* Schließen Sie nun das [USB-Kabel (A/A)](https://www.amazon.de/deleyCON-Super-Speed-Kabel-Stecker/dp/B00WHZ746E/ref=sr_1_3?ie=UTF8&qid=1531928442&sr=8-3&keywords=usb+kabel+male+to+male) an den USB-Port des Empfängers und an einen USB-Port Ihres Rechners unter Microsoft Windows an.

![Empfänger mit Ihrem PC per USB-Kabel (A/A) anschließen](/assets/img/RX_Touch-USB-cable_lite.png)

Wenn der Treiber richtig installiert ist und der Empfänger angeschlossen ist, sollte das Gerät **Realtek generic USB Device** im Geräte-Manager erscheinen. Wenn nicht, überprüfen Sie die Treiber-Installation, Kabel-Konfiguration, und den Update-Modus, wie im vorherigen Schritt beschrieben.

!["Realtek generic USB Device“ erscheint im Geräte-Manager](/assets/img/device_manager.jpg)

### Neueste Firmware installieren {#LR01_install_latest_fw}

* Im Ordner `QuattroPod.TR01.Repair.Tool` führen Sie die Datei **EZCastUpdate.exe** aus.
 
![EZCastUpdate.exe ausführen](/assets/img/LR01.Repair_Tool_Update.exe.png)

Das folgende Fenster erscheint. Wenn der QuattroPod-Empfänger erfolgreich im Update-Modus ist, wird im Tool der Status `Device connected`  angezeigt:

* Wählen Sie `Download`, um die neueste Firmware herunterzuladen.
 
![Die Schaltfläche Download wählen](/assets/img/EZCastUpdate.DeviceConnected.jpg)
 
Das Downloaden der Firmware wird durchgeführt:

!!! tip "Hinweis"

     Sie dürfen den Strom während der Aktualisierung nicht unterbrechen.
	 
![QuattroPod Firmware wird heruntergefahren](/assets/img/EZCastUpdate.Firmware.Downloading.jpg)

* Um die Installation der Firmware zu starten, wählen Sie `Upgrade`:

![Wählen Sie Upgrade, um die Installation zu starten](/assets/img/EZCastUpdate.Upgrade.jpg)

Die Firmware wird installiert:

![Die Firmware wird installiert](/assets/img/EZCastUpdate.Firmware.Updating.jpg)

Am Ende der Aktualisierung wird der Status **Upgrade Success** angezeigt:

* Sie können das USB-Kabel nun herausziehen und den Empfänger neustarten, indem Sie ihn über die Power-Taste aus- und einschalten.

![Die Installation war erfolgreich](/assets/img/EZCastUpdate_Upgrade.Success.jpg)

Schalten Sie den Empfänger aus und wieder ein. Der Empfänger ist wieder einsatzbereit.

## Sender (LT01) - Firmware neu installieren

### Repair Tool herunterladen

* Laden Sie das [QuattroPod Lite Sender (LT01) Repair Tool](https://download.stueber.de/doc/de/quattropod/repair_tools/QuattroPod.LT01.Repair.Tool.zip) herunter.

* Extrahieren Sie die Datei **QuattroPod.LT01.Repair.Tool.zip**.

![Sender Repair Tool extrahieren](/assets/img/LT01.Repair_Tool_Extract.png)

* Installieren Sie **die Treiber**, indem Sie die Batchdatei **QuattroPod.LT01.Repair.Tool\usb_driver\install.bat** als Administrator ausführen. 

![install.bat als Administrator ausführen](/assets/img/LT01.install.bat.png) 

* Wenn die folgende Sicherheitsmeldung erscheint, wählen Sie `Installieren`:

![Klicken Sie auf Installieren, um die Treiber zu installieren](/assets/img/install_drivers.jpg)

### Sender in den **Update-Modus** versetzen 

* Entfernen Sie die Antenne vom Sender:

![Sender in den Update-Modus versetzen](/assets/img/QP.lite.remove.antenna.png) 

* Um den Sender in den **Update-Modus** zu versetzen, lösen Sie die Rückseite mit einem Öffnungswerkzeug:

![Sender in den Update-Modus versetzen](/assets/img/QP.lite.open.tx.png) 

* Entfernen Sie die 5 Schrauben für das Mainboard:

![Sender in den Update-Modus versetzen](/assets/img/QP.lite.remove.screws.png)

* Entfernen Sie das Mainboard vorsichtig aus dem Gehäuse und schließen Sie das Micro-USB-Kabel an:

![Sender in den Update-Modus versetzen](/assets/img/QP.lite.connect.usb.png) 

* Mithilfe einer Pinzette halten Sie gedrückt Pin 5 und Pin 6 auf dem mainboard:

![Sender in den Update-Modus versetzen](/assets/img/QP.lite.pin5.-6.a.png) 

![Sender in den Update-Modus versetzen](/assets/img/QP.lite.pin5.-6.b.png) 

* Schließen Sie das USB-Kabel an einen USB-Port Ihres Rechners an. Nach einer Sekunde können Sie die Pinzette vom Mainboard des Senders loslassen.

![Sender in den Update-Modus versetzen](/assets/img/QP.lite.TX.connect.USB.png) 

### Neueste Firmware installieren  {#LT01_install_latest_fw}

* Im Ordner `QuattroPod.LT01.Repair.Tool` führen Sie die Datei **EZCastUpdate.exe** aus.
 
![EZCastUpdate.exe ausführen](/assets/img/LT01.Repair_Tool_Update.exe.png)

Das folgende Fenster erscheint. Wenn der QuattroPod-Empfänger erfolgreich im Update-Modus ist, wird im Tool der Status `Device connected`  angezeigt:

* Wählen Sie `Download`, um die neueste Firmware herunterzuladen.
 
![Die Schaltfläche Download wählen](/assets/img/EZCastUpdate.DeviceConnected.jpg)
 
Das Downloaden der Firmware wird durchgeführt:

!!! tip "Hinweis"

    Sie dürfen den Strom während der Aktualisierung nicht unterbrechen.

![QuattroPod Firmware wird heruntergefahren](/assets/img/EZCastUpdate.Firmware.Downloading.jpg)

* Um die Installation der Firmware zu starten, wählen Sie `Upgrade`:

![Wählen Sie Upgrade, um die Installation zu starten](/assets/img/EZCastUpdate.Upgrade.jpg)

Die Firmware wird installiert:

![Die Firmware wird installiert](/assets/img/EZCastUpdate.Firmware.Updating.jpg)

Am Ende der Aktualisierung wird der Status **Upgrade Success** angezeigt:

* Sie können das USB-Kabel nun herausziehen und den Empfänger neustarten, indem Sie ihn über die Power-Taste aus- und einschalten.

![Die Installation war erfolgreich](/assets/img/EZCastUpdate_Upgrade.Success.jpg)

Sie können nun den Sender vom Computer trennen und die Software schließen.

## Problembehandlung

### Fehlermeldung: Tool must be in a directory where there are no spaces

* Das Repair Tool muss sich in einem Dateipfad ohne Leerzeichen befinden z.B. `C:\Repair_Tool\EZCastUpdate.exe`. Um diese Fehlermeldung zu vermeiden, verschieben Sie die Software auf einen Pfad ohne Leerzeichen.

![Vermeiden Sie Leerzeichen im Daeipfad vorm Start](/assets/img/no_spaces.jpg)