---
title: EmfLogFontPanose Class
type: docs
weight: 160
url: /python-net/aspose.imaging.fileformats.emf.emf.objects/emflogfontpanose/
---

**Summary:** The LogFontPanose object specifies the PANOSE characteristics of a logical font.

**Module:** [aspose.imaging.fileformats.emf.emf.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emf.objects.EmfLogFontPanose

**Inheritance:** EmfLogFont

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfLogFontPanose(emf_log_font)](#EmfLogFontPanose_emf_log_font_1) | Initializes a new instance of the [EmfLogFontPanose](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emflogfontpanose/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| char_set | [WmfCharacterSet](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfcharacterset/) | r/w | Gets or sets an 8-bit unsigned integer that specifies the set of character glyphs. It MUST <br/>            be a value in the WMF CharacterSet enumeration ([MS-WMF] section 2.1.1.5). If the <br/>            character set is unknown, metafile processing SHOULD NOT attempt to translate or interpret <br/>            strings that are rendered with that font. |
| clip_precision | [WmfClipPrecisionFlags](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfclipprecisionflags/) | r/w | Gets or sets an 8-bit unsigned integer that specifies the clipping precision. The <br/>            clipping precision defines how to clip characters that are partially outside the clipping region. <br/>            It can be one or more of the WMF ClipPrecision Flags |
| culture | int | r/w | Gets or sets a 32-bit unsigned integer that MUST be set to zero and MUST be ignored. |
| escapement | int | r/w | Gets or sets a 32-bit signed integer that specifies the angle, in tenths of degrees, <br/>            between the escapement vector and the x-axis of the device. The escapement vector is <br/>            parallel to the baseline of a row of text. |
| facename | string | r/w | Gets or sets a Facename (64 bytes):  A string of no more than 32 Unicode characters that specifies the <br/>            typeface name of the font. If the length of this string is less than 32 characters, a terminating <br/>            NULL MUST be present, after which the remainder of this field MUST be ignored. |
| full_name | string | r/w | Gets or sets a string of 64 Unicode characters that defines the font's full name. If <br/>            the length of this string is less than 64 characters, a terminating NULL MUST be present, after <br/>            which the remainder of this field MUST be ignored. |
| height | int | r/w | Gets or sets a 32-bit signed integer that specifies the height, in logical units, of the font's <br/>            character cell or character. The character height value, also known as the em size, is the <br/>            character cell height value minus the internal leading value. The font mapper SHOULD <br/>            interpret the value specified in the Height field in the following manner. |
| italic | System.Byte | r/w | Gets or sets an 8-bit unsigned integer that specifies an italic font if set to 0x01; otherwise, <br/>            it MUST be set to 0x00. |
| match | int | r/w | Gets or sets This field MUST be ignored. |
| orientation | int | r/w | Gets or sets a 32-bit signed integer that specifies the angle, in tenths of degrees, <br/>            between each character's baseline and the x-axis of the device. |
| out_precision | [WmfOutPrecision](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfoutprecision/) | r/w | Gets or sets an 8-bit unsigned integer that specifies the output precision. The <br/>            output precision defines how closely the font is required to match the requested height, width, <br/>            character orientation, escapement, pitch, and font type. It MUST be a value from the WMF <br/>            OutPrecision enumeration |
| padding | int | r/w | Gets or sets a field that exists only to ensure 32-bit alignment of this structure. It MUST be ignored |
| panose | [EmfPanose](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emfpanose/) | r/w | Gets or sets a Panose object (section 2.2.21) that specifies the PANOSE characteristics <br/>            of the logical font. If all fields of this object are zero, it MUST be ignored. |
| pitch_and_family | [WmfPitchAndFamily](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfpitchandfamily/) | r/w | Gets or sets a WMF PitchAndFamily object ([MS-WMF] section 2.2.2.14) that <br/>            specifies the pitch and family of the font. Font families describe the look of a font in a general <br/>            way. They are intended for specifying a font when the specified typeface is not available. |
| quality | [WmfFontQuality](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmffontquality/) | r/w | Gets or sets an 8-bit unsigned integer that specifies the output quality. The output quality <br/>            defines how closely to attempt to match the logical-font attributes to those of an actual <br/>            physical font. It MUST be one of the values in the WMF FontQuality enumeration ([MS-WMF] <br/>            section 2.1.1.10). |
| strikeout | System.Byte | r/w | Gets or sets an 8-bit unsigned integer that specifies a strikeout font if set to 0x01; <br/>            otherwise, it MUST be set to 0x00. |
| style | string | r/w | Gets or sets a string of 32 Unicode characters that defines the font's style. If the length of <br/>            this string is less than 32 characters, a terminating NULL MUST be present, after which the <br/>            remainder of this field MUST be ignored. |
| style_size | int | r/w | Gets or sets a 32-bit unsigned integer that specifies the point size at which font <br/>            hinting is performed. If set to zero, font hinting is performed at the point size corresponding <br/>            to the Height field in the LogFont object in the LogFont field |
| underline | System.Byte | r/w | Gets or sets an 8-bit unsigned integer that specifies an underlined font if set to 0x01; <br/>            otherwise, it MUST be set to 0x00. |
| vendor_id | int | r/w | Gets or sets This field MUST be ignored. |
| version | int | r/w | Gets or sets This field MUST be ignored. |
| weight | [EmfLogFontWeight](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emflogfontweight/) | r/w | Gets or sets a 32-bit signed integer that specifies the weight of the font in the range <br/>            zero through 1000. For example, 400 is normal and 700 is bold. If this value is zero, a default <br/>            weight can be used. |
| width | int | r/w | Gets or sets a 32-bit signed integer that specifies the average width, in logical units, of <br/>            characters in the font. If the Width field value is zero, an appropriate value SHOULD be <br/>            calculated from other LogFont values to find a font that has the typographer's intended <br/>            aspect ratio |


### Constructor: EmfLogFontPanose(emf_log_font) {#EmfLogFontPanose_emf_log_font_1}


```
 EmfLogFontPanose(emf_log_font) 
```

Initializes a new instance of the [EmfLogFontPanose](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emflogfontpanose/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| emf_log_font | [EmfLogFont](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emflogfont/) | The base log font. |

