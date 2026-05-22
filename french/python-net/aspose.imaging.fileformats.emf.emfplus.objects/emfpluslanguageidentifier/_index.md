---
title: "EmfPlusLanguageIdentifier Classe"
type: docs
weight: 410
url: /fr/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluslanguageidentifier/
---

**Summary:** The EmfPlusLanguageIdentifier object specifies a language identifier that corresponds to the natural<br/>            language in a locale, including countries, geographical regions, and administrative districts. <br/>            Each language identifier is an encoding of a primary language value and sublanguage value.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusLanguageIdentifier

**Inheritance:** EmfPlusStructureObjectType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusLanguageIdentifier()](#EmfPlusLanguageIdentifier__1) | Initialise une nouvelle instance de la classe EmfPlusLanguageIdentifier |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| value | [EmfPlusLanguageIdentifierType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluslanguageidentifiertype/) | r/w | Gets or sets the value of the field<br/>              0 1 2 3 4 5 6 7 8 9 1 0 1 2 3 4 5 6 7 8 9 2 0 1 2 3 4 5 6 7 8 9 3 0 1<br/>            SubLanguageId | PrimaryLanguageId | <br/>            SubLanguageId (6 bits) : Le pays, la région géographique ou le district administratif pour la langue naturelle spécifiée dans le champ PrimaryLanguageId.<br/>            Les identifiants de sous-langue sont extensibles par le vendeur. Les identifiants de sous-langue définis par le vendeur DOIVENT être dans la plage 0x20 à 0x3F, inclus.<br/>            PrimaryLanguageId (10 bits) : La langue naturelle.<br/>            Les identifiants de langue principale sont extensibles par le vendeur. Les identifiants de langue principale définis par le vendeur DOIVENT être dans la plage 0x0200 à 0x03FF, inclus. |


### Constructor: EmfPlusLanguageIdentifier() {#EmfPlusLanguageIdentifier__1}


```
 EmfPlusLanguageIdentifier() 
```

Initialise une nouvelle instance de la classe EmfPlusLanguageIdentifier

