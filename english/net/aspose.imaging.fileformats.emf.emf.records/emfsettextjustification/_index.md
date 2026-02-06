---
title: Class EmfSetTextJustification
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfSetTextJustification class. The EMR_SETTEXTJUSTIFICATION record specifies the amount of extra space to add to break characters for text justification
type: docs
weight: 4630
url: /net/aspose.imaging.fileformats.emf.emf.records/emfsettextjustification/
---
## EmfSetTextJustification class

The EMR_SETTEXTJUSTIFICATION record specifies the amount of extra space to add to break characters for text justification.

```csharp
public sealed class EmfSetTextJustification : EmfStateRecordType
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfSetTextJustification](emfsettextjustification/)(EmfRecord) | Initializes a new instance of the `EmfSetTextJustification` class. |

## Properties

| Name | Description |
| --- | --- |
| [NBreakCount](../../aspose.imaging.fileformats.emf.emf.records/emfsettextjustification/nbreakcount/) { get; set; } | Gets or sets a 32-bit signed integer that specifies the number of break characters. |
| [NBreakExtra](../../aspose.imaging.fileformats.emf.emf.records/emfsettextjustification/nbreakextra/) { get; set; } | Gets or sets a 32-bit signed integer that specifies the total amount of extra space, in logical units, to add. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | Gets or sets the size of the record |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | Gets or sets the type. |

## Remarks

Instead of using an EMR_SETTEXTJUSTIFICATION record, an implementation SHOULD use an EMR_EXTTEXTOUTW record (section 2.3.5.8) to perform this function.

### See Also

* class [EmfStateRecordType](../emfstaterecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


