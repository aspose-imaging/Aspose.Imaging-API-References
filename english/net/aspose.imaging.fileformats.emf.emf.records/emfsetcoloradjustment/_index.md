---
title: Class EmfSetColorAdjustment
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfSetColorAdjustment class. The EMR_SETCOLORADJUSTMENT record specifies color adjustment properties in the playback device context
type: docs
weight: 4430
url: /net/aspose.imaging.fileformats.emf.emf.records/emfsetcoloradjustment/
---
## EmfSetColorAdjustment class

The EMR_SETCOLORADJUSTMENT record specifies color adjustment properties in the playback device context.

```csharp
public sealed class EmfSetColorAdjustment : EmfStateRecordType
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfSetColorAdjustment](emfsetcoloradjustment/)(EmfRecord) | Initializes a new instance of the `EmfSetColorAdjustment` class. |

## Properties

| Name | Description |
| --- | --- |
| [ColorAdjustment](../../aspose.imaging.fileformats.emf.emf.records/emfsetcoloradjustment/coloradjustment/) { get; set; } | Gets or sets a ColorAdjustment object (section 2.2.2) that specifies color adjustment values. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | Gets or sets the size of the record |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | Gets or sets the type. |

## Remarks

Color adjustment values are used to adjust the input color of the source bitmap for graphics operations performed by EMR_STRETCHBLT and EMR_STRETCHDIBITS records when STRETCH_HALFTONE mode is set from the StretchMode enumeration (section 2.1.32). The ColorAdjustment object specified by this record MUST be used in graphics operations that require a ColorAdjustment object, until a different ColorAdjustment object is specified by another EMR_SETCOLORADJUSTMENT record, or until the object is removed by a EMR_DELETEOBJECT record.

### See Also

* class [EmfStateRecordType](../emfstaterecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


