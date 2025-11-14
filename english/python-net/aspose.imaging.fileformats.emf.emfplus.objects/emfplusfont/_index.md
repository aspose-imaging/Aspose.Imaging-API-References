---
title: EmfPlusFont Class
type: docs
weight: 330
url: /python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusfont/
---

**Summary:** The EmfPlusFont object specifies properties that determine the appearance of text, including<br/>            typeface, size, and style.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusFont

**Inheritance:** EmfPlusGraphicsObjectType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusFont()](#EmfPlusFont__1) | Initializes a new instance of the EmfPlusFont class |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| em_size | float | r/w | Gets or sets a 32-bit floating-point value that specifies the em size of the <br/>            font in units specified by the SizeUnit field. |
| family_name | string | r/w | Gets or sets a string of Length Unicode characters that contains<br/>            the name of the font family |
| font_style_flags | [EmfPlusFontStyleFlags](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusfontstyleflags/) | r/w | Gets or sets a 32-bit signed integer that specifies attributes of the<br/>            character glyphs that affect the appearance of the font, <br/>            such as bold and italic. This value MUST be composed of <br/>            FontStyle flags (section 2.1.2.4). |
| size_unit | [EmfPlusUnitType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusunittype/) | r/w | Gets or sets a 32-bit unsigned integer that specifies the units used for <br/>            the EmSize field. These are typically the units that were <br/>            employed when designing the font. The value MUST be in the<br/>             UnitType enumeration (section 2.1.1.33). |
| version | [EmfPlusGraphicsVersion](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsversion/) | r/w | Gets or sets the version. |


### Constructor: EmfPlusFont() {#EmfPlusFont__1}


```
 EmfPlusFont() 
```

Initializes a new instance of the EmfPlusFont class

