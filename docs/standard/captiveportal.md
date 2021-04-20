## Was ist Captive Portal?

Ein Captive Portal präsentiert dem Benutzer eine Anmeldeseite, die sich nach der Erstverbindung mit dem WLAN automatisch öffnet. Er muss die Nutzungsbedingungen akzeptieren, bevor er auf das WLAN-Netzwerk der Schule bzw. des Unternehmens zugreifen darf. In manchen Fällen kann das Captive Portal einen Benutzernamen und ein Kennwort erfordern. Die Verwendung eines Captive Portals gibt einer Schule bzw. einem Hotel erhöhte Kontrolle über ihre Bandbreite und bietet gleichzeitig individuell anpassbare Grenzen dafür, wie lange Benutzer mit Ihrem Netzwerk verbunden bleiben können.

![Captive Portal im Einsatz in einer Schule](/assets/img/captiveportal.login.png)

## Kann der QuattroPod sich in einem Captive Portal anmelden?

Da ein Captive Portal ein manuelles Eingeben der Zugangsdaten benötigt, kann der QuattroPod sich nicht in einem Captive Portal anmelden. Jedoch, es ist möglich den QuattroPod in Ihre Infrastruktur zu integrieren, in dem Sie eine `MAC-Authentifizierung` als eine Ausnahme auf Ihrem Router bzw. auf Ihrer Firewall erstellen, damit dieser Schritt entfällt.

* Die MAC-Adresse des QuattroPods ist im Rubrik `Über das Gerät` in den [Erweiterten Einstellungen](adv.settings.md) zu finden:

![MAC-Adresse im Rubrik Über](/assets/img/D10.About.MAC.jpg)

Eine MAC-Adresse ist die bessere Wahl als die Verwendung einer IP-Adresse, da sich die MAC-Adresse nicht ändert. 

* Bitte wenden Sie sich an Ihre IT-Abteilung, um die MAC-Adresse des QuattroPods zuzulassen.
