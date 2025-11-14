---
title: EmfPlusLanguageIdentifier Class
type: docs
weight: 410
url: /python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluslanguageidentifier/
---

**Summary:** The EmfPlusLanguageIdentifier object specifies a language identifier that corresponds to the natural<br/>            language in a locale, including countries, geographical regions, and administrative districts. <br/>            Each language identifier is an encoding of a primary language value and sublanguage value.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusLanguageIdentifier

**Inheritance:** EmfPlusStructureObjectType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusLanguageIdentifier()](#EmfPlusLanguageIdentifier__1) | Initializes a new instance of the EmfPlusLanguageIdentifier class |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| value | [EmfPlusLanguageIdentifierType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluslanguageidentifiertype/) | r/w | Gets or sets the value of the field<br/>              0 1 2 3 4 5 6 7 8 9 1 0 1 2 3 4 5 6 7 8 9 2 0 1 2 3 4 5 6 7 8 9 3 0 1<br/>            SubLanguageId|   PrimaryLanguageId | <br/>            SubLanguageId (6 bits): The country, geographic region or administrative district for the natural language specified in the PrimaryLanguageId field.<br/>            Sublanguage identifiers are vendor-extensible. Vendor-defined sublanguage identifiers MUST be in the range 0x20 to 0x3F, inclusive.<br/>            PrimaryLanguageId (10 bits): The natural language.<br/>            Primary language identifiers are vendor-extensible. Vendor-defined primary language identifiers MUST be in the range 0x0200 to 0x03FF, inclusive. |


### Constructor: EmfPlusLanguageIdentifier() {#EmfPlusLanguageIdentifier__1}


```
 EmfPlusLanguageIdentifier() 
```

Initializes a new instance of the EmfPlusLanguageIdentifier class

