---
title: Class WmfLogColorSpaceW
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Wmf.Objects.WmfLogColorSpaceW class. The LogColorSpaceW object specifies a logical color space which can be defined by a color profile file with a name consisting of Unicode 16bit characters
type: docs
weight: 8940
url: /net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew/
---
## WmfLogColorSpaceW class

The LogColorSpaceW object specifies a logical color space, which can be defined by a color profile file with a name consisting of Unicode 16-bit characters.

```csharp
public class WmfLogColorSpaceW : MetaObject
```

## Constructors

| Name | Description |
| --- | --- |
| [WmfLogColorSpaceW](wmflogcolorspacew/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [ColorSpaceType](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew/colorspacetype/) { get; set; } | Gets or sets a 32-bit signed integer that specifies the color space type. It MUST be defined in the LogicalColorSpace enumeration (section 2.1.1.14). If this value is LCS_sRGB or LCS_WINDOWS_COLOR_SPACE, the sRGB color space MUST be used. |
| [Endpoints](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew/endpoints/) { get; set; } | Gets or sets a CIEXYZTriple object (section 2.2.2.7) that defines the CIE chromaticity x, y, and z coordinates of the three colors that correspond to the RGB endpoints for the logical color space associated with the bitmap. If the [`ColorSpaceType`](./colorspacetype/) field does not specify LCS_CALIBRATED_RGB, this field MUST be ignored. |
| [Filename](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew/filename/) { get; set; } | Gets or sets an optional, null-terminated Unicode UTF16-LE character string, which specifies the name of a file that contains a color profile. If a file name is specified, and the [`ColorSpaceType`](./colorspacetype/) field is set to LCS_CALIBRATED_RGB, the other fields of this structure SHOULD be ignored. |
| [GammaBlue](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew/gammablue/) { get; set; } | Gets or sets a 32-bit fixed point value that defines the toned response curve for blue. If the [`ColorSpaceType`](./colorspacetype/) field does not specify LCS_CALIBRATED_RGB, this field MUST be ignored. |
| [GammaGreen](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew/gammagreen/) { get; set; } | Gets or sets a 32-bit fixed point value that defines the toned response curve for green. If the [`ColorSpaceType`](./colorspacetype/) field does not specify LCS_CALIBRATED_RGB, this field MUST be ignored. |
| [GammaRed](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew/gammared/) { get; set; } | Gets or sets a 32-bit fixed point value that defines the toned response curve for red. If the [`ColorSpaceType`](./colorspacetype/) field does not specify LCS_CALIBRATED_RGB, this field MUST be ignored. |
| [Intent](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew/intent/) { get; set; } | Gets or sets a 32-bit signed integer that defines the gamut mapping intent. It MUST be defined in the GamutMappingIntent enumeration (section 2.1.1.11). |
| [Signature](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew/signature/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies the signature of color space objects; it MUST be set to the value 0x50534F43, which is the ASCII encoding of the string "PSOC". |
| [Size](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew/size/) { get; set; } | Gets or sets a 32-bit unsigned integer that defines the size of this object, in bytes. |
| [Version](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew/version/) { get; set; } | Gets or sets a 32-bit unsigned integer that defines a version number; it MUST be0x00000400. |

## Remarks

See the [`WmfLogColorSpace`](../wmflogcolorspace/) object (section 2.2.2.11) for additional details concerning the interpretation of field values of this object.

### See Also

* class [MetaObject](../../aspose.imaging.fileformats.emf/metaobject/)
* namespace [Aspose.Imaging.FileFormats.Wmf.Objects](../../aspose.imaging.fileformats.wmf.objects/)
* assembly [Aspose.Imaging](../../)


