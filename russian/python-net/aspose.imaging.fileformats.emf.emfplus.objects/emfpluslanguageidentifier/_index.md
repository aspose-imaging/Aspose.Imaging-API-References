---
title: "EmfPlusLanguageIdentifier Класс"
type: docs
weight: 410
url: /ru/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluslanguageidentifier/
---

**Summary:** The EmfPlusLanguageIdentifier object specifies a language identifier that corresponds to the natural<br/>            language in a locale, including countries, geographical regions, and administrative districts. <br/>            Each language identifier is an encoding of a primary language value and sublanguage value.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusLanguageIdentifier

**Inheritance:** EmfPlusStructureObjectType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusLanguageIdentifier()](#EmfPlusLanguageIdentifier__1) | Инициализирует новый экземпляр класса EmfPlusLanguageIdentifier |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| value | [EmfPlusLanguageIdentifierType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluslanguageidentifiertype/) | r/w | Gets or sets the value of the field<br/>              0 1 2 3 4 5 6 7 8 9 1 0 1 2 3 4 5 6 7 8 9 2 0 1 2 3 4 5 6 7 8 9 3 0 1<br/>            SubLanguageId | PrimaryLanguageId | <br/>            SubLanguageId (6 бит): Страна, географический регион или административный район для естественного языка, указанного в поле PrimaryLanguageId.<br/>            Идентификаторы субязыков расширяемы поставщиком. Субязыковые идентификаторы, определённые поставщиком, ДОЛЖНЫ находиться в диапазоне от 0x20 до 0x3F включительно.<br/>            PrimaryLanguageId (10 бит): Естественный язык.<br/>            Идентификаторы основных языков расширяемы поставщиком. Основные языковые идентификаторы, определённые поставщиком, ДОЛЖНЫ находиться в диапазоне от 0x0200 до 0x03FF включительно. |


### Constructor: EmfPlusLanguageIdentifier() {#EmfPlusLanguageIdentifier__1}


```
 EmfPlusLanguageIdentifier() 
```

Инициализирует новый экземпляр класса EmfPlusLanguageIdentifier

