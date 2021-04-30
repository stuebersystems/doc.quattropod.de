# Linux

Obwohl Linux offiziell nicht von QuattroPod unterstützt wird, stehen Ihnen folgende Möglichkeit zur Verfügung:

## Google Cast streamen

Mit dem Google Chrome-Browser können Sie die Funktion [Streamen](#linuxchromecast) verwenden:

![Übertragungsquelle](/assets/img/Linux.Chrome_select_stream2.png)

In dieser Anleitung wird erklärt, wie man unter Ubuntu 20.04 Google Chrome installiert. Der Chrome Browser kann jedoch auf vielen Distributions wie [Debian](https://www.debian.org/distrib/), [Kali](https://www.kali.org/) und [Linux Mint](https://linuxmint.com/) installiert werden.

### Google Cast auf QuattroPod freischalten

Standardmäßig ist Chromecast auf QuattroPod-Geräten aktiviert. Sollten Sie die Funktion jedoch erneut aktivieren wollen, finden Sie die entsprechende Option `Chromecast` unter [Erweiterte Einstellungen](adv.settings.md#Chromecast):

![](/assets/img/Chromecast-support.png)

### Google Chrome installieren

* Drücken Sie `STRG` + `Alt` + `T`, um ein Terminal-Fenster zu öffnen.

* Paketlisten aktualisieren

```
apt-get update
```

* Führen Sie anschließend folgende zwei Befehle aus:

```
$ wget https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb
$ sudo apt install ./google-chrome-stable_current_amd64.deb
```

### Aus dem Chrome-Browser Streamen {#linuxchromecast}

* Suchen Sie Google Chrome und führen Sie ihn aus:

![](/assets/img/Linux.Launch.Chrome.png)

* Wählen Sie über die drei Punkte oben rechts den Menüpunkt `Streamen...`

![Streamen..](/assets/img/Linux.Chrome_stream.png)

Wählen Sie die gewünschte Übertragungsquelle aus:

+ `Tab streamen` - Überträgt standardmäßig nur den aktiven Tab
+ `Desktop streamen` - Überträgt den gesamten Computerbildschirm 
+ `Datei streamen` - Bietet beste Leistung zum Video abspielen

![Übertragungsquelle](/assets/img/Linux.Chrome_select_stream2.png)

Um die Übertragung zu starten, wählen Sie einfach den gewünschten Empfänger aus.

![Übertragung starten](/assets/img/Linux.Chrome_start_stream.png)

Um die Übertragung zu beenden, klicken Sie nochmal auf den Empfänger.

![Übertragung beenden](/assets/img/end_stream.png)

Per Rechtsklick kann man Streamen-Symbol an die Symbolleiste anheften:

![Streamen-Symbol immer zeigen](/assets/img/Linux.Chrome.Always_show_icon.png)
