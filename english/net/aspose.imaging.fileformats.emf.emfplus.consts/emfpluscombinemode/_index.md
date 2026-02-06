---
title: Enum EmfPlusCombineMode
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.EmfPlus.Consts.EmfPlusCombineMode enum. The CombineMode enumeration defines modes for combining two graphics regions. In the following descriptions the regions to be combined are referred to as the existing and new regions
type: docs
weight: 4830
url: /net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluscombinemode/
---
## EmfPlusCombineMode enumeration

The CombineMode enumeration defines modes for combining two graphics regions. In the following descriptions, the regions to be combined are referred to as the "existing" and "new" regions.

```csharp
public enum EmfPlusCombineMode : byte
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| CombineModeReplace | `0` | Replaces the existing region with the new region. |
| CombineModeIntersect | `1` | Replaces the existing region with the intersection of the existing region and the new region. |
| CombineModeUnion | `2` | Replaces the existing region with the union of the existing and new regions. |
| CombineModeXor | `3` | Replaces the existing region with the XOR of the existing and new regions. |
| CombineModeExclude | `4` | Replaces the existing region with the part of itself that is not in the new region. |
| CombineModeComplement | `5` | Replaces the existing region with the part of the new region that is not in the existing region. |

### See Also

* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Consts](../../aspose.imaging.fileformats.emf.emfplus.consts/)
* assembly [Aspose.Imaging](../../)


