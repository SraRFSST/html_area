# 4 Site Veröffentlichen

um eine HTML-Seite öffentlich zugänglich zu machen benötigt man einen Zugang zu einem WebServer. Dieser Zugang ist üblicherweise kostenpflichtig, es gibt jedoch viele freie Möglichkeiten.

## GitHub

GitHub ist ein (Microsoft) Portal für das verteilte Arbeiten mit Software. Um eine Seite hier zu veröffentlichen:

- Erstellen eines Profiles 

- Erstellen eines Repositories (kann man sich als ein Projekt vorstellen) (hier `html_area`)

- In diesem Projekt kann man `Settings`->`Pages`->`Branch`=main einstellen und eventuell ein Unterverzeichnis, welches zur Verfügung gestellt werden soll. Etwa `/docs`

- Auf der Seite wird direkt wenn diese Einstellung getroffen wurde unter `Custom domain` eine Domänenbezeichnung eingeblendet, hier `srarfsst.github.io`. Die Site kann damit mit

  https://srarfsst.github.io/html_area/

  erreicht werden

- Im Repository muss das Unterverzeichnis das oben eingestellt `/docs` wurde abgelegt werden.

- In diesem Unterverzeichnis können html-Dokumente abgelegt (z.B. `demo.html`) werden auf die nun zugegriffen werden kann:

  https://srarfsst.github.io/html_area/demo.html

## QR-Code

für diesen Link kann auch ein QR-Code erzeugt werden. Im Web gibts viele Online-Tools die das machen. Zum Beispiel:
https://qrcode.tec-it.com/de/Url

damit wurde der Code für die oben erwähnte Seite https://srarfsst.github.io/html_area/demo.html erzeugt:
![qr-code](./img/html_bsp_qrcode.png)