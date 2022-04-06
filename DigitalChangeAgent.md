<!--
author:   Sebastian Zug

email:    Sebastian.Zug@informatik.tu-freiberg.de

version:  1.0.3

language: de

narrator: Deutsch Male

mode:     Presentation

comment:  Dieser Kurs für in das Projekt LiaScript ein und diskutiert die
          Vorteile im Kontext der OER Idee.

link:     https://cdn.jsdelivr.net/chartist.js/latest/chartist.min.css

script:   https://cdn.jsdelivr.net/chartist.js/latest/chartist.min.js

logo:     ./images/logo.png

import: https://raw.githubusercontent.com/LiaTemplates/Rextester/master/README.md
        https://raw.githubusercontent.com/liaTemplates/processingjs/master/README.md
        https://raw.githubusercontent.com/liaTemplates/TextAnalysis/main/README.md

translation: Deutsch  translations/German.md

-->

[![LiaScript](https://raw.githubusercontent.com/LiaScript/LiaScript/master/badges/course.svg)](https://liascript.github.io/course/?https://raw.githubusercontent.com/SebastianZug/WillkommenAufLiaScript/master/DigitalChangeAgent.md#1)

# Open Educational Ressources (OER) - Hemmnisse und Lösungsansätze

![alt-text](images/Global_Open_Educational_Resources_Logo.png "OER-Logo - Quelle: [^1]")<!-- style="width: 50%; max-width=315px;" -->

------------------------------------------------------

Diese Präsentation beschreibt die Vision der _Open Educational Ressources_ mit Blick auf die "etablierten Vorbehalte". Der Beitrag wurde als Pitch Talk im Rahmen des [Digital Change Agent Programm](https://www.hd-sachsen.de/web/page.php?id=1333) am 7. April. 2022 vorgestellt.

_ Der Quellcode kann des Open Source Dokuments ist unter [Link](https://github.com/SebastianZug/WillkommenAufLiaScript/blob/master/DigitalChangeAgent.md) zu finden._

------------------------------------------------------

Sebastian Zug,

Fakultät für Mathematik und Informatik

TU Bergakademie Freiberg

[sebastian.zug@informatik.tu-freiberg.de](mailto:sebastian.zug@informatik.tu-freiberg.de)

------------------------------------------------------

[^1]: Jonathasmello - Eigenes Werk, CC BY 3.0, [https://commons.wikimedia.org/w/index.php?curid=18460156](https://commons.wikimedia.org/w/index.php?curid=18460156)

## OER Vision

                                  {{0-1}}
********************************************************************************

<!--
style="width: 100%; max-width: 860px; display: block; margin-left: auto; margin-right: auto;"
-->
```ascii

Kurs.txt         Version 1.0          Kurs.txt          Version 1.1
+--------------------------+          +---------------------------+
| Kurs  Deutsche Literatur |          | Kurs  Deutsche Literatur  |
| Autor Peter Muster       | "Fehler" | Autoren Peter Muster      |
|                          |------>   |         Angelika Maier    |----->
|~~~~~~~~~~~~~~~~~~~~~~~~~~|          |~~~~~~~~~~~~~~~~~~~~~~~~~~~|
| Ab 1756 bereiste Goethe  |---.      | Ab 1786 bereiste Goethe   |--.
| Italien ...              |   |      | Italien ...               |  |
                               |                                     |    Course.txt       Version 1.1.2
                               |                                     |    +----------------------------+
                               |                                     |    | Kurs  German Literature    |
                               |                                     |    | Autoren Peter Muster       |
                               |                                     .--> |         Angelika Maier     |
                               |                                          |         Steve Gray         |
                               |                                          |~~~~~~~~~~~~~~~~~~~~~~~~~~~~|
                               |                                          | In 1786 Goethe traveled to |
                               |                                          | Italy ...                  |
                               |      Kurs.txt         Version 1.0
                               |      +---------------------------+
                               |      | Kurs  Goethes Welt        |
                               |      | Autoren Peter Muster      |
                               .-->   |         Angelika Maier    |----->
                                      |~~~~~~~~~~~~~~~~~~~~~~~~~~~|
                                      | Während der italienischen |
                                      | Reise ...                 |
```
*Versionen der Lehrinhalte eines Kurses und deren Wiederverwendung in anderen Veranstaltungen*

********************************************************************************

                                 {{1-2}}
********************************************************************************

| Anforderung                  | Bedeutung                                  |
| ---------------------------- | ------------------------------------------ |
| `verwahren/vervielfältigen ` | Download, Speicherung und Vervielfältigung |
| `verwenden`                  | Nutzung im Lernkontext                     |
| `verarbeiten`                | Umgestaltung und Adaption                  |
| `vermischen`                 | Kombination und Extraktion                 |
| `verbreiten`                 | (digitale) Publikation                     |
*_5 V-Freiheiten für Offenheit_ von Jöran Muuß-Merholz und Jörg Lohrer für [open-educational-ressources](https://open-educational-resources.de) - Transferstelle für OER*

********************************************************************************

## OER Hemmnisse


                                  {{0-1}}
********************************************************************************

Status Quellcode
=========================

<!-- data-type="BarChart"
data-title="Anteil der Datenformate im Kontext der OPAL OER Materialien"
data-xlabel="Datentyp"
data-ylabel="% of Anzahl" -->
| Dateityp | Anzahl | Anteil |
| -------- | ------ | ------ |
| `pdf`    | 5242   | 49 %   |
| `jpg`    | 1040   | 9 %    |
| `mkv`    | 873    | 8 %    |
| `mp4`    | 586    | 5 %    |
| `png`    | 494    | 4 %    |
| `zip`    | 443    | 4 %    |
| `html`   | 387    | 3 %    |
| `docx`   | 376    | 3 %    |
| `pptx`   | 245    | 2 %    |
| `xlsx`   | 191    | 1 %    |
*_Typen von Materialien, die im OPAL-Datensatz als OER markiert sind._*

********************************************************************************

                                 {{1-2}}
********************************************************************************

Gegenargumente
=========================

|     | Ebene                        | Kernaussage                                                                                      |
| --- | ---------------------------- | ------------------------------------------------------------------------------------------------ |
| 1   | Emotionale Einordnung        | "_Da kann ja jeder meine Arbeit für sich nutzen!_"                                               |
|     |                              | "_Da kann mich ja jeder kontrollieren!_"                                                         |
| 2   | Rechtliche Herausforderungen | "_Ich verwende viele Grafiken, die bei deren Urheberrecht ich mir im besten Fall unsicher bin!_" |
| 3   | Auffindbarkeit               | "_Ich finde keine Inhalte, die ich in meiner Lehre gewinnbringend integrieren kann!_"            |
| 4   | Aufwand                      | "_Da muss man ja Informatik studiert haben!_"                                                    |
| 5   | Abdeckung                    | "_Da fehlen mir aber die Schnittstellen für meine Tools XY!_"                                    |

********************************************************************************

## OER Change Agent Strategie

|     | Ebene                        | <!-- Style="color:green" --> Lösungsansätze                                                                                                                                                                                                                                                  |
| --- | ---------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1   | Emotionale Einordnung        | <!-- Style="color:green" --> Präsentation des Themas im Rahmen der Freiberger E-Teach-Talks [Aufzeichnung](https://video.tu-freiberg.de/video/E-TeachTalk5-Open-Educational-Ressources-OER-Vision-Vorteile-amp-praktische-Umsetzung-mit-LiaScript-und-OPAL/0e36a414baa3158a6339be43b2e4dbc5) |
| 2   | Rechtliche Herausforderungen |                                                                                                                                                                                                                                                                 |
| 3   | Auffindbarkeit               | <!-- Style="color:green" --> Miniprojekt mit der Universitätsbibliothek Freiberg zur Generierung von standardisierten Meta-Informationen für OPAL-basierte OER Inhalte                                                                                                                       |
| 4   | Aufwand                      |                                                                                                                                                                                                                                                                 |
| 5   | Abdeckung                    | <!-- Style="color:green" --> Erweiterung der LiaScript Plugin                                                                                                                                                                                                                                |

                                     {{1-2}}
*******************************************************************************

```` Markdown
``` text
On Tuesday, January 10, I’ll go home to Chicago to say my
grateful farewell to you, even if you can’t be there in
person.
```
@Textanalysis.check(`[words", "syllables", "sentences"]`)
````

``` text Obama, Farewell Speech
On Tuesday, January 10, I’ll go home to Chicago to say my
grateful farewell to you, even if you can’t be there in
person.
```
@Textanalysis.base

*******************************************************************************

## Kontakt

Neugierig geworden auf OER und die Umsetzung mit OPAL / LiaScript? Sprechen Sie uns an!

| | |
| Prof. Dr. Sebastian Zug | [sebastian.zug@informatik.tu-freiberg.de](mailto:sebastian.zug@informatik.tu-freiberg.de)   |
| Dr. André Dietrich      | [andre.dietrich@informatik.tu-freiberg.de](mailto:andre.dietrich@informatik.tu-freiberg.de) |
