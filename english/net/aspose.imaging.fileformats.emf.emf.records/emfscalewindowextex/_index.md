---
title: Class EmfScaleWindowExtex
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfScaleWindowExtex class. The EMR_SCALEWINDOWEXTEX record respecifies the window for a playback device context by using the ratios formed by the specified multiplicands and divisors
type: docs
weight: 4350
url: /net/aspose.imaging.fileformats.emf.emf.records/emfscalewindowextex/
---
## EmfScaleWindowExtex class

The EMR_SCALEWINDOWEXTEX record respecifies the window for a playback device context by using the ratios formed by the specified multiplicands and divisors.

```csharp
public sealed class EmfScaleWindowExtex : EmfStateRecordType
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfScaleWindowExtex](emfscalewindowextex/#constructor)() | Initializes a new instance of the `EmfScaleWindowExtex` class. |
| [EmfScaleWindowExtex](emfscalewindowextex/#constructor_1)(EmfRecord) | Initializes a new instance of the `EmfScaleWindowExtex` class. |

## Properties

| Name | Description |
| --- | --- |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | Gets or sets the size of the record |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | Gets or sets the type. |
| [XDenom](../../aspose.imaging.fileformats.emf.emf.records/emfscalewindowextex/xdenom/) { get; set; } | Gets or sets a 32-bit signed integer that specifies the horizontal divisor. MUST NOT be zero. |
| [XNum](../../aspose.imaging.fileformats.emf.emf.records/emfscalewindowextex/xnum/) { get; set; } | Gets or sets a 32-bit signed integer that specifies the horizontal multiplicand. MUST NOT be zero. |
| [YDenom](../../aspose.imaging.fileformats.emf.emf.records/emfscalewindowextex/ydenom/) { get; set; } | Gets or sets a 32-bit signed integer that specifies the vertical divisor. MUST NOT be zero. |
| [YNum](../../aspose.imaging.fileformats.emf.emf.records/emfscalewindowextex/ynum/) { get; set; } | Gets or sets a 32-bit signed integer that specifies the vertical multiplicand. MUST NOT be zero. |

## Remarks

The extent cannot be changed if the device context is using a fixed scale mapping mode. Only MM_ISOTROPIC and MM_ANISOTROPIC are not fixed scale. The window extents are modified as follows. xNewWE = (xOldWE * xNum) / xDenom yNewWE = (yOldWE * yNum) / yDenom

### See Also

* class [EmfStateRecordType](../emfstaterecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


