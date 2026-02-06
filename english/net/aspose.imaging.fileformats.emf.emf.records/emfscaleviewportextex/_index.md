---
title: Class EmfScaleViewportExtex
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfScaleViewportExtex class. The EMR_SCALEVIEWPORTEXTEX record respecifies the viewport for a device context by using the ratios formed by the specified multiplicands and divisors
type: docs
weight: 4340
url: /net/aspose.imaging.fileformats.emf.emf.records/emfscaleviewportextex/
---
## EmfScaleViewportExtex class

The EMR_SCALEVIEWPORTEXTEX record respecifies the viewport for a device context by using the ratios formed by the specified multiplicands and divisors.

```csharp
public sealed class EmfScaleViewportExtex : EmfStateRecordType
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfScaleViewportExtex](emfscaleviewportextex/#constructor)() | Initializes a new instance of the `EmfScaleViewportExtex` class. |
| [EmfScaleViewportExtex](emfscaleviewportextex/#constructor_1)(EmfRecord) | Initializes a new instance of the `EmfScaleViewportExtex` class. |

## Properties

| Name | Description |
| --- | --- |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | Gets or sets the size of the record |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | Gets or sets the type. |
| [XDenom](../../aspose.imaging.fileformats.emf.emf.records/emfscaleviewportextex/xdenom/) { get; set; } | Gets or sets a 32-bit signed integer that specifies the horizontal divisor. Cannot be zero. |
| [XNum](../../aspose.imaging.fileformats.emf.emf.records/emfscaleviewportextex/xnum/) { get; set; } | Gets or sets a 32-bit signed integer that specifies the horizontal multiplicand. Cannot be zero. |
| [YDenom](../../aspose.imaging.fileformats.emf.emf.records/emfscaleviewportextex/ydenom/) { get; set; } | Gets or sets a 32-bit signed integer that specifies the vertical divisor. Cannot be zero. |
| [YNum](../../aspose.imaging.fileformats.emf.emf.records/emfscaleviewportextex/ynum/) { get; set; } | Gets or sets a 32-bit signed integer that specifies the vertical multiplicand. Cannot be zero. |

## Remarks

The extent cannot be changed if the device context is using a fixed scale mapping mode. Only MM_ISOTROPIC and MM_ANISOTROPIC are not fixed scale. The viewport extents are modified as follows. xNewWE = (xOldWE * xNum) / xDenom yNewWE = (yOldWE * yNum) / yDenom

### See Also

* class [EmfStateRecordType](../emfstaterecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


