![Start Coding](https://raw.githubusercontent.com/danielhauchler/start-coding/master/_assets/media/images/readme/start-coding-banner.jpg)

<br>

**Termine:**

2017

> **12.10.** // Kick-Off, IDE, Terminal, Browser, HTML

> **17.10** // Chrome DevTools, HTML, CSS

> **25.10.** // Chrome DevTools, HTML, CSS

<br>

**Sitemap**

- [01 - Entwicklungsumgebung](01-ide#01---entwicklungsumgebung)
  - [IDEs (Integrated Development Enviroment)](#ides-integrated-development-environments)
  - [Terminal (Command Line Interface)](#terminal-command-line-interface)
  - [Git](#git)
  - [Webbrowser](#webbrowser)
  - [Dev Tools](#dev-tools)
  - [W3C](#w3c)

- [02 - HTML (Hypertext Markup Language)](#02---html-hypertext-markup-language)

<!--
## 01 - Entwicklungsumgebung
### IDEs (Integrated Development Environments)
### Terminal (Command Line Interface)
### Git
### Webbrowser
### Dev Tools
### W3C

## 02 - HTML (Hypertext Markup Language)
### Document Object Model
### DOCTYPE
### HEAD
##### Unicodes and Character Sets
### BODY

## 03 - Cascading Style Sheets
### CSS Einbindung
#### Inline Styles
#### Internal Styles
#### External Styles
### Cascading -->

<br>

- [Roadmap to become a web developer in 2017](https://github.com/danielhauchler/developer-roadmap)
- [Kollaborative Notizen aus unseren Sessions](https://docs.google.com/document/d/17UVzmxNfac6yb9yI6B0vMZwanRJNC34Tepmt1gZ7-rI/edit)

<br>

## 02 - HTML (Hypertext Markup Language)

- HTML beschreibt die semantische Dokumentenstruktur von Web Applikationen
- HTML Tags repräsentieren HTML Elemente
- HTML Elemente bilden eine Baumstruktur, auch DOM (Dokumenten-Objekt-Modell) gegannt
- DOM-Elemente bildet Knoten, jeder Knoten bildet ein Objekt
- Objekte repräsentieren Teile des Dokumentes
- Browser nutzen das DOM um Inhalte zu rendern

### Document Object Model

Das Dokumenten-Objekt-Modell ist eine Spezifikation, welche HTML- oder XML-Dokumente als eine Baumstruktur darstellt, in der jeder Knoten ein Objekt ist, welches einen Teil des Dokumentes repräsentiert, z.B. einen Absatz, eine Überschrift, ein Video oder etwa eine Tabellenzelle. Es definiert die logische Struktur von Dokumenten und die Art und Weise, wie auf ein Dokument zugegriffen wird und es manipuliert werden kann.

An diesem Beispiel lässt sich der prinzipielle Aufbau des Objektmodells diskutieren: Dokumente werden logisch wie ein Stammbaum dargestellt. Knoten (nodes) stehen über „Verwandtschaftsbeziehungen“ zueinander in Verbindung.

![DOM-Knoten](https://raw.githubusercontent.com/danielhauchler/start-coding/master/_assets/media/images/readme/dom-knoten.png)

Die vorliegende Struktur wird im Objektmodell durch die folgenden Beziehungen charakterisiert:

- Der Wurzelknoten (root) ist ein html-Tag und hat als Kinder (children) die Elementknoten head und body.
- Der html-Elementknoten ist umgekehrt ein Elternteil (parent) von head und body.
- Knoten mit gemeinsamem Elternteil (zum Beispiel die Elementknoten head und body) werden Geschwister (siblings) genannt.


### DOCTYPE

Mit der Dateiendung '.html' definieren wir Dateien als HTML Dokumente. Der Dateiname 'index' kann beliebig gewählt werden. Wenn wir jedoch später eine html-Datei auf einem Server bereitstellen, sind index-Dateien standardmäßig als Startseiten referenziert. Mit der URL https://www.start-coding.de/ würden wir den Inhalt der Datei https://www.html-seminar.de/index.html angezeigt bekommen.
````
index.html
````

Eine gewöhnliche HTML-Datei besteht grundsätzlich aus folgenden Bestandteilen:
- Dokumententyp-Deklaration (!DOCTYPE html)
- head (unsichtbarer Kopfdaten. z.B. Angaben zu Seitentitel)
- body (Körper mit anzuzeigendem Inhalt, also Texte, Hyperlinks, Bilder, Tabellen, Listen, Grafikreferenzen usw.)

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

__*[Sourcecode](https://github.com/danielhauchler/start-coding/blob/master/02-html/01-doctype/index.html)*__

### HEAD
Das head-Element ist ein Container für alle Kopfelemente und kann einen Titel für das Dokument, Skripte, Stile, Metainformationen enthalten. 
````
<head>
  <meta charset="UTF-8">
  <title>Der einzigartige Titel</title>
  <meta name="description" content="Die einzigartige Beschreibung">
</head>
````
__*[Sourcecode](https://github.com/danielhauchler/start-coding/blob/master/02-html/02-html-head/index.html)*__

Weitere html-Elemente zur Auszeichnung von Metainformationen im head findet ihr unter [HTML Elemente für den Head](https://github.com/danielhauchler/HEAD).

##### Unicodes and Character Sets
```
<meta charset="utf-8">
```
[Unicode](https://wiki.selfhtml.org/wiki/Referenz:HTML/Zeichenreferenz) ist ein internationaler Standard, in dem langfristig für jedes Sinn tragende Schriftzeichen oder Textelement aller bekannten Schriftkulturen und Zeichensysteme ein digitaler Code festgelegt wird. [Character Sets](https://www.w3schools.com/tags/ref_charactersets.asp) (Zeichenkodierungen) erlauben die eindeutige Zuordnung von Schriftzeichen und Symbolen innerhalb eines Zeichensatzes.

- [About unicodes and character sets.](https://www.joelonsoftware.com/2003/10/08/the-absolute-minimum-every-software-developer-absolutely-positively-must-know-about-unicode-and-character-sets-no-excuses/)

### BODY
Das body-Element definiert den Dokumenten-Körper und enthält alle Inhalte eines HTML-Dokumentes wie Text, Hyperlinks, Bilder, Tabellen, Listen usw.
- [HTML5 Elemente](https://www.w3schools.com/tags/ref_byfunc.asp)

````
<body>
  <h1></h1>
  <p></p>
</body>
````

__*[Sourcecode](https://github.com/danielhauchler/start-coding/blob/master/02-html/03-html-body/index.html)*__

<br>

## 03 - Cascading Style Sheets
Cascading Style Sheets (gestufte Gestaltungsbögen), kurz CSS genannt ist eine Stylesheet-Sprache für elektronische Dokumente mit der Gestaltungsanweisungen erstellt werden, die zusammen mit den Auszeichnungssprachen HTML, dem DOM und XML eingesetzt werden. Sie ist ein so genannter „living standard“ und wird vom World Wide Web Consortium (W3C) stetig weiterentwickelt. CSS wurde entworfen, um Darstellungen weitestgehend von inhaltlicher Semantik zu trennen. Ob und in welchen Browserversionen welche CSS Properties implementiert sind könnt ihr unter [https://caniuse.com/](https://caniuse.com/]) prüfen.

Ein CSS-Regel-Set besteht aus einem Selektor und einem Deklarationsblock mit CSS Eigenschaften und Werten.

Der Selektor zeigt auf das HTML-Element, das Du formatieren möchten. Der Deklarationsblock enthält eine oder mehrere Deklarationen, die durch Semikolons voneinander getrennt werden. Jede Deklaration enthält einen CSS-Eigenschaftsnamen und einen durch einen Doppelpunkt getrennten Wert. Eine CSS-Deklaration endet immer mit einem Semikolon, und Deklarationsblöcke werden von geschweiften Klammern umgeben.

![CSS Selektoren und Eigenschaften](https://raw.githubusercontent.com/danielhauchler/start-coding/master/_assets/media/images/readme/css.png)

### CSS Einbindung
Es gibt verschiedene Wege CSS zu implementieren:

- **Inline Styles** - innerhalb von HTML-Elementen (abweichende Formatierung!)
- **Internal Styles** - im Head des HTML-Dokumentes
- **External Styles** - ausgelagertes Stylesheet in externer CSS-Datei

#### Inline Styles
Inline-Styles sind an ein Element gebunden und können nicht an zentraler Stelle bearbeitet werden. Die Formatdefinition gilt dann nur für den Geltungsbereich des betreffenden HTML-Elements. Innerhalb eines einleitenden HTML-Elements wird das globale Attribut style verwendet. Die Wertzuweisung an das style-Attribut besteht in einer oder mehreren CSS-Formatdefinitionen.
````
  <HTML-Tag style="Formatdefinition-01, Formatdefinition-02"></HTML-Tag>
````
Sinnvoll ist die Verwendung von Inline-Styles, wenn Du sonst auf CSS verzichten möchtest und es nur mal für ein paar Ausnahmen benötigst, oder wenn Du zentrale Formate verwendest, einzelne Elemente aber ausnahmsweise anders gestalten möchtest. Darüber hinaus ist das Injekten von Inline-Styles per Javascript üblich, weiteres hierzu später.

Grundsätzlich solltest du die Verwendung von „Inline-Styles“ meiden, da du keine globalen Änderungen mehr vornehmen kannst und es den Wartungsaufwand erhöht.

Beispiel:
````
<h1 style="color:white;background-color:black">Eine Überschrift</h1>
````
Inline-Styles angewendet auf eine Überschrift ersten Grades in Weiß auf schwarzem Hintergrund.


#### Internal Styles
Hier sind die CSS-Anweisungen im Kopfbereich (Head) des HTML-Dokumentes platziert und haben Auswirkungen auf das gesamte HTML-Dokument.
````
<!DOCTYPE html>
<html>
<head>
  <style>
    h1 {
        color: white;
        background-color: black;
    }
  </style>
</head>
<body>
  <h1>Eine Überschrift</h1>
</body>
</html>
````
Ein Nachteil von internen Stylesheets ist, dass Änderungen nur die Seite selbt beeinflussen, in der die Styles platziert wurden.


#### External Styles
Eine externe CSS-Datei ist die erste Wahl, wenn mehr als ein HTML-Dokument mit denselben CSS-Regeln formatiert werden soll. Bei der Verwendung von externen Styles werden CSS-Anweisungen in eine externe CSS-Datei (style.css) ausgelagert, welche im Head des Dokumentes über ein link-Tag eingebunden wird.

Inhalt des ausgelagerten Stylesheets:
````
h1 {
    color: white;
    background-color: black;
}
````

Einbindung im Head des HTML-Dokumentes:
````
<!DOCTYPE html>
<html>
<head>
  <link rel="stylesheet" src="css/style.css"
</head>
<body>
  <h1>Eine Überschrift</h1>
</body>
</html>
````

CSS ist nicht auf eine externe CSS-Datei beschränkt. Mit HTML link-Tags und der import-Regel können beliebig viele externe CSS-Dateien eingebunden werden. Grundsätzlich ist es besser, nicht zu viele CSS-Dateien anzulegen, da jede CSS-Datei mit einem HTTP-Request geladen wird und dies zusätzliche Ladezeit kostet. Damit eine große CSS-Datei übersichtlich bliebt, hilft strikte Organisation, eine saubere Struktur und die Verwendung von CSS Präprozessoren wie Sass oder Less und/oder ganze Task Runner wie [Webpack](https://webpack.js.org/), [Gulp](https://gulpjs.com/) und [Grunt](https://gruntjs.com/).

### Cascading
Wenn CSS-Stile in Konflikt geraten, weil sie extern in der CSS-Datei, im style-Tag, in einer inline-Regel und im Stylesheet des Benutzers unterschiedlich deklariert sind, löst die Kaskade den Konflikt. Die Regel, die dem Element am nächsten liegt, hat die höhere Priorität.

- Eine CSS-Eigenschaft überschreibt die vom Browser vorgegebene Eigenschaft.
- Führen CSS-Stile zu Konflikten innerhalb des globalen Stylesheets, übertrumpft die zuletzt im globalen Stylesheet aufgeführt Anweisung.

![Stylesheet Cascading](https://raw.githubusercontent.com/danielhauchler/start-coding/master/_assets/media/images/readme/cascading.png)








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
  #20a3d4
  #05b1b2
  #009899
```
