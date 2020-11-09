<a href="https://github.com/danielhauchler/start-coding"><< Inhaltsverzeichnis </a> | <a href="https://github.com/danielhauchler/start-coding/tree/master/03-css"> 03 - Cascading Style Sheets >></a>

## 01 - Entwicklungsumgebung

### IDEs (Integrated Development Environments)

Die [IDE (integrierte Entwicklungsumgebung)](https://de.wikipedia.org/wiki/Integrierte_Entwicklungsumgebung/) sammelt unter einer gemeinsamen Oberfläche die wichtigsten Tools für das Erstellen von Software, wie z.B. [Quelltextformatierung](https://de.wikipedia.org/wiki/Quelltextformatierung), [Syntaxhervorhebung](https://de.wikipedia.org/wiki/Syntaxhervorhebung), [Compiler](https://de.wikipedia.org/wiki/Compiler), [Debugger](https://de.wikipedia.org/wiki/Debugger), [Interpreter](https://de.wikipedia.org/wiki/Interpreter), [Versionskontrolle](https://git-scm.com/book/de/v1/Los-geht%E2%80%99s-Wozu-Versionskontrolle%3F) und Werkzeuge für das Erstellen von grafischen Oberflächen.

Es gibt viele gute IDEs, die Wahl der Richtigen hängt von eurem Technologie Stack ab. Als Web Entwickler konzetriere ich mich in unseren Start Coding Sessions auf HTML, CSS, JavaScript, Node, PHP, SQL, Git und beliebige Task Runner.
- [Sublime Text](https://www.sublimetext.com/)
- [Adobe Edge Code](http://www.adobe.com/de/products/edge-code.html)
- [Brackets](http://brackets.io/)
- [WebStorm](https://www.jetbrains.com/webstorm/)
- [PhpStorm](https://www.jetbrains.com/phpstorm/)
- [Netbeans](https://netbeans.org/)

... sind alles mächtige IDEs!
Für unsere Zwecke empfehle ich im Augenblick den Visual Studio Code von Microsoft.
- [Visual Studio Code](https://code.visualstudio.com/)

Schaut euch Emmet an, ein Plugin für viele gängige Texteditoren, welches den HTML- und CSS-Workflow erheblich verbessert! - in Visual Studio Code schon standardmäßig implementiert.
- [Emmet.io](https://emmet.io/)
- [Emmet Docs](https://docs.emmet.io/)

<br>

### Terminal (Command Line Interface)

Der Terminal, auch als Kommandozeile oder "Command Line Interface" bekannt, liefert uns eine Befehlszeilenschnittstelle und textbasierten Zugriff auf unser Betriebssystem.
![Terminal](https://raw.githubusercontent.com/danielhauchler/start-coding/master/99_assets/media/images/readme/terminal.png)

Grundlegende Betriebssystem basierte Kommandozeilen-Befehle:
- [Terminal Cheatsheet for Mac (Basics)](https://github.com/danielhauchler/terminal-mac-cheatsheet)

Und noch ein nützliches Plugin Bundle und Theme für den Terminal:
- [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh)

Auch unsere IDE, der Visual Studio Code verfügt über eine integrierte IDE.
Öffnen könnt ihr sie entweder über das Menü 'Anzeigen' > 'Integriertes Terminal' oder mit dem Shortcut:
````
Shift + control + `
````
![VSC Terminal](https://raw.githubusercontent.com/danielhauchler/start-coding/master/99_assets/media/images/readme/vsc-terminal.png)

<br>

### Git

Open-Source Software zur verteilten Versionsverwaltung, stetiger Protokollierung von Änderungen eurer Dateien/Projekte innerhalb eines Repositorys. Vor allem in der Programmierung dient es dazu die eigenen Änderungen zu überwachen, sie rückgängig zu machen, sie anderen über sogenannte Repos zur Verfügung zu stellen oder Aktualisierungen von anderen einzuholen.

- Die eigene Arbeit kann einfach wieder in die zentrale Basis integriert werden.
- Es kann zeitgleich weiterentwickelt werden, z.B. jeder an verschiedenen Features.
- Die Versionierung verhindert, dass bereits getätigte Arbeiten verloren gehen bzw. überschrieben werden.
- Bei Bedarf kann zu früheren Versionen zurückgekehrt werden oder simultan an verschiedenen Versionen gearbeitet werden (auch "Branches" genannt).

Im übrigen befindest Du dich gerade auch in einem meiner Ropositorys auf [Github](https://github.com/). Hier aktualisiere, versioniere und teile ich den aktuellen Stand unseres Quellcodes aus den Sessions, sowie diese Doku.

Für die Nutzung muss folgende Software auf eurem Betriebssystem installiert sein:
- [Git](https://git-scm.com/), Download für [Windows](https://git-scm.com/download/win) oder [Mac](https://git-scm.com/download/mac).

Folgende Online-Dienste bieten sich zur webbasierten Versionsverwaltung an:

- [GitHub](https://github.com/) (nur kostenfreie "public" Repositorys) 
- [Bitbucket von Atlassian](https://bitbucket.org/) (kostenfreie "privat" und "public" Repositorys)

Auch Git lässt sich mit [Komandozeilen-Befehle über den Terminal](https://rogerdudler.github.io/git-guide/index.de.html) steuern. Darüber hinaus gibt es Git Clients wie z.B. [Sourcetree](https://www.sourcetreeapp.com/) oder auch [Tower](https://www.git-tower.com/mac/). Unser Visual Studio Code verfügt bereits auch über einen rudimentären Git Client.

![VSC Git Client](https://raw.githubusercontent.com/danielhauchler/start-coding/master/99_assets/media/images/readme/vsc-git-client.png)

<br>

### Webbrowser

Webbrowser stellen die Benutzeroberfläche für Webanwendungen dar und sind Computerprogramme zur Visualisierung von Webseiten im World Wide Web basierend auf HTML Dokumenten, Vektor Grafiken, Bildern und PDF-Dokumenten durch Zuhilfenahme von [Cascading Stylesheets](#03---css-cascading-style-sheets) und Javascript.

- [Google Chrome](https://www.google.de/chrome/browser/desktop/index.html) (WebKit / V8)
- [Mozilla Firefox](https://www.mozilla.org/de/firefox/) (Gecko)
- [Safari](https://www.apple.com/de/safari/) (WebKit)
- [Internet Explorer](https://www.microsoft.com/de-de/download/internet-explorer.aspx) (Trident)
- [Opera](http://www.opera.com/de/download) (Presto)

Folgender Artikel ist nicht nötig zu lesen oder zu verstehen! Es ist lediglich ein guter Artikel über die Funktionsweise von Browsern. [Hinter den Kulissen moderner Web-Browser.](https://www.html5rocks.com/de/tutorials/internals/howbrowserswork/)

Keep calm and [browse happy!](https://browsehappy.com/) ;)

<br>

### Dev Tools

Mit den Developer Tools können wir unseren Code testen und debuggen. Wir können im Browser unser erzeugtes HTML, CSS, das DOM ([Document Object Model](https://github.com/danielhauchler/start-coding#document-object-model)), sowie JavaScript und andere Komponenten anfassen, die vom Webbrowser verarbeitet werden. 

Solche Web-Entwicklungstools unterscheiden sich von den Website-Buildern und den IDEs dadurch, dass sie nicht zur direkten Erstellung einer Webseite verwendet werden, sondern sie Werkzeuge zum Testen der Benutzeroberfläche einer Website oder einer Webanwendung sind. Die gängigsten Webbrowser wie Google Chrome, Firefox, Opera, Internet Explorer und Safari verfügen über integrierte Tools für Webentwickler. 

'Rechtsklick' + 'Untersuchen/Inspect' oder auch:
```
cmd + shift + I
```

![Screenshot - Inspect Element](https://raw.githubusercontent.com/danielhauchler/start-coding/master/99_assets/media/images/readme/devtools.png)

[Paul Irish](https://www.paulirish.com/), amerikanischer Front End und Google Chrome Web Browser Engineer.

<br>

### W3C

[Tim Berners-Lee](https://www.w3.org/People/Berners-Lee/) ist Wegbereiter des World Wide Webs und zudem Gründer und Vorsitzender des World Wide Web Consortiums ([W3C](https://www.w3.org/)).

Das World Wide Web Consortium ist ein Gremium zur Standardisierung von Techniken im World Wide Web. Es entwickelt technische Spezifikationen und Richtlinien in einem ausgereiften, transparenten Prozess, um maximalen Konsens über den Inhalt technischer Protokolle, sowie eine hohe technische und redaktionelle Qualität zu erzielen.

- [World Wide Web Consortium (W3C)](https://www.w3.org/)
- [World Wide Web Consortium (W3Schools)](https://www.w3schools.com/)

Das W3C stellt einen Markup Validator zur Überprüfung von Markup-Gültigkeit von Web-Dokumenten in HTML, XHTML, SMIL, MathML usw. zur Verfügung. Wenn ihr also euer erzeugtes Markup auf Gültigkeit überprüfen wollt, könnt ihr folgenden Validator nutzen:
- [W3C Validator](https://validator.w3.org/)

<br>

<a href="https://github.com/danielhauchler/start-coding"><< Inhaltsverzeichnis </a> | <a href="https://github.com/danielhauchler/start-coding/tree/master/03-css"> 03 - Cascading Style Sheets >></a>
