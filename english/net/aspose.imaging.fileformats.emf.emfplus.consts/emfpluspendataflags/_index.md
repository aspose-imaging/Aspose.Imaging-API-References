---
title: Enum EmfPlusPenDataFlags
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.EmfPlus.Consts.EmfPlusPenDataFlags enum. The PenData flags specify properties of graphics pens including the presence of optional data fields. These flags can be combined to specify multiple options
type: docs
weight: 5120
url: /net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluspendataflags/
---
## EmfPlusPenDataFlags enumeration

The PenData flags specify properties of graphics pens, including the presence of optional data fields. These flags can be combined to specify multiple options.

```csharp
[Flags]
public enum EmfPlusPenDataFlags
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| PenDataTransform | `1` | If set, a 2x3 transform matrix MUST be specified in the OptionalData field of an [`EmfPlusPenData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata/) object. |
| PenDataStartCap | `2` | If set, the style of a starting line cap MUST be specified in the OptionalData field of an [`EmfPlusPenData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata/) object. |
| PenDataEndCap | `4` | Indicates whether the style of an ending line cap MUST be specified in the OptionalData field of an [`EmfPlusPenData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata/) object. |
| PenDataJoin | `8` | Indicates whether a line join type MUST be specified in the OptionalData field of an [`EmfPlusPenData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata/) object. |
| PenDataMiterLimit | `10` | Indicates whether a miter limit MUST be specified in the OptionalData field of an [`EmfPlusPenData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata/) object. |
| PenDataLineStyle | `20` | Indicates whether a line style MUST be specified in the OptionalData field of an [`EmfPlusPenData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata/) object. |
| PenDataDashedLineCap | `40` | Indicates whether a dashed line cap MUST be specified in the OptionalData field of an [`EmfPlusPenData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata/) object. |
| PenDataDashedLineOffset | `80` | Indicates whether a dashed line offset MUST be specified in the OptionalData field of an [`EmfPlusPenData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata/) object. |
| PenDataDashedLine | `100` | Indicates whether an [`EmfPlusDashedLineData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusdashedlinedata/) object MUST be specified in the OptionalData field of an [`EmfPlusPenData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata/) object. |
| PenDataNonCenter | `200` | Indicates whether a pen alignment MUST be specified in the OptionalData field of an [`EmfPlusPenData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata/) object. |
| PenDataCompoundLine | `400` | Indicates whether the length and content of a [`EmfPlusCompoundLineData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluscompoundlinedata/) object are present in the OptionalData field of an [`EmfPlusPenData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata/) object. |
| PenDataCustomStartCap | `800` | Indicates whether an [`EmfPlusCustomStartCapData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomstartcapdata/) object MUST be specified in the OptionalData field of an [`EmfPlusPenData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata/) object. |
| PenDataCustomEndCap | `1000` | Indicates whether an [`EmfPlusCustomEndCapData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomendcapdata/) object MUST be specified in the OptionalData field of an [`EmfPlusPenData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata/) object. |

## Remarks

Graphics pens are specified by [`EmfPlusPen`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspen/) objects.

### See Also

* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Consts](../../aspose.imaging.fileformats.emf.emfplus.consts/)
* assembly [Aspose.Imaging](../../)


