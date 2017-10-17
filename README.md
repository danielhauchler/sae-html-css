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

## 01 - IDE (Integrated Development Environment)

Die [IDE (integrierte Entwicklungsumgebung)](https://de.wikipedia.org/wiki/Integrierte_Entwicklungsumgebung/) sammelt unter einer gemeinsamen Oberfläche die wichtigsten Tools für das Erstellen von Software. Z.B. [Quelltextformatierung](https://de.wikipedia.org/wiki/Quelltextformatierung), [Syntaxhervorhebung](https://de.wikipedia.org/wiki/Syntaxhervorhebung), [Compiler](https://de.wikipedia.org/wiki/Compiler), [Debugger](https://de.wikipedia.org/wiki/Debugger), [Interpreter](https://de.wikipedia.org/wiki/Interpreter), Werkzeuge für das Erstellen von grafischen Oberflächen, [Versionskontrolle](https://git-scm.com/book/de/v1/Los-geht%E2%80%99s-Wozu-Versionskontrolle%3F) und weitere.

Es gibt viel gute IDEs, die Wahl der Richtigen hängt von eurem Technologie Stack ab. Als Web Entwickler konzetrieren wir uns auf HTML, CSS, JavaScript, Node, PHP, SQL, Python, Git und beliebige Task Runner.
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

<br>

### Terminal (Command Line Interface)

Der Terminal, auch die Kommandozeile "Command Line" liefert uns eine Befehlszeilenschnittstelle und textbasierten Zugriff auf das Betriebssystem.

![Terminal](https://raw.githubusercontent.com/danielhauchler/start-coding/master/_assets/media/images/readme/terminal.png)

Rudimentäre Befehle im Terminal.
- [Terminal Cheatsheet for Mac (Basics)](https://github.com/danielhauchler/terminal-mac-cheatsheet)

Ein nützliches Plugin Bundle und Theme für den Terminal.
- [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh)

<br>

#### Command Line Tools
Freie Software zur Versionsverwaltung von publiken und privaten Dateien/Projekten innerhalb eines Repositoriums.

- [Git](https://git-scm.com/)

Webbasierter Online-Versionsverwaltung

- [GitHub](https://github.com/)
- [Bitbucket von Atlassian](https://bitbucket.org/)


<br>

## 02 - Webbrowser

Ein Computerprogramm zur Visualisierung von HTML Dokumenten, Vektor Grafiken, Bildern und PDF-Dokumenten durch Zuhilfenahme von Cascading Stylesheets.<br>
[Browse Happy!](https://browsehappy.com/)

- [Google Chrome](https://www.google.de/chrome/browser/desktop/index.html) (WebKit / V8)
- [Mozilla Firefox](https://www.mozilla.org/de/firefox/) (Gecko)
- [Safari](https://www.apple.com/de/safari/) (WebKit)
- [Internet Explorer](https://www.microsoft.com/de-de/download/internet-explorer.aspx) (Trident)
- [Opera](http://www.opera.com/de/download) (Presto)

Funktionsweisen von Browsern: [Hinter den Kulissen moderner Web-Browser.](https://www.html5rocks.com/de/tutorials/internals/howbrowserswork/)

<br>

### Dev Tools
Google Chrome Developer Tools zum debuggen von Web Applikationen.

'Rechtsklick' + 'Untersuchen/Inspect'

```
cmd + shift + I
```

![Screenshot - Inspect Element](https://raw.githubusercontent.com/danielhauchler/start-coding/master/_assets/media/images/readme/devtools.png)

[Paul Irish](https://www.paulirish.com/), amerikanischer Front End und Google Chrome Web Browser Engineer.

<br>

## 03 - HTML

- HTML (Hypertext Markup Language)
- HTML beschreibt die semantische Dokumentenstruktur von Webapplikationen
- HTML Tags repräsentieren HTML Elemente
- Browser nutzen HTML Tags um Inhalte zu rendern.

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

[__Doctype Sourcecode__](https://github.com/danielhauchler/start-coding/blob/master/01-html/doctype/doctype.html)

### <HEAD>
Das Head Element ist ein Container für Metadaten. Metadaten beinhalten Informationen über das HTML Dokument wie z.B. 'character sets', 'styles', 'links', 'scripts'...

````
<head>
  <meta charset="UTF-8">
  <title>Der einzigartige Titel</title>
  <meta charset="utf-8">
  <meta name="description" content="Die einzigartige Beschreibung">
</head>
````
- [HTML Elemente für den Head.](https://github.com/danielhauchler/HEAD)

##### Unicodes and Character Sets
```
<meta charset="utf-8">
```
[The minimum every software developer must know about unicodes and character sets.](https://www.joelonsoftware.com/2003/10/08/the-absolute-minimum-every-software-developer-absolutely-positively-must-know-about-unicode-and-character-sets-no-excuses/)

### <BODY>
Der Body definiert Inhalte von HTML Dokumenten wie Überschriften, Text, Hyperlinks, Bilder, Listen und Tabellen.
- [Lister HTML5 Elemente](https://developer.mozilla.org/de/docs/Web/HTML/HTML5/HTML5_element_list)

[Doctype Sourcecode](https://github.com/danielhauchler/start-coding/blob/master/01-html/html-tags/html-tags.html)

<br>

## 04 - CSS
 CSS ist eine Stylesheet-Sprache für elektronische Dokumente und zusammen mit HTML und DOM eine der Kernsprachen des World Wide Webs. Mit CSS werden Gestaltungsanweisungen erstellt, die vor allem zusammen mit den Auszeichnungssprachen HTML und XML eingesetzt werden.

- [Can i use?](https://caniuse.com/])

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
