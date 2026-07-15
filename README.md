<!--
@onload

setTimeout(function() {
  const checkbox = document.getElementById("lia-checkbox-google_translate")

  checkbox.addEventListener("click", function(event) {
    event.preventDefault();

    // Show your custom confirmation dialog
    const userConfirmed = confirm(
      "Note on translation: This website uses Google Translate to translate content into different languages. Please note that when you use this function, data is transmitted to Google and processed there. Further information can be found in Google's Privacy Policy: https://policies.google.com/privacy?hl=de. Click OK to accept, or Cancel to abort."
    );

    if (!userConfirmed) {
      event.stopImmediatePropagation();
    }
  }, true);

}, 2000)

@end

language: de

narrator: Deutsch Female

author: Viola Voß

comment: 

logo: https://www.ulb.uni-muenster.de/imperia/md/images/ulb2/_v/logo.svg

classroom: false
classroom: disable
sharing: off

version: 0.0.1

-->

[![course badge](https://raw.githubusercontent.com/LiaScript/LiaScript/master/badges/course.svg)](https://LiaScript.github.io/course/?https://github.com/vossviola/RVK-Kurs)


# Die RVK – wozu, was, wie?

{{|>}}
*************************************************************************************************************

Hier kommt ein Einleitungstext hin


Kontaktmöglichkeit?

Notiz fürs Impressum: Credits an
* https://liascript.github.io/course/?https://raw.githubusercontent.com/NFDI4Biodiversity/nfdi4biodiversity-sle/main/README.md für die LiaScript-Datei
* https://liascript.github.io/course/?https://raw.githubusercontent.com/NFDI4Biodiversity/nfdi4biodiversity-sle/main/README.md#1 für Anregungen zu Übungsaufgaben

Snapshops auf Zenodo veröffentlichen, wie beim Bio-FDM-Kurs?

*************************************************************************************************************

## Wie diesen Kurs nutzen

{{|>}}
*************************************************************************************************************
**Wie diesen Kurs nutzen**

Dies ist ein LiaScript-Kurs. Um ihm im Präsentationsmodus anzeigen zu lassen, klicken Sie bitte [hier](https://liascript.github.io/course/?https://github.com/vossviola/RVK-Kurs)!

Only if you use the link, you will be able use all features of this course:

        {{1}}
After each chapter, you can test your knowledge with questions. These questions only work in the LiaScript version, not in simple Markdown.

![LiaScript question](images/figure0-2_LiaScript-questions.png)

        {{2}}
You can listen to the text by clicking on the little PLAY button on top of each page. Please note that this feature is used as commentary, this is **not** a tool to increase accessibility.

![location play button](images/figure0-1_play-button.png)

        {{3}}
You can automatically translate the course with one click. However, please be aware that any automatic translation may contain mistakes and mistranslations of terms and concepts.

![where to click for translation](images/figure0-3_translation.png)

        {{4}}
Please note that if you want to **listen** to a **translation** of the text, you should change the narrator voice in the html header in the raw version of this file. 

![picture of header with narrator English Female](images/figure0-4_narrator.png) 

For more details on the Markdown dialect LiaScript, see the [LiaScript documentation](https://liascript.github.io/course/?https://raw.githubusercontent.com/liaScript/docs/master/README.md#1).
 

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

## Unterkapitel

{{|>}}
*************************************************************************************************************

xxx

 

*************************************************************************************************************

### Unterunterkapitel

{{|>}}
*************************************************************************************************************

xxx  

*************************************************************************************************************



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

## Unterkapitel

{{|>}}
*************************************************************************************************************

xxx 

*************************************************************************************************************

## Unterkapitel

{{|>}}
*************************************************************************************************************

xxx   

*************************************************************************************************************

## Übungsaufgaben Übersicht

{{|>}}
*************************************************************************************************************

**Texteingaben**
Eine Texteingabe ist im Grunde nur ein auf eine Frage folgendes Eingabefeld, bei dem geprüft wird, ob der eingegebene Text mit einer Lösung übereinstimmt. In LiaScript wird dazu die folgende Notation verwendet (doppelt eckige Klammern):

Wie heißt der Hund von Asterix?
    [[Idefix]]



**Single Choice**
Es werden mehrere Lösungsmöglichkeiten vorgegeben, üblicherweise werden solche Aufgaben im Browser über sogenannte Radio-Buttons dargestellt. In LiaScript wird diese Notation einfach übernommen und mithilfe von runden Klammern innerhalb der eckigen angezeigt und das X markiert die einzig richtige Lösung:

    [( )] Option 1
    [(X)] <-- **Die richtige Auswahlmöglichkeit**
    [( )] Eine weitere falsche Option


**Multiple Choice**
Es werden mehrere Lösungsmöglichkeiten vorgegeben, von denen auch mehrere auswählbar sind. Diese Aufgaben werden zumeist durch sogenannte Checkboxen abgebildet, die in LiaScript wie folgt abgebildet werden:

    [[X]] **<-- richtig**
    [[ ]] falsch
    [[ ]] **<-- richtig**
    [[X]] falsch


**Matrix**

Which of these are tools to organize your data analysis?

- [[Tools for data analysis] (Not a tool for data analysis)]
- [           (X)                         ( )              ]  Jupyter
- [           (X)                         ( )              ]  Binder
- [           (X)                         ( )              ]  Git
- [           (X)                         ( )              ]  RMarkdown
- [           (X)                         ( )              ]  Python
- [           (X)                         ( )              ]  Bioconda
- [           (X)                         ( )              ]  roxygen2
- [           ( )                         (X)              ]  Saturn
- [           ( )                         (X)              ]  Boa
- [           ( )                         (X)              ]  Reddit
- [           ( )                         (X)              ]  Klaxxon
- [           ( )                         (X)              ]  Miro board
- [           ( )                         (X)              ]  Jamboard


Which of the following repositories are generic, and which are subject-specific? Assign the repositories to the two categories.

<!-- data-randomize data-max-trials="3" data-show-solution-button="0"-->
- [[Generic]    [Subject-specific]]
- [    (X)             ( )      ]  Zenodo  
- [    (X)             ( )      ]  figshare  
- [    (X)             ( )      ]  data_UMR  
- [    (X)             ( )      ]  RADAR  
- [    (X)             ( )      ]  Dryad
- [    (X)             ( )      ]  Plant Genomics and Phenomics Research Data Repository (e!DAL-PGP)
- [    ( )             (X)      ]  PANGAEA
- [    ( )             (X)      ]  European Nucleotide Archive (ENA)
- [    ( )             (X)      ]  Movebank
- [    ( )             (X)      ]  Ocean Biodiversity Information System (OBIS)
- [    ( )             (X)      ]  FishBase
- 

Bei dieser Darstellung werden die beiden zuvor vorgestellten Quizze in einer zwei-dimensionalen Matrix kombiniert. Die oberste Zeile definiert die möglichen Optionen, während die Zeilen Multiple und Single Choice Quizze kombinieren.

    [ [head1] [ ;-) ] [ Option3 ] ]
    [   ( )     ( )       (X)     ]  <-- Single Choice
    [   [ ]     [X]       [X]     ]  <-- Multiple Choice


* Begriffe zueinandersortieren*
  
Assign the terms to the FAIR principles.

| Definition      | Term |
| ----------- | ----------- |
| [[ Findable | Accessible | Interoperable | (Reusable) ]]      | [[ Persistent indetifier (PID) | Data is described with rich metadata | (License) | Metadata is accessible, even if data is (no longer) available or accessible | Use a metadata standard to describe your data ]]|
| [[ (Findable) | Accessible | Interoperable | Reusable ]]      | [[ (Persistent indetifier (PID)) | Data is described with rich metadata | License | Metadata is accessible, even if data is (no longer) available or accessible | Use a metadata standard to describe your data ]]|
| [[ (Findable) | Accessible | Interoperable | Reusable ]]      | [[ Persistent indetifier (PID) | (Data is described with rich metadata) | License | Metadata is accessible, even if data is (no longer) available or accessible | Use a metadata standard to describe your data ]]|
| [[ Findable | (Accessible) | Interoperable | Reusable ]]      | [[ Persistent indetifier (PID) | Data is described with rich metadata | License | (Metadata is accessible, even if data is (no longer) available or accessible) | Use a metadata standard to describe your data ]]|
| [[ Findable | Accessible | (Interoperable) | Reusable ]]      | [[ Persistent indetifier (PID) | Data is described with rich metadata | License | Metadata is accessible, even if data is (no longer) available or accessible | (Use a metadata standard to describe your data) ]]|



**Begriffe in eine Reihenfolge bringen**

What is the correct order of a species name?
[[_lowii_ | J. E. Gray | (_Ptilocercus_) | 1848 ]][[ 1848 | _Ptilocercus_ | J. E. Gray | (_lowii_) ]][[ 1848  | (J. E. Gray) | _lowii_| _Ptilocercus_ ]][[ J. E. Gray | _Ptilocercus_ | _lowii_ | (1848) ]] 
***
Correct! Species names consist of Genus, epithet, authority, and year of publication of the species description.

The pen-tailed treeshrew (_Ptilocercus lowii_ J. E. Gray, 1848) is a treeshrew of the family Ptilocercidae native to southern Thailand, the Malay Peninsula, Borneo, and some Indonesian islands. In a study of wild pen-tailed treeshrews, the animals frequently consumed large amounts of fermented nectar, equivalent of 10–12 glasses of wine adjusted to body weight with an alcohol content up to 3.8%. The pen-tailed treeshrews did not show any signs of intoxication, probably because they use a different pathway to metabolize alcohol compared to humans.
***


**Weitere Optionen**
Zu Quizzen können verschiedene weitere Hilfen sowie erweiterte Auflösungen hinzugefügt werden. Die vorgestellten Anpassungen können allen Quiz-Typen angefügt werden…

*Hilfen*
Gegebenenfalls kann es notwendig sein, dass Hilfen/Tipps zu den Quizzen hinzugefügt werden sollen, sodass der Nutzer selber entscheiden kann, sich eine Hilfe geben zu lassen, bevor er/sie auf den Auflöse-Button klickt.

Wie heißt der Freund von Asterix?

    [[Obelix]]
    [[?]] Hier ist nicht der Hund gemeint
    [[?]] Und auch nicht der Druide


*Auflösungen*
Mithilfe von zwei Linienzügen, die durch mindestens drei aufeinander folgenden `***` definiert werden, können erweiterte Auflösungen definiert werden, die mehrere Markdown-Blöcke enthalten können. Diese werden nur gezeigt, falls der Nutzer die richtige Lösung gegeben hat bzw. auf Auflösungen klickt.

How do I collect metadata?
- [(X)] I enquire about suitable metadata standards before starting research and collect as much metadata as possible to ensure that the data can also be understood by other researchers.
- [( )] I simply transfer the metadata from another project.
- [( )] I always follow the same scheme, no matter what type of research data it is.
***
Correct! But it really won't hurt to ask colleagues of the same discipline whether there are any known suitable metadata standards and how they should be applied.
***



    [[LiaScript]]
    [[?]] Bitte achten Sie auf die korrekte Schreibweise
    [[?]] Die Lösung beginnt mit Lia.....
    **************************************************
    LiaScript ist eine interaktive Erweiterung zu
    Markdown, zur Entwicklung interaktiver und freier
    Lehrinhalte. Mehr Informationen finden Sie unter:

    https://LiaScript.github.io

                    Nur ein weiteres Diagramm
    1.9 |
        |                 ***
      y |               *     *
      - | r r r r r r r*r r r r*r r r r r r r
      a |             *         *
      x |            *           *
      i | B B B B B * B B B B B B * B B B B B
      s |         *                 *
        |**  * *                       * *   *
     -1 +------------------------------------
        0              x-axis               1

    **************************************************


Die maximale Anzahl an Versuchen kann limitiert werden (im folgenden Beispiel: 3), und der "zeige die Lösung"-Button kann ausgeblendet werden:

How do I collect metadata?
<!-- data-randomize data-max-trials="3" data-show-solution-button="0"-->
- [(X)] I enquire about suitable metadata standards before starting research and collect as much metadata as possible to ensure that the data can also be understood by other researchers.
- [( )] I simply transfer the metadata from another project.
- [( )] I always follow the same scheme, no matter what type of research data it is.
***
Correct! But it really won't hurt to ask colleagues of the same discipline whether there are any known suitable metadata standards and how they should be applied.
***


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

## Unterkapitel

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

## Unerkapitel

{{|>}}
*************************************************************************************************************

xxx


*************************************************************************************************************

## Übungsaufgaben

{{|>}}
*************************************************************************************************************

xxx

*************************************************************************************************************
