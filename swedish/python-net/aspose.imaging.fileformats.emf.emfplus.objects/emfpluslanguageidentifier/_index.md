---
title: "EmfPlusLanguageIdentifier-klass"
type: docs
weight: 410
url: /sv/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluslanguageidentifier/
---

**Summary:** The EmfPlusLanguageIdentifier object specifies a language identifier that corresponds to the natural<br/>            language in a locale, including countries, geographical regions, and administrative districts. <br/>            Each language identifier is an encoding of a primary language value and sublanguage value.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusLanguageIdentifier

**Inheritance:** EmfPlusStructureObjectType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusLanguageIdentifier()](#EmfPlusLanguageIdentifier__1) | Initierar en ny instans av EmfPlusLanguageIdentifier-klassen |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| value | [EmfPlusLanguageIdentifierType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluslanguageidentifiertype/) | r/w | Gets or sets the value of the field<br/>              0 1 2 3 4 5 6 7 8 9 1 0 1 2 3 4 5 6 7 8 9 2 0 1 2 3 4 5 6 7 8 9 3 0 1<br/>            SubLanguageId | PrimaryLanguageId | <br/>            SubLanguageId (6 bitar): Landet, den geografiska regionen eller den administrativa distriktet för det naturliga språket som anges i PrimaryLanguageId-fältet.<br/>            Sublanguage-identifierare är leverantörsutbyggbara. Leverantörsdefinierade sublanguage-identifierare MÅSTE ligga i intervallet 0x20 till 0x3F, inklusive.<br/>            PrimaryLanguageId (10 bitar): Det naturliga språket.<br/>            Primary language-identifierare är leverantörsutbyggbara. Leverantörsdefinierade primary language-identifierare MÅSTE ligga i intervallet 0x0200 till 0x03FF, inklusive. |


### Constructor: EmfPlusLanguageIdentifier() {#EmfPlusLanguageIdentifier__1}


```
 EmfPlusLanguageIdentifier() 
```

Initierar en ny instans av EmfPlusLanguageIdentifier-klassen

