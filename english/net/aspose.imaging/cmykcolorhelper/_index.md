---
title: CmykColorHelper
second_title: Aspose.Imaging for .NET API Reference
description: 
type: docs
weight: 290
url: /net/aspose.imaging/cmykcolorhelper/
---
## CmykColorHelper class

Helper methods to work with CMYK color presented as a signed 32-bit integer value. Provides the similar API as the [`CmykColor`](../cmykcolor) struct. It's more lightweight because CMYK color is presented just as Int32 rather than structure with internal fields. Please prefer to use static methods of this class when possible instead of the deprecated [`CmykColor`](../cmykcolor) struct.

```csharp
public static class CmykColorHelper
```

## Methods

| Name | Description |
| --- | --- |
| static [FromComponents](../../aspose.imaging/cmykcolorhelper/fromcomponents)(int, int, int, int) | Creates CMYK from a 32-bit cyan, magenta, yellow and black values. |
| static [GetC](../../aspose.imaging/cmykcolorhelper/getc)(int) | Gets the cyan component value. |
| static [GetK](../../aspose.imaging/cmykcolorhelper/getk)(int) | Gets the black component value. |
| static [GetM](../../aspose.imaging/cmykcolorhelper/getm)(int) | Gets the magenta component value. |
| static [GetY](../../aspose.imaging/cmykcolorhelper/gety)(int) | Gets the yellow component value. |
| static [ToArgb](../../aspose.imaging/cmykcolorhelper/toargb)(int) | The conversion from CMYK color to ARGB color. |
| static [ToArgb](../../aspose.imaging/cmykcolorhelper/toargb)(int[]) | The conversion from CMYK colors to ARGB colors. |
| static [ToArgb32](../../aspose.imaging/cmykcolorhelper/toargb32)(int[]) | The conversion from CMYK colors to ARGB colors. |
| static [ToArgbIcc](../../aspose.imaging/cmykcolorhelper/toargbicc)(int) | The conversion from CMYK color to ARGB Color using Icc conversion with default profiles. |
| static [ToArgbIcc](../../aspose.imaging/cmykcolorhelper/toargbicc)(int[]) | The conversion from CMYK colors to ARGB colors using Icc conversion with default profiles. |
| static [ToArgbIcc](../../aspose.imaging/cmykcolorhelper/toargbicc)(int, Stream, Stream) | The conversion from CMYK color to ARGB color using Icc conversion with custom profile. |
| static [ToArgbIcc](../../aspose.imaging/cmykcolorhelper/toargbicc)(int[], Stream, Stream) | The conversion from CMYK colors to ARGB colors using Icc conversion with custom profiles. |
| static [ToCmyk](../../aspose.imaging/cmykcolorhelper/tocmyk)(Color) | The conversion from ARGB color to CMYK color. |
| static [ToCmyk](../../aspose.imaging/cmykcolorhelper/tocmyk)(Color[]) | The conversion from ARGB colors to CMYK colors. |
| static [ToCmyk](../../aspose.imaging/cmykcolorhelper/tocmyk)(int) | The conversion from ARGB color to CMYK color. |
| static [ToCmyk](../../aspose.imaging/cmykcolorhelper/tocmyk)(int[]) | The conversion from ARGB colors to CMYK colors. |
| static [ToCmykBytes](../../aspose.imaging/cmykcolorhelper/tocmykbytes)(int[], int, int) | Converts RGB to CMYK. |
| static [ToCmykIcc](../../aspose.imaging/cmykcolorhelper/tocmykicc)(Color) | The conversion from ARGB color to CMYK color using Icc conversion with default profiles. |
| static [ToCmykIcc](../../aspose.imaging/cmykcolorhelper/tocmykicc)(Color[]) | The conversion from ARGB colors to CMYK colors using Icc conversion with default profiles. |
| static [ToCmykIcc](../../aspose.imaging/cmykcolorhelper/tocmykicc)(int) | The conversion from ARGB color to CMYK color using Icc conversion with default profiles. |
| static [ToCmykIcc](../../aspose.imaging/cmykcolorhelper/tocmykicc)(int[]) | The conversion from ARGB colors to CMYK colors using Icc conversion with default profiles. |
| static [ToCmykIcc](../../aspose.imaging/cmykcolorhelper/tocmykicc)(Color, Stream, Stream) | The conversion from ARGB color to CMYK color using Icc conversion with custom profiles. |
| static [ToCmykIcc](../../aspose.imaging/cmykcolorhelper/tocmykicc)(Color[], Stream, Stream) | The conversion from ARGB colors to CMYK colors using Icc conversion with custom profiles. |
| static [ToCmykIcc](../../aspose.imaging/cmykcolorhelper/tocmykicc)(int, Stream, Stream) | The conversion from ARGB color to CMYK color using Icc conversion with custom profiles. |
| static [ToCmykIcc](../../aspose.imaging/cmykcolorhelper/tocmykicc)(int[], Stream, Stream) | The conversion from ARGB colors to CMYK colors using Icc conversion with custom profiles. |
| static [ToCmykIccBytes](../../aspose.imaging/cmykcolorhelper/tocmykiccbytes)(int[], int, int, Stream, Stream) | Converts RGB to CMYK using custom ICC profiles. |
| static [ToPsdCmykIcc](../../aspose.imaging/cmykcolorhelper/topsdcmykicc)(int) | The conversion from ARGB color to CMYK color using Icc conversion with default profiles. Uses PSD CMYK format KCMY byte order with inverted channel values. |
| static [ToPsdCmykIcc](../../aspose.imaging/cmykcolorhelper/topsdcmykicc)(int[]) | The conversion from ARGB colors to CMYK colors using Icc conversion with default profiles. Uses PSD CMYK format KCMY byte order with inverted channel values. |
| static [ToPsdCmykIcc](../../aspose.imaging/cmykcolorhelper/topsdcmykicc)(int, Stream, Stream) | The conversion from ARGB color to CMYK color using Icc conversion with custom profiles. |
| static [ToPsdCmykIcc](../../aspose.imaging/cmykcolorhelper/topsdcmykicc)(int[], Stream, Stream) | The conversion from ARGB colors to CMYK colors using Icc conversion with custom profiles. Uses PSD CMYK format KCMY byte order with inverted channel values. |

### See Also

* namespace [Aspose.Imaging](../../aspose.imaging)
* assembly [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
