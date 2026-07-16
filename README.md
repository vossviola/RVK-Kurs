<!--
author:   RVK-Koordinierungsstelle in der ULB / Viola Voß
email:    rvk.ulb@uni‐muenster.de
version:  0.0.1

logo:     https://www.ulb.uni-muenster.de/imperia/md/images/ulb2/_v/logo.svg

language: de
narrator: Deutsch Female

comment:  Einführung in die Regensburger Verbundklassifikation (RVK)
tags:     Bibliothek, Bestandsmanagement, Bestandserschließung, RVK, Tutorial

@btn:     <span class="lia-icon"><lia-keep>@0</lia-keep></span>

import:   https://github.com/LiaTemplates/KekuleJS
          https://github.com/LiaTemplates/VTK
          https://github.com/LiaTemplates/Algebrite
          https://github.com/LiaTemplates/ProcessingJS
          https://github.com/LiaTemplates/mec2/blob/main/README.md

classroom: false
classroom: disable
translate: off

-->


[![course badge](https://raw.githubusercontent.com/LiaScript/LiaScript/master/badges/course.svg)](https://LiaScript.github.io/course/?https://github.com/vossviola/RVK-Kurs)


# Die RVK – wozu, was, wie?

{{|>}}
*************************************************************************************************************

> [!TIP] Dieser geplante RVK-Kurs ist noch Work in Progress! | Stand 16.7.2026


Dieser Kurs soll einen interaktiven Einstieg in die Nutzung der Regensburger Verbundklassifikation (RVK) geben. 
Im ersten Teil ...


Zwischenüberschrift
====================
Texttexttext

Unterzwischenüberschrift
-------------------------

Zu jedem Abschnitt gibt es Aufgaben zur Lernkontrolle, die Sie direkt im Dokument ausführen können.

Dies ist ein LiaScript-Kurs. Um ihm im Präsentationsmodus anzeigen zu lassen, klicken Sie bitte [hier](https://liascript.github.io/course/?https://github.com/vossviola/RVK-Kurs)!

You can listen to the text by clicking on the little PLAY button on top of each page. Please note that this feature is used as commentary, this is **not** a tool to increase accessibility.
You can automatically translate the course with one click. However, please be aware that any automatic translation may contain mistakes and mistranslations of terms and concepts.
Please note that if you want to listen to a translation of the text, you should change the narrator voice in the html header in the raw version of this file. 


> [!NOTE] blauer Kasten

> [!TIP] gelber Kasten

> [!WARNING] rotbrauner Kasten

> Zitat

* man kann natürlich auch Bilder und Videos einbetten
* man kann Abschnitte einer Seite "blätterbar" machen (wie z.B. [in der Doku}(https://liascript.github.io/course/?https://raw.githubusercontent.com/liaScript/docs/master/README.md#107))


*************************************************************************************************************

## Impressum

{{|>}}
*************************************************************************************************************
Kontaktmöglichkeit: RVK-Koordinierungsstelle der ULB Münster, rvk.ulb@uni‐muenster.de

Notiz fürs Impressum: Credits an
* https://liascript.github.io/course/?https://raw.githubusercontent.com/NFDI4Biodiversity/nfdi4biodiversity-sle/main/README.md für die LiaScript-Datei
* https://liascript.github.io/course/?https://raw.githubusercontent.com/NFDI4Biodiversity/nfdi4biodiversity-sle/main/README.md#1 für Anregungen zu Übungsaufgaben

Snapshops auf Zenodo veröffentlichen, wie beim Bio-FDM-Kurs?

*************************************************************************************************************


# RVK – was ist das?

{{|>}}
*************************************************************************************************************

Lernziele:

{{1}}
Ziel 1

{{2}}
Ziel 2

{{3}}
Ziel 3


*************************************************************************************************************

## Inhalt 

{{|>}}
*************************************************************************************************************

xxx


*************************************************************************************************************

### Inhalt Unterunterkapitel

{{|>}}
*************************************************************************************************************

xxx  

*************************************************************************************************************


## Tools

{{|>}}
*************************************************************************************************************

xxx   

*************************************************************************************************************

## Zum Weiterlesen

{{|>}}
*************************************************************************************************************

xxx   

*************************************************************************************************************


## Übungsaufgaben Übersicht

{{|>}}
*************************************************************************************************************

Texteingabe
======================================

Eine Texteingabe ist im Grunde nur ein auf eine Frage folgendes Eingabefeld, bei dem geprüft wird, ob der eingegebene Text mit einer Lösung übereinstimmt.
Der Button mit dem Haken zeigt die Lösung an und setzt die Übung auf "bearbeitet" (für die Dauer der Browser-Sitzung).

Wie heißt der Hund von Asterix?

    [[Idefix]]


*Variante ohne "Zeig mir die Lösung"-Button*

Wie heißt der Freund von Asterix? 

    <!-- data-solution-button="off" -->
    [[Obelix]]


*Variante mit "der Zeig-mir-die-Lösung-Button wird erst nach zwei Fehlversuchen angezeigt"*

Wie heißt der Freund von Asterix? 

    <!-- data-solution-button="2" -->
    [[Obelix]]


*Variante mit Lösungshinweis* (solange der Hinweis-Button nach einem Klick farbig bleibt, gibt es noch einen weiteren Hinweis)

Wie heißt der Freund von Asterix? 

    [[Obelix]]
    [[?]] Hier ist nicht der Hund gemeint.
    [[?]] Und auch nicht der Druide.


*Variante mit "der Lösungshinweis wird erst nach zwei Fehlversuchen angezeigt"*

Wie heißt der Freund von Asterix? 

    <!-- data-hint-button="2" -->
    [[Obelix]]
    [[?]] Hier ist nicht der Hund gemeint.
    [[?]] Und auch nicht der Druide.
    


Single Choice
======================================

Es gibt eine richtige Lösung.

    [( )] Option falsch 1
    [(X)] <-- **Die richtige Antwort**
    [( )] Option falsch 2


*Variante mit Kommentar der richtigen Lösung*
*(macht aber nicht so richtig Sinn, weil es auch immer einen automatischen richtig/falsch-Hinweis gibt)*

What is 37 + 15?

    [[52]]
    [[?]] the solution is larger than 50
    [[?]] it is less than 55
    [[?]] it should be an even number
***********************************************************************
52 is the correct solution, because ...
***********************************************************************


*damit kann man dann auch Richtig-Falsch-Fragen erstellen*

Heißt der Hund von Asterix Fido?

    [( )] ja
    [(X)] nein

    
Die RVK wurde in Regensburg erfunden.

    [(X)] richtig
    [( )] falsch



Multiple Choice
======================================

Es werden mehrere Lösungsmöglichkeiten vorgegeben, von denen auch mehrere auswählbar sind. 

    [[X]] **<-- richtig**
    [[ ]] falsch
    [[ ]] **<-- richtig**
    [[X]] falsch



Matrix
======================================

Which of these are tools to organize your data analysis?

- [[Tools for data analysis] (Not a tool for data analysis)]
- [           (X)                         ( )              ]  Jupyter
- [           (X)                         ( )              ]  Binder
- [           ( )                         (X)              ]  Saturn
- [           ( )                         (X)              ]  Boa


*Variante mit Limitierung auf drei Versuche, dann wird aufgelöst*:

Which of the following repositories are generic, and which are subject-specific? Assign the repositories to the two categories.

<!-- data-randomize data-max-trials="3" data-show-solution-button="0"-->
- [[Generic]    [Subject-specific]]
- [    (X)             ( )      ]  Zenodo  
- [    (X)             ( )      ]  figshare  
- [    ( )             (X)      ]  PANGAEA
- [    ( )             (X)      ]  European Nucleotide Archive (ENA)


Man kan auch Single und Multi Choice in einer Matrix kombinieren:

    [ [head1] [ ;-) ] [ Option3 ] ]
    [   ( )     ( )       (X)     ]  <-- Single Choice
    [   [ ]     [X]       [X]     ]  <-- Multiple Choice



Begriffe zueinandersortieren
======================================
  
Assign the terms to the FAIR principles.

| Definition      | Term |
| ----------- | ----------- |
| [[ Findable | Accessible | Interoperable | (Reusable) ]]      | [[ Persistent Identifier (PID) | Data is described with rich metadata | (License) | Metadata is accessible, even if data is (no longer) available or accessible | Use a metadata standard to describe your data ]]|
| [[ (Findable) | Accessible | Interoperable | Reusable ]]      | [[ (Persistent Identifier (PID)) | Data is described with rich metadata | License | Metadata is accessible, even if data is (no longer) available or accessible | Use a metadata standard to describe your data ]]|
| [[ (Findable) | Accessible | Interoperable | Reusable ]]      | [[ Persistent Identifier (PID) | (Data is described with rich metadata) | License | Metadata is accessible, even if data is (no longer) available or accessible | Use a metadata standard to describe your data ]]|
| [[ Findable | (Accessible) | Interoperable | Reusable ]]      | [[ Persistent Identifier (PID) | Data is described with rich metadata | License | (Metadata is accessible, even if data is (no longer) available or accessible) | Use a metadata standard to describe your data ]]|
| [[ Findable | Accessible | (Interoperable) | Reusable ]]      | [[ Persistent Identifier (PID) | Data is described with rich metadata | License | Metadata is accessible, even if data is (no longer) available or accessible | (Use a metadata standard to describe your data) ]]|


Begriffe in eine Reihenfolge bringen
======================================

What is the correct order of a species name?

[[_lowii_ | J. E. Gray | (_Ptilocercus_) | 1848 ]][[ 1848 | _Ptilocercus_ | J. E. Gray | (_lowii_) ]][[ 1848  | (J. E. Gray) | _lowii_| _Ptilocercus_ ]][[ J. E. Gray | _Ptilocercus_ | _lowii_ | (1848) ]] 
***
Correct! Species names consist of Genus, epithet, authority, and year of publication of the species description.

The pen-tailed treeshrew (_Ptilocercus lowii_ J. E. Gray, 1848) is a treeshrew of the family Ptilocercidae native to southern Thailand, the Malay Peninsula, Borneo, and some Indonesian islands. In a study of wild pen-tailed treeshrews, the animals frequently consumed large amounts of fermented nectar, equivalent of 10–12 glasses of wine adjusted to body weight with an alcohol content up to 3.8%. The pen-tailed treeshrews did not show any signs of intoxication, probably because they use a different pathway to metabolize alcohol compared to humans.
***



Lückentext
======================================

mit Auswahl der gesuchten Wörter aus einer Dropdown-Liste
---------------------------------------------------------

Dies ist ein Beipielsatz, bei dem hier [[ Wort 4 | Wort 2 | Wort 3 | (Wort 1) ]] ausgewählt werden muss, hier [[ Wort 3 | Wort 1 | Wort 4 | (Wort 2) ]], dann hier [[ Wort 1 | Wort 2 | (Wort 3) | Wort 4 ]] und zum Schluss hier [[ Wort 1 | Wort 2 | Wort 3 | (Wort 4) ]].


mit Eintragen der gesuchten Wörter
-----------------------------------

I (learn) [[  have been learning  ]] English for seven years now. But last year I (not / work) [[ was not working ]] hard enough for English, that's why my marks (not / be) [[ were not ]] really that good then. 
As I (pass / want) [[ want to pass ]] my English exam successfully next year, I (study) [[ am going to study ]] harder this term.


kombiniert
-----------------------------------
Asterix und  [[  Obelix  ]] wohnen in [[ Westfalen | Tirol | (Fallien) ]]. [[ Ihre Katze | (Ihr Hund) ]] hei0t [[ Idefix ]].



*************************************************************************************************************



# Das Portal "RVK online"

{{|>}}
*************************************************************************************************************

Lernziele:

    {{1}}
Ziel 1

    {{2}}
Ziel 2

    {{3}}
Ziel 3

*************************************************************************************************************

## Inhalt 1

{{|>}}
*************************************************************************************************************

xxx


*************************************************************************************************************

## Inhalt 2

{{|>}}
*************************************************************************************************************

xxx  

*************************************************************************************************************

## Tools

{{|>}}
*************************************************************************************************************

xxx   

*************************************************************************************************************

## Zum Weiterlesen

{{|>}}
*************************************************************************************************************

xxx   

*************************************************************************************************************

## Übungsaufgaben

{{|>}}
*************************************************************************************************************

xxx   

*************************************************************************************************************



# Notationen & Signaturen

    {{|>}}
*************************************************************************************************************

Lernziele

After completing this chapter, you will be able to...

    {{1}}
...define the key aspects of your planning process

    {{2}}
...decide how to structure your data management plan

    {{3}}
...find a suitable tool to help you create a data management plan

*************************************************************************************************************

## Inhalt

{{|>}}
*************************************************************************************************************

xxx 

*************************************************************************************************************

## Tools

{{|>}}
*************************************************************************************************************

xxx   

*************************************************************************************************************

## Zum Weiterlesen

{{|>}}
*************************************************************************************************************

xxx   

*************************************************************************************************************

## Übungsaufgaben

{{|>}}
*************************************************************************************************************

xxx


*************************************************************************************************************


# RVK zur Recherche nach Medien


{{|>}}
*************************************************************************************************************

Lernziele:

{{1}}
Ziel 1

{{2}}
Ziel 2

{{3}}
Ziel 3

*************************************************************************************************************

## Inhalt

{{|>}}
*************************************************************************************************************

xxx


*************************************************************************************************************

## Tools

{{|>}}
*************************************************************************************************************

xxx   

*************************************************************************************************************

## Zum Weiterlesen

{{|>}}
*************************************************************************************************************

xxx   

*************************************************************************************************************

## Übungsaufgaben

{{|>}}
*************************************************************************************************************

xxx


*************************************************************************************************************

# RVK zur Aufstellung von Medien

{{|>}}
*************************************************************************************************************

Lernziele:

{{1}}
Ziel 1

{{2}}
Ziel 2

{{3}}
Ziel 3

*************************************************************************************************************

## Inhalt

{{|>}}
*************************************************************************************************************

xxx   

*************************************************************************************************************

## Tools

{{|>}}
*************************************************************************************************************

xxx   

*************************************************************************************************************

## Zum Weiterlesen

{{|>}}
*************************************************************************************************************

xxx   

*************************************************************************************************************

## Übungsaufgaben

{{|>}}
*************************************************************************************************************

 xxx


*************************************************************************************************************

# RVK @ MS – Die RVK in Bibliotheken der ULB Münster

{{|>}}
*************************************************************************************************************

Lernziele:

{{1}}
Ziel 1

{{2}}
Ziel 2

{{3}}
Ziel 3

*************************************************************************************************************

## Inhalt

{{|>}}
*************************************************************************************************************

xxx


*************************************************************************************************************

## Tools

{{|>}}
*************************************************************************************************************

xxx   

*************************************************************************************************************

## Zum Weiterlesen

{{|>}}
*************************************************************************************************************

xxx   

*************************************************************************************************************

## Übungsaufgaben

{{|>}}
*************************************************************************************************************

xxx

*************************************************************************************************************
