---
title: Enum EmfPlusCustomLineCapDataFlags
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.EmfPlus.Consts.EmfPlusCustomLineCapDataFlags enum. The CustomLineCapData flags specify data for custom line caps. These flags can be combined to specify multiple options
type: docs
weight: 4880
url: /net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluscustomlinecapdataflags/
---
## EmfPlusCustomLineCapDataFlags enumeration

The CustomLineCapData flags specify data for custom line caps. These flags can be combined to specify multiple options.

```csharp
[Flags]
public enum EmfPlusCustomLineCapDataFlags
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| CustomLineCapDataFillPath | `1` | If set, an [`EmfPlusFillPath`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusfillpath/) object MUST be specified in the OptionalData field of the [`EmfPlusCustomLineCapData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecapdata/) object for filling the custom line cap. |
| CustomLineCapDataLinePath | `2` | If set, an [`EmfPlusLinePath`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluslinepath/) object MUST be specified in the OptionalData field of the EmfPlusCustomLineCapData object for outlining the custom line cap. |

## Remarks

Custom graphics line caps are specified by [`EmfPlusCustomLineCap`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecap/) objects.

### See Also

* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Consts](../../aspose.imaging.fileformats.emf.emfplus.consts/)
* assembly [Aspose.Imaging](../../)


