---
title: "EmfPlusLanguageIdentifier Clase"
type: docs
weight: 410
url: /es/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluslanguageidentifier/
---

**Summary:** The EmfPlusLanguageIdentifier object specifies a language identifier that corresponds to the natural<br/>            language in a locale, including countries, geographical regions, and administrative districts. <br/>            Each language identifier is an encoding of a primary language value and sublanguage value.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusLanguageIdentifier

**Inheritance:** EmfPlusStructureObjectType

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [EmfPlusLanguageIdentifier()](#EmfPlusLanguageIdentifier__1) | Inicializa una nueva instancia de la clase EmfPlusLanguageIdentifier |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| value | [EmfPlusLanguageIdentifierType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluslanguageidentifiertype/) | r/w | Gets or sets the value of the field<br/>              0 1 2 3 4 5 6 7 8 9 1 0 1 2 3 4 5 6 7 8 9 2 0 1 2 3 4 5 6 7 8 9 3 0 1<br/>            SubLanguageId | PrimaryLanguageId | <br/>            SubLanguageId (6 bits): El país, región geográfica o distrito administrativo para el idioma natural especificado en el campo PrimaryLanguageId.<br/>            Los identificadores de subidioma son extensibles por el proveedor. Los identificadores de subidioma definidos por el proveedor DEBEN estar en el rango 0x20 a 0x3F, inclusive.<br/>            PrimaryLanguageId (10 bits): El idioma natural.<br/>            Los identificadores de idioma principal son extensibles por el proveedor. Los identificadores de idioma principal definidos por el proveedor DEBEN estar en el rango 0x0200 a 0x03FF, inclusive. |


### Constructor: EmfPlusLanguageIdentifier() {#EmfPlusLanguageIdentifier__1}


```
 EmfPlusLanguageIdentifier() 
```

Inicializa una nueva instancia de la clase EmfPlusLanguageIdentifier

