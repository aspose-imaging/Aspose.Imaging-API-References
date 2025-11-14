---
title: WmfLogColorSpaceW Class
type: docs
weight: 390
url: /python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew/
---

**Summary:** The LogColorSpaceW object specifies a logical color space, which can be<br/>                defined by a color profile file with a name consisting of Unicode 16-bit<br/>                characters.

**Module:** [aspose.imaging.fileformats.wmf.objects](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/)

**Full Name:** aspose.imaging.fileformats.wmf.objects.WmfLogColorSpaceW

**Inheritance:** MetaObject

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [WmfLogColorSpaceW()](#WmfLogColorSpaceW__1) | Initializes a new instance of the WmfLogColorSpaceW class |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| color_space_type | [WmfLogicalColorSpaceEnum](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmflogicalcolorspaceenum/) | r/w | Gets or sets a 32-bit signed integer that specifies the color space<br/>                type. It MUST be defined in the LogicalColorSpace enumeration<br/>                (section 2.1.1.14). If this value is LCS_sRGB or<br/>                LCS_WINDOWS_COLOR_SPACE, the sRGB color space MUST be used. |
| endpoints | [WmfCieXyzTriple](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfciexyztriple/) | r/w | Gets or sets a CIEXYZTriple object (section 2.2.2.7) that defines<br/>                the CIE chromaticity x, y, and z coordinates of the three colors<br/>                that correspond to the RGB [None](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew/) for the logical<br/>                color space associated with the bitmap. If the<br/>                [WmfLogColorSpaceW.color_space_type](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew/) field does not specify<br/>                LCS_CALIBRATED_RGB, this field MUST be ignored. |
| filename | string | r/w | Gets or sets an optional, null-terminated Unicode UTF16-LE character<br/>                string, which specifies the name of a file that contains a color<br/>                profile. If a file name is specified, and the<br/>                [WmfLogColorSpaceW.color_space_type](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew/) field is set to LCS_CALIBRATED_RGB, the<br/>                other fields of this structure SHOULD be ignored. |
| gamma_blue | int | r/w | Gets or sets a 32-bit fixed point value that defines the toned<br/>                response curve for blue. If the [WmfLogColorSpaceW.color_space_type](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew/) field<br/>                does not specify LCS_CALIBRATED_RGB, this field MUST be ignored. |
| gamma_green | int | r/w | Gets or sets a 32-bit fixed point value that defines the toned<br/>                response curve for green. If the [WmfLogColorSpaceW.color_space_type](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew/) field<br/>                does not specify LCS_CALIBRATED_RGB, this field MUST be ignored. |
| gamma_red | int | r/w | Gets or sets a 32-bit fixed point value that defines the toned<br/>                response curve for red. If the [WmfLogColorSpaceW.color_space_type](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew/) field<br/>                does not specify LCS_CALIBRATED_RGB, this field MUST be ignored. |
| intent | [WmfGamutMappingIntent](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfgamutmappingintent/) | r/w | Gets or sets a 32-bit signed integer that defines the gamut mapping<br/>                intent. It MUST be defined in the GamutMappingIntent enumeration<br/>                (section 2.1.1.11). |
| signature | int | r/w | Gets or sets a 32-bit unsigned integer that specifies the<br/>                [None](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew/) of color space objects; it MUST be set to<br/>                the value 0x50534F43, which is the ASCII encoding of the string<br/>                "PSOC". |
| size | int | r/w | Gets or sets a 32-bit unsigned integer that defines the<br/>                [None](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew/) of this object, in bytes. |
| version | int | r/w | Gets or sets a 32-bit unsigned integer that defines a<br/>                [None](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew/) number; it MUST be0x00000400. |


### Constructor: WmfLogColorSpaceW() {#WmfLogColorSpaceW__1}


```
 WmfLogColorSpaceW() 
```

Initializes a new instance of the WmfLogColorSpaceW class

