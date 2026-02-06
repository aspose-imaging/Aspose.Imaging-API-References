---
title: Enum TiffAlphaStorage
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Tiff.Enums.TiffAlphaStorage enum. Specifies the alpha storage for tiff documents
type: docs
weight: 7710
url: /net/aspose.imaging.fileformats.tiff.enums/tiffalphastorage/
---
## TiffAlphaStorage enumeration

Specifies the alpha storage for tiff documents.

```csharp
public enum TiffAlphaStorage : ushort
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Unspecified | `0` | The alpha is not specified and stored in the tiff file. |
| Associated | `1` | The alpha value is stored in premultiplied form. When alpha is restored there may be some rounding effects and restored value may be different from the original. |
| Unassociated | `2` | The alpha value is stored in unassociated form. That means that alpha restored is exactly the same as it was stored to the tiff. |

### See Also

* namespace [Aspose.Imaging.FileFormats.Tiff.Enums](../../aspose.imaging.fileformats.tiff.enums/)
* assembly [Aspose.Imaging](../../)


