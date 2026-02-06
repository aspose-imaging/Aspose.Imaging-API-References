---
title: Enum EmfPlusCompositingQuality
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.EmfPlus.Consts.EmfPlusCompositingQuality enum. The CompositingQuality enumeration defines levels of quality for creating composite images
type: docs
weight: 4850
url: /net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluscompositingquality/
---
## EmfPlusCompositingQuality enumeration

The CompositingQuality enumeration defines levels of quality for creating composite images

```csharp
public enum EmfPlusCompositingQuality : byte
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| CompositingQualityDefault | `1` | No gamma correction is performed. Gamma correction controls the overall brightness and contrast of an image. Without gamma correction, composited images can appear too light or too dark. |
| CompositingQualityHighSpeed | `2` | No gamma correction is performed. Compositing speed is favored at the expense of quality. In terms of the result, there is no difference between this value and CompositingQualityDefault. |
| CompositingQualityHighQuality | `3` | Gamma correction is performed. Compositing quality is favored at the expense of speed. |
| CompositingQualityGammaCorrected | `4` | Enable gamma correction for higher-quality compositing with lower speed. In terms of the result, there is no difference between this value and CompositingQualityHighQuality. |
| CompositingQualityAssumeLinear | `5` | No gamma correction is performed; however, using linear values results in better quality than the default at a slightly lower speed. |

### See Also

* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Consts](../../aspose.imaging.fileformats.emf.emfplus.consts/)
* assembly [Aspose.Imaging](../../)


