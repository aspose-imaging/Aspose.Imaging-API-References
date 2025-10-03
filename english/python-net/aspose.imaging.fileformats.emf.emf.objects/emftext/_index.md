---
title: EmfText Class
type: docs
weight: 260
url: /python-net/aspose.imaging.fileformats.emf.emf.objects/emftext/
---

**Summary:** The EmrText object contains values for text output.

**Module:** [aspose.imaging.fileformats.emf.emf.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emf.objects.EmfText

**Inheritance:** EmfObject

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfText()](#EmfText__1) | Initializes a new instance of the EmfText class |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| chars | int | r/w | Gets or sets a 32-bit unsigned integer that specifies the number of characters in the string |
| dx_buffer | int[] | r/w | Gets or sets the optional character spacing buffer<br/>            UndefinedSpace2 (variable): An optional number of unused bytes. The OutputDx field is not required to <br/>            follow immediately the preceding portion of this structure.<br/>            OutputDx (variable): An array of 32-bit unsigned integers that specify the output spacing between <br/>            the origins of adjacent character cells in logical units. The location of this field is specified by <br/>            the value of offDx in bytes from the start of this record. If spacing is defined, this field contains <br/>            the same number of values as characters in the output string. If the Options field of the EmrText object <br/>            contains the ETO_PDY flag, then this buffer contains twice as many values as there are characters in <br/>            the output string, one horizontal and one vertical offset for each, in that order. If ETO_RTLREADING is specified, <br/>            characters are laid right to left instead of left to right. No other options affect the interpretation of this field. |
| glyph_index_buffer | int[] | r/w | Gets or sets the optional glyph index buffer.<br/>            If options has ETO_GLYPH_INDEX flag then the codes for characters in an output text string are actually indexes<br/>            of the character glyphs in a TrueType font (2.1.11 ExtTextOutOptions enumeration). Glyph indexes are font-specific,<br/>            so to display the correct characters on playback, the font that is used MUST be identical to the font used to<br/>            generate the indexes. |
| options | [EmfExtTextOutOptions](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfexttextoutoptions/) | r/w | Gets or sets a 32-bit unsigned integer that specifies how to use the rectangle specified in the <br/>            Rectangle field. This field can be a combination of more than one ExtTextOutOptions <br/>            enumeration (section 2.1.11) values |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Gets or sets an optional WMF RectL object ([MS-WMF] section 2.2.2.19) that defines a clipping <br/>            and/or opaquing rectangle in logical units. This rectangle is applied to the text <br/>            output performed by the containing record. |
| reference | [Point](/imaging/python-net/aspose.imaging/point/) | r/w | Gets or sets a WMF PointL object ([MS-WMF] section 2.2.2.15) that specifies the coordinates of the <br/>            reference point used to position the string. The reference point is defined by the last <br/>            EMR_SETTEXTALIGN record (section 2.3.11.25). If no such record has been set, <br/>            the default alignment is TA_LEFT,TA_TOP. |
| string_buffer | string | r/w | Gets or sets the character string buffer<br/>            UndefinedSpace1 (variable): An optional number of unused bytes. <br/>            The OutputString field is not required to follow immediately the preceding portion of this structure.<br/>            OutputString (variable): An array of characters that specify the string to output. <br/>            The location of this field is specified by the value of offString in bytes from the start of this record. <br/>            The number of characters is specified by the value of Chars. |


### Constructor: EmfText() {#EmfText__1}


```
 EmfText() 
```

Initializes a new instance of the EmfText class

