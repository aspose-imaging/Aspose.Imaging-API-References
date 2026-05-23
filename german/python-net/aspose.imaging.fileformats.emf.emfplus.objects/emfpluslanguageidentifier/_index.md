---
title: "EmfPlusLanguageIdentifier Klasse"
type: docs
weight: 410
url: /de/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluslanguageidentifier/
---

**Summary:** The EmfPlusLanguageIdentifier object specifies a language identifier that corresponds to the natural<br/>            language in a locale, including countries, geographical regions, and administrative districts. <br/>            Each language identifier is an encoding of a primary language value and sublanguage value.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusLanguageIdentifier

**Inheritance:** EmfPlusStructureObjectType

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [EmfPlusLanguageIdentifier()](#EmfPlusLanguageIdentifier__1) | Initialisiert eine neue Instanz der EmfPlusLanguageIdentifier Klasse |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| value | [EmfPlusLanguageIdentifierType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluslanguageidentifiertype/) | r/w | Gets or sets the value of the field<br/>              0 1 2 3 4 5 6 7 8 9 1 0 1 2 3 4 5 6 7 8 9 2 0 1 2 3 4 5 6 7 8 9 3 0 1<br/>            SubLanguageId | PrimaryLanguageId | <br/>            SubLanguageId (6 Bits): Das Land, die geografische Region oder der Verwaltungsbezirk für die in dem PrimaryLanguageId‑Feld angegebene natürliche Sprache.<br/>            Sublanguage‑Bezeichner sind herstellererweiterbar. Vom Hersteller definierte Sublanguage‑Bezeichner MUSS im Bereich 0x20 bis 0x3F liegen, inklusiv.<br/>            PrimaryLanguageId (10 Bits): Die natürliche Sprache.<br/>            Primary‑Sprachbezeichner sind herstellererweiterbar. Vom Hersteller definierte Primary‑Sprachbezeichner MUSS im Bereich 0x0200 bis 0x03FF liegen, inklusiv. |


### Constructor: EmfPlusLanguageIdentifier() {#EmfPlusLanguageIdentifier__1}


```
 EmfPlusLanguageIdentifier() 
```

Initialisiert eine neue Instanz der EmfPlusLanguageIdentifier Klasse

