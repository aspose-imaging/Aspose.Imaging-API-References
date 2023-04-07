---
title: WmfLogColorSpaceW Class
type: docs
weight: 360
url: /python-net/api-reference/aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew/
---

The LogColorSpaceW object specifies a logical color space, which can be<br/>                defined by a color profile file with a name consisting of Unicode 16-bit<br/>                characters.

**Namespace:** [aspose.imaging.fileformats.wmf.objects](/imaging/python-net/api-reference/aspose.imaging.fileformats.wmf.objects/)

**Full Class Name:** aspose.imaging.fileformats.wmf.objects.WmfLogColorSpaceW

**Assembly:**  Aspose.Imaging Version: 23.3.0

The WmfLogColorSpaceW type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|WmfLogColorSpaceW()|Initializes a new instance of the WmfLogColorSpaceW class|
## **Properties**
|**Name**|**Description**|
| :- | :- |
|signature|Gets or sets a 32-bit unsigned integer that specifies the<br/>                [None](/imaging/python-net/api-reference/aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew/) of color space objects; it MUST be set to<br/>                the value 0x50534F43, which is the ASCII encoding of the string<br/>                "PSOC".|
|version|Gets or sets a 32-bit unsigned integer that defines a<br/>                [None](/imaging/python-net/api-reference/aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew/) number; it MUST be0x00000400.|
|size|Gets or sets a 32-bit unsigned integer that defines the<br/>                [None](/imaging/python-net/api-reference/aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew/) of this object, in bytes.|
|color_space_type|Gets or sets a 32-bit signed integer that specifies the color space<br/>                type. It MUST be defined in the LogicalColorSpace enumeration<br/>                (section 2.1.1.14). If this value is LCS_sRGB or<br/>                LCS_WINDOWS_COLOR_SPACE, the sRGB color space MUST be used.|
|intent|Gets or sets a 32-bit signed integer that defines the gamut mapping<br/>                intent. It MUST be defined in the GamutMappingIntent enumeration<br/>                (section 2.1.1.11).|
|endpoints|Gets or sets a CIEXYZTriple object (section 2.2.2.7) that defines<br/>                the CIE chromaticity x, y, and z coordinates of the three colors<br/>                that correspond to the RGB [None](/imaging/python-net/api-reference/aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew/) for the logical<br/>                color space associated with the bitmap. If the<br/>                [color_space_type](/imaging/python-net/api-reference/aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew/) field does not specify<br/>                LCS_CALIBRATED_RGB, this field MUST be ignored.|
|gamma_red|Gets or sets a 32-bit fixed point value that defines the toned<br/>                response curve for red. If the [color_space_type](/imaging/python-net/api-reference/aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew/) field<br/>                does not specify LCS_CALIBRATED_RGB, this field MUST be ignored.|
|gamma_green|Gets or sets a 32-bit fixed point value that defines the toned<br/>                response curve for green. If the [color_space_type](/imaging/python-net/api-reference/aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew/) field<br/>                does not specify LCS_CALIBRATED_RGB, this field MUST be ignored.|
|gamma_blue|Gets or sets a 32-bit fixed point value that defines the toned<br/>                response curve for blue. If the [color_space_type](/imaging/python-net/api-reference/aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew/) field<br/>                does not specify LCS_CALIBRATED_RGB, this field MUST be ignored.|
|filename|Gets or sets an optional, null-terminated Unicode UTF16-LE character<br/>                string, which specifies the name of a file that contains a color<br/>                profile. If a file name is specified, and the<br/>                [color_space_type](/imaging/python-net/api-reference/aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew/) field is set to LCS_CALIBRATED_RGB, the<br/>                other fields of this structure SHOULD be ignored.|
