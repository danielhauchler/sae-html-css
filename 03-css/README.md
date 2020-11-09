## 03 - CSS (Cascading Style Sheets)
Cascading Style Sheets (gestufte Gestaltungsbögen), kurz CSS genannt ist eine Stylesheet-Sprache für elektronische Dokumente mit der Gestaltungsanweisungen erstellt werden, die zusammen mit den Auszeichnungssprachen HTML, dem DOM und XML eingesetzt werden. Sie ist ein so genannter „living standard“ und wird vom World Wide Web Consortium (W3C) stetig weiterentwickelt. CSS wurde entworfen, um Darstellungen weitestgehend von inhaltlicher Semantik zu trennen. Ob und in welchen Browserversionen welche CSS Properties implementiert sind könnt ihr unter [https://caniuse.com/](https://caniuse.com/]) prüfen.

Ein CSS-Regel-Set besteht aus einem Selektor und einem Deklarationsblock mit CSS Eigenschaften und Werten. Der Selektor zeigt auf das HTML-Element, das Du formatieren möchtest. Der Deklarationsblock enthält eine oder mehrere Deklarationen, die durch Semikolons voneinander getrennt werden. Jede Deklaration enthält einen CSS-Eigenschaftsnamen und einen durch einen Doppelpunkt getrennten Wert. Eine CSS-Deklaration endet immer mit einem Semikolon, und Deklarationsblöcke werden von geschweiften Klammern umgeben.

![CSS Selektoren und Eigenschaften](https://raw.githubusercontent.com/danielhauchler/start-coding/master/99_assets/media/images/readme/css.png)

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

![Stylesheet Cascading](https://raw.githubusercontent.com/danielhauchler/start-coding/master/99_assets/media/images/readme/cascading.png)








### Box Model
### CSS3
#### Flexbox
#### Transitions
#### Transforms / Rotate / Scale
### Responsive Web
