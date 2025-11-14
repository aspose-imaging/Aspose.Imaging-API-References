---
title: WmfLogColorSpace Class
type: docs
weight: 380
url: /python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/
---

**Summary:** The LogColorSpace object specifies a logical color space for the<br/>                playback device context, which can be the name of a color profile in<br/>                ASCII characters.

**Module:** [aspose.imaging.fileformats.wmf.objects](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/)

**Full Name:** aspose.imaging.fileformats.wmf.objects.WmfLogColorSpace

**Inheritance:** MetaObject

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [WmfLogColorSpace()](#WmfLogColorSpace__1) | Initializes a new instance of the WmfLogColorSpace class |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| color_space_type | [WmfLogicalColorSpaceEnum](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmflogicalcolorspaceenum/) | r/w | Gets or sets a 32-bit signed integer that specifies the color space<br/>                type. It MUST be defined in the LogicalColorSpace enumeration<br/>                (section 2.1.1.14). If this value is LCS_sRGB or<br/>                LCS_WINDOWS_COLOR_SPACE, the sRGB color space MUST be used. |
| endpoints | [WmfCieXyzTriple](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfciexyztriple/) | r/w | Gets or sets a CIEXYZTriple object (section 2.2.2.7) that defines<br/>                the CIE chromaticity x, y, and z coordinates of the three colors<br/>                that correspond to the RGB [None](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/) for the logical<br/>                color space associated with the bitmap. If the<br/>                [WmfLogColorSpace.color_space_type](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/) field does not specify<br/>                LCS_CALIBRATED_RGB, this field MUST be ignored. |
| filename | string | r/w | Gets or sets an optional, ASCII charactger string that specifies the<br/>                name of a file that contains a color profile. If a file name is<br/>                specified, and the [WmfLogColorSpace.color_space_type](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/) field is set to<br/>                LCS_CALIBRATED_RGB, the other fields of this structure SHOULD be<br/>                ignored. |
| gamma_blue | int | r/w | Gets or sets a 32-bit fixed point value that defines the toned<br/>                response curve for blue. If the [WmfLogColorSpace.color_space_type](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/) field<br/>                does not specify LCS_CALIBRATED_RGB, this field MUST be ignored. |
| gamma_green | int | r/w | Gets or sets a 32-bit fixed point value that defines the toned<br/>                response curve for green. If the [WmfLogColorSpace.color_space_type](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/) field<br/>                does not specify LCS_CALIBRATED_RGB, this field MUST be ignored. |
| gamma_red | int | r/w | Gets or sets a 32-bit fixed point value that defines the toned<br/>                response curve for red. If the [WmfLogColorSpace.color_space_type](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/) field<br/>                does not specify LCS_CALIBRATED_RGB, this field MUST be ignored. |
| intent | [WmfGamutMappingIntent](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfgamutmappingintent/) | r/w | Gets or sets a 32-bit signed integer that defines the gamut mapping<br/>                intent. It MUST be defined in the GamutMappingIntent enumeration<br/>                (section 2.1.1.11). |
| signature | int | r/w | Gets or sets a 32-bit unsigned integer that specifies the<br/>                [None](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/) of color space objects; it MUST be set to<br/>                the value 0x50534F43, which is the ASCII encoding of the string<br/>                "PSOC". |
| size | int | r/w | Gets or sets a 32-bit unsigned integer that defines the<br/>                [None](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/) of this object, in bytes. |
| version | int | r/w | Gets or sets a 32-bit unsigned integer that defines a<br/>                [None](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/) number; it MUST be0x00000400. |


### Constructor: WmfLogColorSpace() {#WmfLogColorSpace__1}


```
 WmfLogColorSpace() 
```

Initializes a new instance of the WmfLogColorSpace class

