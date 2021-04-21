# Anschlüsse, die von QuattroPod verwendet werden

In der folgenden Tabelle sind die von QuattroPod verwendeten Anschlüsse aufgeführt. 

## Verwendete Anschlüsse

### AirPlay

Port | Typ                  
:---- | :----------------------
7000 | TCP          
7001 | TCP         
7100 | TCP         
5353 | UDP         

### QuattroPod Sender / Empfänger

| Port |
| :---- |
| 2425 |
| 63630 |

### ChromeCast

| Port | Typ
| :---- | :---
| 80 | TCP
| 443 | TCP
| 8008 | TCP
| 8009 | TCP
| 53 | UDP
| 1900 | UDP
| 5353 | UDP

### HTTP Web-Server für die Web-Oberfläche 

| Port |
| :---- |
| 80 |
| 8080 |

### Over-The-Air Firmware

| Port |
| :---- |
| 80 |
| 443 |


## QuattroPod verwendete Anschlüsse untersuchen

Haben Sie festgestellt, dass bestimmte Funktionen von QuattroPod über Ihre Infrastruktur nicht funktionieren? Microsoft stellt eine grafische Benutzeroberfläche des Tools namens PortQueryUI bereit, die zur Fehlersuche in solchen Szenarien mit Port-Konnektivitätsproblemen verwendet werden kann. Dieses Tool können Sie zur Behebung von TCP/IP-Verbindungsproblemen verwenden. Das Hilfsprogramm meldet den Portstatus von TCP- und UDP-Ports auf einem Gerät, das Sie auswählen.

### PortQueryUI.exe herunterladen

* Laden Sie das Tool [portqueryui.exe](https://download.microsoft.com/download/3/f/4/3f4c6a54-65f0-4164-bdec-a3411ba24d3a/portqryui.exe) herunter und führen Sie es aus. Zum Akzeptieren der Lizenzvereinbarung klicken Sie auf `Yes`:

![Lizenzvereinbarung akzeptieren](/assets/img/PortQueryUI-License-Agreement.png)

* Extrahieren Sie die Dateien im gewünschten Ordner:

![die Dateien extrahieren](/assets/img/PortQryUI_extract.png)
 
* Die `PortQueryUI.exe` muss nicht installiert werden, sondern kann einfach per Doppelklick gestartet werden:

![PortQueryUI.exe per Doppelklick starten](/assets/img/portqueryui.exe.png)

### Ports abfragen

* Notieren Sie sich die Infrastruktur IP-Adresse, die unten links auf der Startseite angezeigt wird:

![Infrastruktur IP-Adresse notieren](/assets/img/QuattroPod_IP.png)

Im Feld `destination IP` geben Sie die Infrastruktur IP-Adresse ein. Geben Sie anschließend die zu prüfenden Ports an und klicken Sie auf `Query`, wie zum Beispiel:

Für die Funktion `ChromeCast`:

* `Ports to query` = **80,443,8008,8009**
* `Protocol` = **TCP**

![Ports angeben](/assets/img/TCP.png)

### Weitere Informationen

PortQueryUI.exe meldet den Status eines TCP/IP-Ports auf eine der folgenden drei Arten:

`LISTENING` - Abhören

Der Port auf dem ausgewählten QuattroPod Gerät wird von einem Prozess abgehört. PortQueryUI.exe hat eine Antwort vom Port erhalten.

`NOT LISTENING` - Nicht abhören

Der Zielport auf dem QuattroPod Gerät wird nicht von einem Prozess abgehört. Überprüfen Sie bitte Ihre Infrastruktur, um Netzwerkverbindungen für den Port zu erlauben.

`Filtered`

Der Port auf dem ausgewählten QuattroPod Gerät wird gefiltert. PortQueryUI.exe hat keine Antwort vom Port erhalten. Ein Prozess hört den Port möglicherweise ab oder nicht. Standardmäßig werden die TCP-Ports dreimal abgefragt, und die UDP-Ports werden einmal abgefragt, bevor ein Bericht angibt, dass der Port gefiltert wird.

![Abfrage Ergebnisse](/assets/img/TCP.results.png)

