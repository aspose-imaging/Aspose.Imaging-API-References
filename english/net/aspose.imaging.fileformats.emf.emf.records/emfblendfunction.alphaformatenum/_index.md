---
title: Enum EmfBlendFunction.AlphaFormatEnum
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfBlendFunctionAlphaFormatEnum enum. A structure that specifies how source and destination pixels are interpreted with respect to alpha transparency
type: docs
weight: 3370
url: /net/aspose.imaging.fileformats.emf.emf.records/emfblendfunction.alphaformatenum/
---
## EmfBlendFunction.AlphaFormatEnum enumeration

A structure that specifies how source and destination pixels are interpreted with respect to alpha transparency.

```csharp
public enum AlphaFormatEnum : byte
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| NotTransparency | `0` | The pixels in the source bitmap do not specify alpha transparency. In this case, the SrcConstantAlpha value determines the blend of the source and destination bitmaps. Note that in the following equations SrcConstantAlpha is divided by 255, which produces a value in the range 0 to 1. |
| AC_SRC_ALPHA | `1` | Indicates that the source bitmap is 32 bits-per-pixel and specifies an alpha transparency value for each pixel. |

### See Also

* struct [EmfBlendFunction](../emfblendfunction/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


