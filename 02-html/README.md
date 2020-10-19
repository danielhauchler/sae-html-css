![SAE - Study Web Development](https://raw.githubusercontent.com/danielhauchler/start-coding/master/99_assets/media/images/readme/header.png)

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

![DOM-Knoten](https://raw.githubusercontent.com/danielhauchler/start-coding/master/99_assets/media/images/readme/dom-knoten.png)

Die vorliegende Struktur wird im Objektmodell durch die folgenden Beziehungen charakterisiert:

- Der Wurzelknoten (root) ist ein html-Tag und hat als Kinder (children) die Elementknoten head und body.
- Der html-Elementknoten ist umgekehrt ein Elternteil (parent) von head und body.
- Knoten mit gemeinsamem Elternteil (zum Beispiel die Elementknoten head und body) werden Geschwister (siblings) genannt.


### DOCTYPE

Mit der Dateiendung '.html' definieren wir Dateien als HTML Dokumente. Der Dateiname 'index' kann beliebig gewählt werden. Wenn wir jedoch später eine html-Datei auf einem Server bereitstellen, sind index-Dateien standardmäßig als Startseiten referenziert. Mit der URL https://www.start-coding.de/ würden wir den Inhalt der Datei https://www.start-coding.de/index.html angezeigt bekommen.
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

##### Metainformationen

````
    <!-- Page-Title, fokus auf ein Hauptkeyword -->
    <title>Page Title</title>

    <!-- Beschreibung der Seite mit Verwendung des Hauptkeywords -->
    <meta name="description" content="A description of the page content less than 156 characters">

    <!-- Facebook -->
    <meta property="fb:app_id" content="123456789">
    <meta property="og:url" content="https://www.start-coding.de">
    <meta property="og:type" content="website">
    <meta property="og:title" content="Start Coding">
    <meta property="og:image" content="https://www.start-coding.de/de/image.jpg">
    <meta property="og:description" content="Description Here">
    <meta property="og:site_name" content="Site Name">
    <meta property="og:locale" content="de_DE">
    <meta property="article:author" content="">

    <!-- Twitter -->
    <meta name="twitter:card" content="summary">
    <meta name="twitter:site" content="@site_account">
    <meta name="twitter:creator" content="@individual_account">
    <meta name="twitter:url" content="https://www.start-coding.de/page.html">
    <meta name="twitter:title" content="Content Title">
    <meta name="twitter:description" content="Content description less than 200 characters">
    <meta name="twitter:image" content="https://www.start-coding.de/image.jpg">

    <!-- Google+ -->
    <link href="https://plus.google.com/+StartCoding" rel="publisher">
    <meta itemprop="name" content="Staret Coding">
    <meta itemprop="description" content="Content description less than 200 characters">
    <meta itemprop="image" content="https://www.start-coding.de/image.jpg">
````
Weitere Metainformationen für den head findet ihr unter [HTML Elemente für den Head](https://github.com/danielhauchler/HEAD).

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
