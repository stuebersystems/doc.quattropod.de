# Datensicherheit

Die Sender und Empfänger des QuattroPods benutzen den Drahtlostandard **5 Ghz (802.11ac)** und das Authentifizierungsprotokoll **WPA2-PSK (AES)** zur Verschlüsselung von Daten über WLAN.

Der Empfänger sorgt für weitere Sicherheit der Daten bei der Beschränkung von Diensten auf nur einen eingebetteten **Web-Server (lighttpd)** und den **QuattroPod Softwaredienst**. Änderungen, die am Empfänger vom Benutzer über den Web-Server vorgenommen werden, werden in einem nichtflüchtigen NAND-Flash dauerhaft gespeichert.