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

Notiz fürs Impressum: Credit an https://liascript.github.io/course/?https://raw.githubusercontent.com/NFDI4Biodiversity/nfdi4biodiversity-sle/main/README.md für die LiaScript-Datei

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

# **1. RVK – was ist das?**

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

# **2. Das Portal "RVK online"**

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

## 2.1. Unterkapitel

{{|>}}
*************************************************************************************************************

xxx

 

*************************************************************************************************************

### 2.1.1. Unterunterkapitel

{{|>}}
*************************************************************************************************************

xxx  

*************************************************************************************************************



*************************************************************************************************************

# **3. Notationen & Signaturen**

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

## 3.1. Unterkapitel

{{|>}}
*************************************************************************************************************

xxx 

*************************************************************************************************************

## 3.2. Unterkapitel

{{|>}}
*************************************************************************************************************

xxx   

*************************************************************************************************************

## 3.x Übungsaufgaben

{{|>}}
*************************************************************************************************************

Which of these aspects are part of a data management plan?

<!-- data-randomize data-max-trials="3" data-show-solution-button="0"-->
- [[X]] Naming those responsible for data management
- [[ ]] Vote of an ethics committee
- [[X]] Information on data archiving
- [[X]] Costs of data management and data storage
- [[X]] Information on storage and backup during the project
- [[ ]] Description of the benefits of the data management plan
- [[X]] Information on data publication
***
Right! There is of course much more information that should also be mentioned in a DMP, such as information on the data formats produced, data types and the estimated amount of data, in projects with several participants also information on how the data is shared within the project, or information on legal features, if existing.
***

Which statement is true?

<!-- data-randomize data-max-trials="3" data-show-solution-button="0"-->
- [(X)] A data management plan saves time and helps me to minimize data loss.
- [( )] I only need to create a DMP if I expect large amounts of data.
- [( )] The DMP is primarily a control instrument for funding institutions.
***
Right! Also, a DMP created before or with the start of the project will help you organise the research data management for you and your team. Remember, however, that it is a living document that might need adjustments at regular intervals. A well-maintained DMP can also facilitate the onboarding of new project staff with regard to research data management.
***


*************************************************************************************************************

# **4. RVK zur Recherche nach Medien**


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

## 4.2. xxx

{{|>}}
*************************************************************************************************************

xxx


*************************************************************************************************************

## 4.5 Übungsaufgaben

{{|>}}
*************************************************************************************************************

How do I collect metadata?

<!-- data-randomize data-max-trials="3" data-show-solution-button="0"-->
- [(X)] I enquire about suitable metadata standards before starting research and collect as much metadata as possible to ensure that the data can also be understood by other researchers.
- [( )] I simply transfer the metadata from another project.
- [( )] I always follow the same scheme, no matter what type of research data it is.
***
Correct! But it really won't hurt to ask colleagues of the same discipline whether there are any known suitable metadata standards and how they should be applied.
***

When should the associated metadata be deleted if research data is deleted from a repository?

<!-- data-randomize data-max-trials="3" data-show-solution-button="0"-->
- [(X)] Preferably not at all. If research data is withdrawn, the metadata provides an overview of the project and possibly why the data was withdrawn.
- [( )] The metadata is deleted together with the research data.
- [( )] For legal reasons, the metadata must remain in the repository for at least one year.
***
Correct! One reason, above all, is the obligation to provide proof of research data. If, for example, a text was published in 2017 that examined data from 2015, but in 2019 it turns out that the data collected at that time violated certain legal requirements, the text must still retain evidence that this research data actually still existed and was accessible at the time of publication, and also information about what this data contained.
***

What exactly is metadata?

<!-- data-randomize data-max-trials="3" data-show-solution-button="0"-->
- [(X)] Metadata describes other data of any kind in a structured way and helps to understand this data.
- [( )] Metadata is data that stores information about files in encrypted form.
- [( )] Metadata is used to make the actual research data available, as it would otherwise not be accessible.
***
Correct! Metadata is data about data. Metadata therefore contain descriptive information to understand another or the described data set. Understanding the described data is mostly dependent on already having expertise in dealing with this type of data through one's own research or studies.
***

How should metadata ideally be stored?

<!-- data-randomize data-max-trials="3" data-show-solution-button="0"-->
- [( )] I create metadata according to my own schema according to the requirements of my own research data.
- [(X)] Metadata should be created according to specific metadata standards.
- [( )] Metadata should only be readable by myself in order to protect my research data.
***
Correct. Ideally, metadata should be available as subject-specific standards. However, this is not always the case, so depending on the research project, metadata sometimes has to be created.
***

What is the correct order of a species name?

<!-- data-randomize data-max-trials="3" data-show-solution-button="0"-->
[[_lowii_ | J. E. Gray | (_Ptilocercus_) | 1848 ]][[ 1848 | _Ptilocercus_ | J. E. Gray | (_lowii_) ]][[ 1848  | (J. E. Gray) | _lowii_| _Ptilocercus_ ]][[ J. E. Gray | _Ptilocercus_ | _lowii_ | (1848) ]] 
***
Correct! Species names consist of Genus, epithet, authority, and year of publication of the species description.

The pen-tailed treeshrew (_Ptilocercus lowii_ J. E. Gray, 1848) is a treeshrew of the family Ptilocercidae native to southern Thailand, the Malay Peninsula, Borneo, and some Indonesian islands. In a study of wild pen-tailed treeshrews, the animals frequently consumed large amounts of fermented nectar, equivalent of 10–12 glasses of wine adjusted to body weight with an alcohol content up to 3.8%. The pen-tailed treeshrews did not show any signs of intoxication, probably because they use a different pathway to metabolize alcohol compared to humans.
***

What is the correct order of a species name?

<!-- data-randomize data-max-trials="3" data-show-solution-button="0"-->
[[ Fresen | _oligospora_ | (_Arthrobotrys_) | 1850 ]] [[ _Arthrobotrys_ | 1850 | Fresen | (_oligospora_) ]] [[ 1850 | _oligospora_ |_Arthrobotrys_ | (Fresen) |]] [[ _Arthrobotrys_ | (1850) | Fresen | _oligospora_ ]]
***
Correct! Species names consist of Genus, epithet, authority, and year of publication of the species description.

_Arthrobotrys oligospora_ Fresen. (1850) is a nematode-capturing fungus. In low nitrogen environments, it grows sticky nets from hyphae and attracts nematodes with semiochemicals1 that nematodes use to communicate with each other. Small nematodes can be caught with a single loop. The more the nematodes struggle to escape, the more they are glued to the net. Finally, the nematodes are paralysed and digested by hyphae growing into their bodies.
 
***

What is the correct order of a species name?

<!-- data-randomize data-max-trials="3" data-show-solution-button="0"-->
[[ (_Cymothoa_) | _exigua_ | Schiødte & Meinert | 1884 ]] [[ _Cymothoa_ | (_exigua_) | Schiødte & Meinert | 1884 ]][[ _Cymothoa_ | _exigua_ | (Schiødte & Meinert) | 1884 ]] [[ _Cymothoa_ | _exigua_ | Schiødte & Meinert | (1884) ]]
***
Correct! Species names consist of Genus, epithet, authority, and year of publication of the species description.

_Cymothoa exigua_ (Schiødte & Meinert, 1884), the tongue-eating louse, is a parasitic isopod of the family Cymothoidae. Females attach to the tongue and sever the blood vessels. When the tongue falls off, the female attaches itself to the remaining stub of tongue and the parasite itself effectively serves as the fish's new "tongue". The parasite feeds on the host's blood and mucus. Juveniles likely first attach to the gills of a fish and become males. As they mature, they become females, with mating likely occurring on the gills.
***

What is the correct order of a species name?

<!-- data-randomize data-max-trials="3" data-show-solution-button="0"-->
[[ (_Ailanthus_) | _altissima_ | Mill. | Swingle ]][[ _Ailanthus_ | (_altissima_) | Mill. | Swingle ]][[ _Ailanthus_ | _altissima_ | (Mill.) | Swingle ]][[ _Ailanthus_ | _altissima_ | Mill. | (Swingle) ]]
***
Correct! Species names of plants consist of Genus, epithet, and authority.

_Ailanthus altissima_ (Mill.) Swingle is a deciduous tree native to northeast and central China, and Taiwan. The tree grows rapidly and is very tolerant of pollution. It is considered to be one of the worst invasive species in Europe and North America. It spreads aggressively both by seeds and vegetatively by very long root sprouts, often "tunneling" even below wide streets and crossroads. This "tree of heaven" inhibits the growth of other plants in their sourroundings. Oh, and the male flowers have a very distinctive smell... 
***

*************************************************************************************************************

# **5. RVK zur Aufstellung von Medien**

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

## 5.4 Übungsaufgaben

{{|>}}
*************************************************************************************************************

Which of these are tools to organize your data analysis?

<!-- data-randomize data-max-trials="3" data-show-solution-button="0"-->
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

Which of these statements are true? Select all correct answers.

<!-- data-randomize data-max-trials="3" data-show-solution-button="0"-->
- [[X]] Git is a free software for version control.
- [[X]] Git means "unpleasant person".
- [[ ]] Code documentation is unnessesary - code is self-explaining.
- [[ ]] GitHub, GitLab and Git are just different names for the same platform.

What is a repository?

<!-- data-randomize data-max-trials="3" data-show-solution-button="0"-->
- [(X)] A digital, curated data center for the storage and reuse of research data
- [( )] A search engine that makes any research data freely available to everyone without restrictions
- [( )] A research community that deals with the reutilization of research data
- [( )] A local copy of all research data collected in a project
***
That is correct. At the University of Marburg, data_UMR is available to you as a repository.
***

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

*************************************************************************************************************

# **6. RVK @ MS – Die RVK in Bibliotheken der ULB Münster**

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

## 6.1 Unerkapitel

{{|>}}
*************************************************************************************************************

xxx


*************************************************************************************************************

## 6.x Questions

{{|>}}
*************************************************************************************************************

Assign the terms to the FAIR principles.

| Definition      | Term |
| ----------- | ----------- |
| [[ Findable | Accessible | Interoperable | (Reusable) ]]      | [[ Persistent indetifier (PID) | Data is described with rich metadata | (License) | Metadata is accessible, even if data is (no longer) available or accessible | Use a metadata standard to describe your data ]]|
| [[ (Findable) | Accessible | Interoperable | Reusable ]]      | [[ (Persistent indetifier (PID)) | Data is described with rich metadata | License | Metadata is accessible, even if data is (no longer) available or accessible | Use a metadata standard to describe your data ]]|
| [[ (Findable) | Accessible | Interoperable | Reusable ]]      | [[ Persistent indetifier (PID) | (Data is described with rich metadata) | License | Metadata is accessible, even if data is (no longer) available or accessible | Use a metadata standard to describe your data ]]|
| [[ Findable | (Accessible) | Interoperable | Reusable ]]      | [[ Persistent indetifier (PID) | Data is described with rich metadata | License | (Metadata is accessible, even if data is (no longer) available or accessible) | Use a metadata standard to describe your data ]]|
| [[ Findable | Accessible | (Interoperable) | Reusable ]]      | [[ Persistent indetifier (PID) | Data is described with rich metadata | License | Metadata is accessible, even if data is (no longer) available or accessible | (Use a metadata standard to describe your data) ]]|

RDM[^57] introduces you to many new abbreviations. Which of the following abbrevations belongs to which term?

<!-- data-randomize data-max-trials="3" data-show-solution-button="0"-->
- [(DFG) (ORCID) (ABCD) (DwC) (GFBio) (GBIF) (DMP) (DSI) (DOI)]
- [ (X)    ( )    ( )    ( )   ( )     ( )    ( )   ( )   ( ) ] Deutsche Forschungsgemeinschaft
- [ ( )    (X)    ( )    ( )   ( )     ( )    ( )   ( )   ( ) ] Open Researcher Contributor Identification Initiative (full name obsolete)
- [ ( )    ( )    (X)    ( )   ( )     ( )    ( )   ( )   ( ) ] Access to Biological Collection Data
- [ ( )    ( )    ( )    (X)   ( )     ( )    ( )   ( )   ( ) ] Darwin Core
- [ ( )    ( )    ( )    ( )   (X)     ( )    ( )   ( )   ( ) ] Gesellschaft für Biologische Daten (German Federation for Biological Data)
- [ ( )    ( )    ( )    ( )   ( )     (X)    ( )   ( )   ( ) ] Global Biodiversity Information Facility
- [ ( )    ( )    ( )    ( )   ( )     ( )    (X)   ( )   ( ) ] Data Management Plan
- [ ( )    ( )    ( )    ( )   ( )     ( )    ( )   (X)   ( ) ] Digital Sequence Information
- [ ( )    ( )    ( )    ( )   ( )     ( )    ( )   ( )   (X) ] Digital Object Identifier

___

[^57]: Research Data Management

*************************************************************************************************************
