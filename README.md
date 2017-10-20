![Start Coding](https://raw.githubusercontent.com/danielhauchler/start-coding/master/_assets/media/images/readme/start-coding-banner.jpg)

<br>

**Termine:**

2017

> **12.10.** // Kick-Off, IDE, Terminal, Browser, HTML

> **17.10** // Chrome DevTools, HTML, CSS

> **25.10.** // Chrome DevTools, HTML, CSS

<br>

- [Roadmap to become a web developer in 2017](https://github.com/danielhauchler/developer-roadmap)
- [Kollaborative Notizen aus unseren Sessions](https://docs.google.com/document/d/17UVzmxNfac6yb9yI6B0vMZwanRJNC34Tepmt1gZ7-rI/edit)

<br>

## 01 - Entwicklungsumgebung

### IDEs (Integrated Development Environments)

Die [IDE (integrierte Entwicklungsumgebung)](https://de.wikipedia.org/wiki/Integrierte_Entwicklungsumgebung/) sammelt unter einer gemeinsamen Oberfläche die wichtigsten Tools für das Erstellen von Software, wie z.B. [Quelltextformatierung](https://de.wikipedia.org/wiki/Quelltextformatierung), [Syntaxhervorhebung](https://de.wikipedia.org/wiki/Syntaxhervorhebung), [Compiler](https://de.wikipedia.org/wiki/Compiler), [Debugger](https://de.wikipedia.org/wiki/Debugger), [Interpreter](https://de.wikipedia.org/wiki/Interpreter), [Versionskontrolle](https://git-scm.com/book/de/v1/Los-geht%E2%80%99s-Wozu-Versionskontrolle%3F) und Werkzeuge für das Erstellen von grafischen Oberflächen.

Es gibt viele gute IDEs, die Wahl der Richtigen hängt von eurem Technologie Stack ab. Als Web Entwickler konzetrieren wir uns auf HTML, CSS, JavaScript, Node, PHP, SQL, Python, Git und beliebige Task Runner.
- [Sublime Text](https://www.sublimetext.com/)
- [Adobe Edge Code](http://www.adobe.com/de/products/edge-code.html)
- [Brackets](http://brackets.io/)
- [WebStorm](https://www.jetbrains.com/webstorm/)
- [PhpStorm](https://www.jetbrains.com/phpstorm/)
- [Netbeans](https://netbeans.org/)

Für unsere Zwecke empfehle ich im Augenblick den Visual Studio Code von Microsoft.
- [Visual Studio Code](https://code.visualstudio.com/)

Schaut euch Emmet an, ein Plugin für viele gängige Texteditoren, welches den HTML- und CSS-Workflow erheblich verbessert!
- [Emmet.io](https://emmet.io/)
- [Emmet Docs](https://docs.emmet.io/)


### Terminal (Command Line Interface)

Der Terminal, auch die Kommandozeile "Command Line" liefert uns eine Befehlszeilenschnittstelle und textbasierten Zugriff auf das Betriebssystem.

![Terminal](https://raw.githubusercontent.com/danielhauchler/start-coding/master/_assets/media/images/readme/terminal.png)

Betriebssystem basierte Kommandozeilen-Befehle
- [Terminal Cheatsheet for Mac (Basics)](https://github.com/danielhauchler/terminal-mac-cheatsheet)

Ein nützliches Plugin Bundle und Theme für den Terminal
- [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh)


#### Command Line Tool

##### Git

Freie Software zur Versionsverwaltung von Dateien/Projekten innerhalb eines 'privat' oder 'public' Repositorys.

- [Git](https://git-scm.com/)

Online-Dienste zur webbasierter Versionsverwaltung

- [GitHub](https://github.com/)
- [Bitbucket von Atlassian](https://bitbucket.org/)


### Webbrowser

Ein Computerprogramm zur Visualisierung von HTML Dokumenten, Vektor Grafiken, Bildern und PDF-Dokumenten durch Zuhilfenahme von Cascading Stylesheets. [Browse Happy!](https://browsehappy.com/)

- [Google Chrome](https://www.google.de/chrome/browser/desktop/index.html) (WebKit / V8)
- [Mozilla Firefox](https://www.mozilla.org/de/firefox/) (Gecko)
- [Safari](https://www.apple.com/de/safari/) (WebKit)
- [Internet Explorer](https://www.microsoft.com/de-de/download/internet-explorer.aspx) (Trident)
- [Opera](http://www.opera.com/de/download) (Presto)

Funktionsweisen von Browsern: [Hinter den Kulissen moderner Web-Browser.](https://www.html5rocks.com/de/tutorials/internals/howbrowserswork/)


### Dev Tools
Google Chrome Developer Tools zum debuggen von Web Applikationen.

'Rechtsklick' + 'Untersuchen/Inspect'

```
cmd + shift + I
```

![Screenshot - Inspect Element](https://raw.githubusercontent.com/danielhauchler/start-coding/master/_assets/media/images/readme/devtools.png)

[Paul Irish](https://www.paulirish.com/), amerikanischer Front End und Google Chrome Web Browser Engineer.

<br>

## 02 - HTML (Hypertext Markup Language)

- HTML beschreibt die semantische Dokumentenstruktur von Web Applikationen
- HTML Tags repräsentieren HTML Elemente
- HTML Elemente bilden eine Baumstruktur, auch DOM (Dokumenten-Objekt-Modell) gegannt
- DOM-Elemente bildet Knoten, jeder Knoten bildet ein Objekt
- Objekte repräsentieren Teile des Dokumentes
- Browser nutzen das DOM um Inhalte zu rendern

![DOM-Knoten](https://raw.githubusercontent.com/danielhauchler/start-coding/master/_assets/media/images/readme/dom-knoten.png)

[Tim Berners-Lee](https://www.w3.org/People/Berners-Lee/), Wegbereiter des World Wide Webs und Director des World Wide Web Consortiums ([W3C](https://www.w3.org/)).

- [World Wide Web Consortium (W3C)](https://www.w3.org/)
- [World Wide Web Consortium (W3Schools)](https://www.w3schools.com/)

### DOCTYPE

Dateiname:
````
index.html
````

Mit der Dateiendung '.html' definieren wir die Datei als HTML Dokument.

````
<!DOCTYPE html>
<html>
<head>
    <title></title>
</head>
<body>
    
</body>
</html>
````

__*[Sourcecode](https://github.com/danielhauchler/start-coding/blob/master/02-html/01_doctype/index.html)*__

### HEAD
Das Head Element ist ein Container für Metadaten. Metadaten beinhalten Informationen über das HTML Dokument wie z.B. 'character sets', 'styles', 'links', 'scripts'...

- [HTML Elemente für den Head.](https://github.com/danielhauchler/HEAD)

````
<head>
  <meta charset="UTF-8">
  <title>Der einzigartige Titel</title>
  <meta name="description" content="Die einzigartige Beschreibung">
</head>
````
__*[Sourcecode](https://github.com/danielhauchler/start-coding/blob/master/02-html/02_html-head/index.html)*__

##### Unicodes and Character Sets
[Unicode](https://wiki.selfhtml.org/wiki/Referenz:HTML/Zeichenreferenz) ist ein internationaler Standard, in dem langfristig für jedes Sinn tragende Schriftzeichen oder Textelement aller bekannten Schriftkulturen und Zeichensysteme ein digitaler Code festgelegt wird. [Character Sets](https://www.w3schools.com/tags/ref_charactersets.asp) (Zeichenkodierungen) erlauben die eindeutige Zuordnung von Schriftzeichen und Symbolen innerhalb eines Zeichensatzes.

- [About unicodes and character sets.](https://www.joelonsoftware.com/2003/10/08/the-absolute-minimum-every-software-developer-absolutely-positively-must-know-about-unicode-and-character-sets-no-excuses/)

```
<meta charset="utf-8">
```

### BODY
Der Body definiert Inhalte von HTML Dokumenten wie Überschriften, Text, Hyperlinks, Bilder, Listen und Tabellen.
- [HTML5 Elemente](https://www.w3schools.com/tags/ref_byfunc.asp)

````
<body>
  <h1></h1>
  <p></p>
  <a href=""></a>      
  <img src="" title="">
  <div>
    <div></div>
  </div>
</body>
````

__*[Sourcecode](https://github.com/danielhauchler/start-coding/blob/master/02-html/03_html-body/index.html)*__

<br>

## 03 - CSS (Cascading Style Sheets)
CSS ist eine Stylesheet-Sprache für elektronische Dokumente mit der Gestaltungsanweisungen erstellt werden.

- [Can i use?](https://caniuse.com/])

### CSS Implementierung
#### Inline
#### Internal
#### External
Das ist ein Test




### Box Model
### CSS3
#### Flexbox
#### Transitions
#### Transforms / Rotate / Scale
### Responsive Web

<br>

## Nodes
Server

Preprocessors

Sass/Less

Libraries/Frameworks

Bootstrap

Terminal Usage

Javascript

Task Runner

npm

Semantic Web / SEO

HTML Head

grunt / gulp / webpack

module bundler

Version Control/Git

CMS

Tracking

URL Tracking

Event Tracking

Datenbanken

Images (png, jpg, svg)

Ad-Session

<br>

## Assets

### Colors
![Colors](https://raw.githubusercontent.com/danielhauchler/start-coding/master/_assets/media/images/readme/colors.jpg)
```
  #f6f6f6
  #99a0aa
  #4d545d
  #05b1b2
  #009899
```
