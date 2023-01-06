<!--
author:   Sebastian Zug & André Dietrich

email:    LiaScript@web.de

version:  0.0.1

language: de

narrator: Deutsch Female

import:   https://raw.githubusercontent.com/liaTemplates/AVR8js/main/README.md

-->


# 2. LiaScript Tutorial an der TU Bergakademie Freiberg

-------------------------------------------------------------------------------

![Screenshot of abandoned education plattforms](pic/CodiLia_screenshot.png)

-------------------------------------------------------------------------------

> André Dietrich, Sebastian Zug

-------------------------------------------------------------------------------

### Quellen

* __Project-Website:__ https://LiaScript.github.io
* __Open-Source:__ https://github.com/liascript
* __YouTube:__ https://www.youtube.com/channel/UCyiTe2GkW_u05HSdvUblGYg
* __Additional resources:__

  - Documentation: https://github.com/LiaScript/docs
  - Free books: https://github.com/LiaBooks
  - Templates: https://github.com/LiaTemplates
  - Talks & ...: https://github.com/LiaPlayground
  - Blog: https://aizac.herokuapp.com

* __Editor:__ https://atom.io

  - Liascript-Preview: https://atom.io/packages/liascript-preview
  - Liascript-Snippets: https://atom.io/packages/liascript-snippets

* __Development-Server:__ https://www.npmjs.com/package/@liascript/devserver


### Motivation

     {{0-1}}
*******************************************************************************

Gefahren geschlossener Plattformen
================================


![Screenshot of abandoned education plattforms](pic/AdresseNichtGefunden.png "Source: ['Adresse nicht gefunden' – Auf den digitalen Spuren der E-Teaching-Förderprojekte](https://www.pedocs.de/volltexte/2011/3215/pdf/Haug_Wedekind_Adresse_nicht_gefunden_D_A.pdf)")

> __Warum ist das so?__

Geschlossenheit der Ansätze

1. Feste Systemgrenzen durch eine Serverinfrastruktur
2. Feste Kreativitätsgrenzen durch den Umfang der möglichen Inhalte
3. Feste Grenzen der Editoren

*******************************************************************************

     {{1-3}}
*******************************************************************************

LiaScript Lösungsansatz
================================

> __LiaScript__ definiert eine __Beschreibungssprache,__ auf der Basis von Markdown
>
> 1. die unabhängig von einer Serverinfrastruktur ist,
> 2. im Umfang durch eigene Plugins erweitert werden kann und
> 3. explizit auf Multi-Autoren-Ansätze abzielt.

     {{1-2}}
`````````
      Texteditor                                        ╔══════╡   nativ   ╞══════╗
          |                                             ║ Digitale Systeme        ║
          v                                         +-> ║ (WiSe 2020)             ║
+---------------------+              .-.  .-.       |   ║                         ║
| # Digitale Systeme  |\          .-(   )(   )-.    |   ╚═════════════════════════╝
| (WiSe 2020)         +-+      .-(  beliebiger  )   |
|                       | --> (       Cloud   -.  --+
| Fallbeispiele         |      '-(  Speicher   )    |   ╔═╡  iFrame im LMS     ╞══╗
| + ...                 |         (   )-(   )-.     |   ║ Digitale Systeme        ║
+-----------------------+          .-.   .-.        +-> ║ (WiSe 2020)             ║
                                                        ║                         ║
                                                        ╚═════════════════════════╝
`````````

     {{2-3}}
`````````
      Texteditor                                        ╔══════╡   nativ   ╞══════╗
          |                                             ║ Digitale Systeme        ║
          v                                         +-> ║ (WiSe 2020)             ║
+---------------------+              .-.  .-.       |   ║                         ║
| # Digitale Systeme  |\          .-(   )(   )-.    |   ╚═════════════════════════╝
| (WiSe 2020)         +-+      .-(  beliebiger  )   |
|                       | --> (       Cloud   -.  --+
| Fallbeispiele         |      '-(  Speicher   )    |   ╔═╡  iFrame im LMS     ╞══╗
| + ...                 |         (   )-(   )-.     |   ║ Digitale Systeme        ║
+-----------------------+          .-.   .-.        +-> ║ (WiSe 2020)             ║
          |                                             ║                         ║
          |                                             ╚═════════════════════════╝
          |
          |                        .-.
          |                     .-(   )-.               ╔══════╡    LMS    ╞══════╗
          |  Exporter        .-(   LMS   )-.            ║ Digitale Systeme        ║
          +-----------------(  OPAL, Moodle )-------->  ║ (WiSe 2020)             ║
                             '-(  Ilias    )            ║                         ║
                                (   )(   )              ╚═════════════════════════╝
                                 .-.  .-.
`````````

*******************************************************************************

### LiaScript Status Quo

         {{0-1}}
*******************************************************************************

Entwicklungspfad
================================

`````````
               Integration in                           Implementierung eines
               Remote-Labore als                        Multiautoren-Tools
               variables Beschreibungs-                 im Rahmen des BMBF
               konzept                                  Projektes MOER

 2016          2017          2018          2019          2020          2021
=|=============|=============|=============|=============|=============|=============|==>

 Entwicklung der             Einsatz als                               Integration des
 Basiskonzepte               Werkzeug für die                          Klassenraumkonzeptes
 im Rahmen des               Vorlesungsmaterialien                     in LiaScript
 BMBF Projektes                                                        DiP-iT Projekt
 Industrial-eLab

`````````


![Screenshot](pic/LiaScriptAtomScreenShot_1.0.png "Screenshot LiaScript V1.0")


*******************************************************************************

        {{1-2}}
*******************************************************************************

Und wer nutzt das?
================================

+ Aktuell bestehen unter GitHub öffentliche 104 Repositories, die `LiaScript` im Namen tragen.

  ![Screenshot of abandoned education plattforms](pic/Screenshot_LiaScriptBeispiel.png)
  ![Screenshot of abandoned education plattforms](pic/Screenshot_Twillo.png)
  ![Screenshot of abandoned education plattforms](pic/Screenshot_LiaScriptBeispiel2.png)

+ Auf der CodiLia-Instanz in Freiberg haben 177 Nutzer 308 Dokumente angelegt.


*******************************************************************************

       {{2-3}}
*******************************************************************************

Welche Möglichkeiten ergeben sich daraus?
================================

+ Blended Learning Ansätze (Dr. Jacob, Sprachenzentrum TU Freiberg)

+ Einbettung der Studierenden in die kontinuierliche Entwicklung der Materialien

  ![Screenshot of abandoned education plattforms](pic/Contributors.png)

*******************************************************************************


## Markdown Basics

Ein Textblock, bestehend aus einer oder mehreren Zeilen und wird als
zusammengehörender Absatz dargestellt.


     {{1}}
Mindestens eine
Leerzeile zwischen
zwei Text-
oder Markdown-Blöcken
dient als
Trenner.


     {{2}}
* Eine "unsortierte" Liste
* mit einer zusätzlichen

  1. "sortierten" Liste
  2. als Unterelement

* ist

  - sehr

    - sehr

      + einfach


     {{3}}
- *italic* ... _also italic_
- **bold** ... __also bold__
- ***bold and italic*** ... ___also ...___
- ~crossed out~
- ~~underlined~~
- ~~~crossed out and underlined~~~
- ** ~_and_ mix~tures ** _are **allowed**_ ^~~as~~ *well*^
- `**inline code**`


     {{4}}
| Tables               |      Are      |  Cool |
| -------------------- |:-------------:| -----:|
| *** columns 3 is *** | right-aligned | $1600 |
| ** column 2 is **    |   centered    |   $12 |
| * zebra stripes *    |   are neat    |    $1 |


     {{5}}
> Ein Zitat mit etwas wichtigem, dass vor sehr langer Zeit
> gesagt wurde ...
>
> -- von jemandem


     {{6}}
``` cpp
// Your First C++ Program

#include <iostream>

int main() {
    std::cout << "Hello World!";
    return 0;
}
```

### Verweise

1. **Ein direkter Link:**

   `https://LiaScript.github.io`

   https://LiaScript.github.io

2. **Ein Link mit einem "Namen":**

   `[LiaScript](https://LiaScript.github.io)`

   [LiaScript](https://LiaScript.github.io)

3. **Ein interner Link:**

   `[Gefahren geschlossener Plattformen](#Gefahren-geschlossener-Plattformen)`

   [Gefahren geschlossener Plattformen](#Gefahren-geschlossener-Plattformen)

4. **Ein Bild:**

   `![alt text](https://...url...image.jpg)`

   ![Niederländische Sprichworte](https://upload.wikimedia.org/wikipedia/commons/thumb/7/7e/Pieter_Brueghel_the_Elder_-_The_Dutch_Proverbs_-_Google_Art_Project.jpg/2560px-Pieter_Brueghel_the_Elder_-_The_Dutch_Proverbs_-_Google_Art_Project.jpg "Pieter Brueghel the Elder - The Dutch Proverbs")

## LiaScript

### Animationen und Darstellungsformate

   --{{1}}--
Schaut her, eine wichtige Tabelle.

      {{1-2}}
| Ich | tauche      | zuerst | auf  |
| --- | ----------- | ------ | ---- |
| und | verschwinde | auf    | zwei |


     {{2}}
* Ich bleibe bis zum Schluß
* und habe sogar einige {3}{__inline Animationen__}
* inline-Element können auch {3-4}{verschwinden} ...

   --{{2}}--
Die Aufzählung ist sehr wichtig und enthält auch inline-Animationen.

   --{{3 Russian Female}}--
Первоначально создан в 2004 году Джоном Грубером (англ. John Gruber) и Аароном
Шварцем. Многие идеи языка были позаимствованы из существующих соглашений по
разметке текста в электронных письмах...

   --{{4}}--
Wenn Sie das experimentelle Feature "Google-Übersetzer" ausprobieren, dann
finden sich auch heraus, dass die Stimmen ersetzt werden, mit Ausnahme der
russischen Sprecherin.

### Verweise++


     {{1-2}}
?[soundcloud](https://soundcloud.com/glennmorrison/beethoven-moonlight-sonata)

     {{2-3}}
!?[Create an LMS Educational Website](https://www.youtube.com/watch?v=df5hfVID5mo)

      {{3}}
??[anatomy of the eye](https://sketchfab.com/3d-models/the-human-eye-extrinsic-muscle-contraction-20-dc9c88630b6c42a8b242fd6024d0697f)


### Coding

``` javascript
console.log("Hello World")

console.warn("Global climate change is a serious threat!!!")

42
```
<script>@input</script>


                               {{1}}
********************************************************************************

<div id="example">
<wokwi-led color="red"   pin="13" label="13"></wokwi-led>
<wokwi-led color="green" pin="12" label="12"></wokwi-led>
<wokwi-led color="blue"  pin="11" label="11"></wokwi-led>
<wokwi-led color="blue"  pin="10" label="10"></wokwi-led>
<span id="simulation-time"></span>
</div>

``` cpp
byte leds[] = {13, 12, 11, 10};
void setup() {
  Serial.begin(115200);
  for (byte i = 0; i < sizeof(leds); i++) {
    pinMode(leds[i], OUTPUT);
  }
}

int i = 0;
void loop() {
  Serial.print("LED: ");
  Serial.println(i);
  digitalWrite(leds[i], HIGH);
  delay(250);
  digitalWrite(leds[i], LOW);
  i = (i + 1) % sizeof(leds);
}
```
@AVR8js.sketch(example)

********************************************************************************


### Tabellen und Daten

     {{1-2}}
<!--
data-title="Government expenditure on education"
data-xlabel="year"
data-ylabel="% of GDP"
-->
| Year | Finland |     USA | Germany |   China |
| ---- | -------:| -------:| -------:| -------:|
| 1995 | 6.80942 |         | 4.42079 | 1.84192 |
| 1996 | 6.86052 |         | 4.48319 | 1.85338 |
| 1997 |         |         |         |         |
| 1998 |         |         | 4.45345 | 1.84432 |
| 1999 | 5.86960 |         |         | 1.88803 |
| 2000 | 5.71687 |         |         |         |
| 2001 | 5.84797 |         |         |         |
| 2002 | 6.02477 |         |         |         |
| 2003 | 6.17476 |         |         |         |
| 2004 | 6.16849 |         |         |         |
| 2005 | 6.03605 |         |         |         |
| 2006 | 5.93809 |         | 4.27930 |         |
| 2007 | 5.68608 |         | 4.34302 |         |
| 2008 | 5.84676 |         | 4.40954 |         |
| 2009 | 6.48517 |         | 4.88047 |         |
| 2010 | 6.54070 | 5.42001 | 4.91368 |         |
| 2011 | 6.48200 | 5.22389 | 4.80779 |         |
| 2012 | 7.19254 | 5.19485 | 4.93331 |         |
| 2013 | 7.15848 | 4.94378 | 4.93496 |         |
| 2014 | 7.15155 | 4.98948 | 4.93112 |         |


     {{2-3}}
| Animal          | weight in kg | Lifespan years | Mitogen |
| --------------- | ------------:| --------------:| -------:|
| Mouse           |        0.028 |              2 |      95 |
| Flying squirrel |        0.085 |             15 |      50 |
| Brown bat       |        0.020 |             30 |      10 |
| Sheep           |           90 |             12 |      95 |
| Human           |           68 |             70 |      10 |


     {{3}}
| Music-Style {3-4}{1994} {4}{2014} |           Classic |           Country | Reggae |             Hip-Hop |           Hard-Rock |               Samba |
|:--------------------------------- | -----------------:| -----------------:| ------:| -------------------:| -------------------:| -------------------:|
| Student rating                    | {3-4}{50} {4}{20} | {3-4}{50} {4}{30} |    100 | {3-4}{200} {4}{220} | {3-4}{350} {4}{400} | {3-4}{250} {4}{230} |


### Quizze & Umfragen

<div style="width:100%;height:0;padding-bottom:93%;position:relative;"><iframe src="https://giphy.com/embed/a8TIlyVS7JixO" width="100%" height="100%" style="position:absolute" frameBorder="0" class="giphy-embed" allowFullScreen></iframe></div><p><a href="https://giphy.com/gifs/footage-rare-flips-a8TIlyVS7JixO">via GIPHY</a></p>

#### Text

Wie heißt der Markdown-Dialekt, der entwickelt wurde um interaktive Lehrinhalte
zu erstellen?

    [[LiaScript]]

---

Geben sie ein paar Stichworte zum Projekt ein?

    [[___]]

---

Gerne auch ganze Texte...

   [[___ ___ ___ ___]]

#### Multiple-Choice

Wie viel ist $3*\frac{3}{2}$?

    [[X]] weniger als 5
    [[ ]] unlösbar
    [[X]] mehr als $-4.5$

---

Welche Features wünschen Sie sich noch für LiaScript?

   [[1]] Learning Analytics
   [[2]] Nichtlineare Kurse
   [[3]] Bessere Doku
   [[0]] Sonstiges


#### Single-Choice


Just add as many points as you wish:

    [( )] ...
    [(X)] <-- Only the **X** is allowed.
    [( )] ...
    [[?]] nur die Mitte
*************************************************

??[Prince of Persia 4D](https://archive.org/details/msdos_4D_Prince_of_Persia_1994)

*************************************************

---

Würden Sie LiaScript auch im Unterricht einsetzen

   [(ja)] Ja auf jeden Fall
   [(nein)] Mir fehlen die Plattform-Features
   [(vielleicht)] Wenn man es in Moodle integrieren kann, dann vielleicht

#### Matrizen

German articles are weird...

    [[male (der<!-- class="notranslate"-->)]   (female [die<!-- class="notranslate"-->])   [neuter (das<!-- class="notranslate"-->)]]
    [    [X]           [ ]             [ ]     ]  Mann<!-- class="notranslate"--> - German for man
    [    ( )           (X)             ( )     ]  Frau<!-- class="notranslate"--> - German for woman
    [    [X]           [ ]             [ ]     ]  Junge<!-- class="notranslate"--> - German for boy
    [    ( )           ( )             (X)     ]  Mädchen<!-- class="notranslate"--> - German for girl
    [    [X]           [X]             [ ]     ]  Paprika<!-- class="notranslate"--> - German for bell pepper
    [    (X)           (X)             (X)     ]  Joghurt<!-- class="notranslate"--> - German for yogurt

---

In wie weit stimmen sie den folgenden Aussagen zu, von 1 für gar nicht, bis 5
für sehr stark.

    [(1)(2)(3)(4)(5)]
    [               ] Ich habe heute viel gelernt
    [               ] LiaScript ist eine einfache Sprache
    [               ] Die Web 3.0 Features klingen spannend


## (K)eine Web 3.0 Plattform

<div style="width:100%;height:0;padding-bottom:100%;position:relative;"><iframe src="https://giphy.com/embed/xThuW7icYBlQZxjnyg" width="100%" height="100%" style="position:absolute" frameBorder="0" class="giphy-embed" allowFullScreen></iframe></div><p><a href="https://giphy.com/gifs/truthorange-dog-surprised-wtf-xThuW7icYBlQZxjnyg">via GIPHY</a></p>

### Wo werden Inhalte gespeichert

     {{1}}
* ### Plattforms with Version-Control:

  1. [GitHub](https://github.com)
  2. [GitLab](https://gitlab.com)
  3. ...

     {{2}}
* ### Peer To Peer Systems with Browser-Support

  1. [Brave-Browser](https://brave.com) with [IPFS](https://ipfs.io)
  2. [Beaker-Browser](https://beakerbrowser.com) with [Hyper](https://hypercore-protocol.org)
  3. ...


     {{3}}
* ### Online stores

  1. [DropBox](https://www.dropbox.com)
  2. [NextCloud](https://nextcloud.com/)
  3. ... any ordinary webstore

     {{4}}
* ### Kollaborative online Editoren

  1. [CodiLia](https://github.com/liascript/codilia)
  2. ...

### Klassenräume

https://LiaScript.github.io/nightly/?https://raw.githubusercontent.com/LiaPlayground/Workshop_Freiberg_09-12-1021/main/README.md

### Index
