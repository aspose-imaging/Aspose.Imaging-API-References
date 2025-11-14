---
title: EmfUniversalFontId Class
type: docs
weight: 280
url: /python-net/aspose.imaging.fileformats.emf.emf.objects/emfuniversalfontid/
---

**Summary:** The UniversalFontId object defines a mechanism for identifying fonts in EMF metafiles.

**Module:** [aspose.imaging.fileformats.emf.emf.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emf.objects.EmfUniversalFontId

**Inheritance:** EmfObject

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfUniversalFontId()](#EmfUniversalFontId__1) | Initializes a new instance of the EmfUniversalFontId class |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| checksum | int | r/w | Gets or sets a 32-bit unsigned integer that is the checksum of the font.<br/>            The checksum value has the following meanings.<br/>            0x00000000  The object is a device font. <br/>            0x00000001  The object is a Type 1 font that has been installed on the client machine and is <br/>            enumerated by the PostScript printer driver as a device font. <br/>            0x00000002  The object is not a font but is a Type 1 rasterizer. <br/>            3 ≤ value   The object is a bitmap, vector, or TrueType font, or a Type 1 rasterized font that <br/>            was created by a Type 1 rasterizer. |
| index | int | r/w | Gets or sets a 32-bit unsigned integer that is an index associated with the font object. The <br/>            meaning of this field is determined by the type of font. |


### Constructor: EmfUniversalFontId() {#EmfUniversalFontId__1}


```
 EmfUniversalFontId() 
```

Initializes a new instance of the EmfUniversalFontId class

