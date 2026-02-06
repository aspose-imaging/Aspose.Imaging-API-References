---
title: Class WmfLogColorSpace
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Wmf.Objects.WmfLogColorSpace class. The LogColorSpace object specifies a logical color space for the playback device context which can be the name of a color profile in ASCII characters
type: docs
weight: 8930
url: /net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/
---
## WmfLogColorSpace class

The LogColorSpace object specifies a logical color space for the playback device context, which can be the name of a color profile in ASCII characters.

```csharp
public class WmfLogColorSpace : MetaObject
```

## Constructors

| Name | Description |
| --- | --- |
| [WmfLogColorSpace](wmflogcolorspace/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [ColorSpaceType](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/colorspacetype/) { get; set; } | Gets or sets a 32-bit signed integer that specifies the color space type. It MUST be defined in the LogicalColorSpace enumeration (section 2.1.1.14). If this value is LCS_sRGB or LCS_WINDOWS_COLOR_SPACE, the sRGB color space MUST be used. |
| [Endpoints](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/endpoints/) { get; set; } | Gets or sets a CIEXYZTriple object (section 2.2.2.7) that defines the CIE chromaticity x, y, and z coordinates of the three colors that correspond to the RGB endpoints for the logical color space associated with the bitmap. If the [`ColorSpaceType`](./colorspacetype/) field does not specify LCS_CALIBRATED_RGB, this field MUST be ignored. |
| [Filename](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/filename/) { get; set; } | Gets or sets an optional, ASCII charactger string that specifies the name of a file that contains a color profile. If a file name is specified, and the [`ColorSpaceType`](./colorspacetype/) field is set to LCS_CALIBRATED_RGB, the other fields of this structure SHOULD be ignored. |
| [GammaBlue](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/gammablue/) { get; set; } | Gets or sets a 32-bit fixed point value that defines the toned response curve for blue. If the [`ColorSpaceType`](./colorspacetype/) field does not specify LCS_CALIBRATED_RGB, this field MUST be ignored. |
| [GammaGreen](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/gammagreen/) { get; set; } | Gets or sets a 32-bit fixed point value that defines the toned response curve for green. If the [`ColorSpaceType`](./colorspacetype/) field does not specify LCS_CALIBRATED_RGB, this field MUST be ignored. |
| [GammaRed](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/gammared/) { get; set; } | Gets or sets a 32-bit fixed point value that defines the toned response curve for red. If the [`ColorSpaceType`](./colorspacetype/) field does not specify LCS_CALIBRATED_RGB, this field MUST be ignored. |
| [Intent](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/intent/) { get; set; } | Gets or sets a 32-bit signed integer that defines the gamut mapping intent. It MUST be defined in the GamutMappingIntent enumeration (section 2.1.1.11). |
| [Signature](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/signature/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies the signature of color space objects; it MUST be set to the value 0x50534F43, which is the ASCII encoding of the string "PSOC". |
| [Size](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/size/) { get; set; } | Gets or sets a 32-bit unsigned integer that defines the size of this object, in bytes. |
| [Version](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/version/) { get; set; } | Gets or sets a 32-bit unsigned integer that defines a version number; it MUST be0x00000400. |

## Remarks

The Endpoints, GammaRed, GammaGreen, and GammaBlue fields are used to specify a logical color space. The Endpoints field is a CIEXYZTriple object that contains the x, y, and z values of the RGB endpoint of the color space. The relation between tri-stimulus values X,Y,Z and chromaticity values x,y,z is expressed as follows. x = X/(X+Y+Z) y = Y/(X+Y+Z) z = Z/(X+Y+Z) The GammaRed, GammaGreen, and GammaBlue fields contain values in "8.8 fixed point" format, which is a technique for representing non-integer numbers. Each value consists of a zeroextended 8-bit magnitude followed by an 8-bit fraction, with the combined 16 bits left-shifted by 8 bits. Thus, in 32-bits, the real value N.F is 00000000nnnnnnnnffffffff00000000, where "nnnnnnnn" and "ffffffff" are binary representations of N and F, respectively. For example, for the real number 10.5, nnnnnnnn would be 00001010 (binary 10) and ffffffff would be 00000101 (binary 5), and the complete 32-bit binary value would be 00000000000010100000010100000000, which is the hexadecimal value 0x0A50.

### See Also

* class [MetaObject](../../aspose.imaging.fileformats.emf/metaobject/)
* namespace [Aspose.Imaging.FileFormats.Wmf.Objects](../../aspose.imaging.fileformats.wmf.objects/)
* assembly [Aspose.Imaging](../../)


