
<p align="center"><img src="http://www.z-icon.com/assets/images/z-icon-logo.svg" width=128px height=auto></p>

# z-Icons

Die Premium-Icon-Schrift für [PhpSQLiteCMS](https://github.com/ztatement/phpsqlitecms/). Entworfen von [@ztatement](https://twitter.com/ztatement).

> **Hinweis:** Alle Markenzeichen sind Warenzeichen der jeweiligen Eigentümer. Die Verwendung dieser Marken bedeutet nicht, dass der Inhaber des Markeninhabers von ztatement bestätigt wird, und nicht umgekehrt.

Besuchen Sie [z-icon.com](http://www.z-icon.com/) und schauen Sie sich die Suchfunktion an, die Schlüsselwörter identifiziert gemeinsamen Symbol Namen und Stile. Wenn Sie beispielsweise nach "Pfeil" suchen, rufen wir jedes Symbol auf, das als Pfeil verwendet werden könnte. Wir haben auch die Icon Klassenname für einfaches kopieren/einfügen, wenn Sie entwickeln!

Wir beabsichtigen, dieses Icon Pack mit [phpSQLiteCMS](http://demo-seite.com/path/to/phpsqlitecms/) zu verwenden, aber es ist keineswegs darauf beschränkt. Verwenden Sie es, wo immer Sie mögen, passen Sie es an, persönlich oder kommerziell. Sie sind frei es zu benutzen, lizenziert unter [MIT](http://opensource.org/licenses/MIT).


## Anfangen

1. Laden Sie das Font-Pack herunter und extrahieren Sie es
2. Kopieren Sie die `z-icons.css` in Ihr Projekt
3. Kopieren Sie den Ordner "Fonts" in Ihr Projekt
4. Stellen Sie sicher, dass die Font-URLs in `z-icons.css` korrekt auf den` fonts'-Pfad in Ihrem Projekt verweisen.
5. Fügen Sie einen Verweis auf die `z-icons.css` Datei in jeder Webseite, die Sie verwenden müssen.

    
vielleicht ist ihnen [bower](http://bower.io/) bekannt?
installieren Sie es mit
   
    $ bower install ionicons

um es zu verwenden.



## HTML Beispiel

Sie können auf [z-icon.com](http://www.z-icon.com/) einfach auf das Symbol klicken, das Sie verwenden möchten. Sobald Sie den CSS-Klassennamen des gewünschten Symbols kopiert haben, fügen Sie einfach das Symbol `icon` und das Symbol des Icons wie` z-home` einem HTML-Element hinzu.

    <i class="icon z-home"></i>
  besser

    <span class="icon z-home"></span>



## Build Anleitung

Dieses Repo kommt bereits mit allen kompilierten Dateien und bereit zur Verwendung, kann aber auch die Schriften aus der Quelle benutzen. Benötigt Python, FontForge und Sass:

1. Installieren Sie FontForge, das ist das Programm, das die Font-Dateien aus den SVG-Dateien erstellt:

    $ brew install fontforge ttfautohint

2. Installieren Sie [Sass](http://sass-lang.com/)

    $ gem install sass

3. Fügen Sie Dateien hinzu oder entfernen sie aus dem Ordner `src/`, die Sie von den Font-Dateien abheben möchten.

4. Ändern Sie alle Einstellungen in der Datei `builder/manifest.json`. Sie können den Namen der Schriftfamilie und den CSS-Klassennamen ändern.

5. Führen Sie den Befehl build aus:

    python ./builder/generate.py



## License

z-icons ist lizenziert unter der [<img src="http://www.z-icon.com/assets/images/mit.svg" width=24px height=auto> license](https://opensource.org/licenses/MIT).
