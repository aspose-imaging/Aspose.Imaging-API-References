---
title: Class EmfCreateBrushIndirect
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfCreateBrushIndirect class. The EMR_CREATEBRUSHINDIRECT record defines a logical brush for graphics operations
type: docs
weight: 3560
url: /net/aspose.imaging.fileformats.emf.emf.records/emfcreatebrushindirect/
---
## EmfCreateBrushIndirect class

The EMR_CREATEBRUSHINDIRECT record defines a logical brush for graphics operations.

The logical brush object defined by this record can be selected into the playback device context by an EMR_SELECTOBJECT record (section 2.3.8.5), which specifies the logical brush to use in subsequent graphics operations.

```csharp
public sealed class EmfCreateBrushIndirect : EmfObjectCreationRecordType
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfCreateBrushIndirect](emfcreatebrushindirect/#constructor)() | Initializes a new instance of the `EmfCreateBrushIndirect` class. |
| [EmfCreateBrushIndirect](emfcreatebrushindirect/#constructor_1)(EmfRecord) | Initializes a new instance of the `EmfCreateBrushIndirect` class. |

## Properties

| Name | Description |
| --- | --- |
| [IhBrush](../../aspose.imaging.fileformats.emf.emf.records/emfcreatebrushindirect/ihbrush/) { get; set; } | Gets or sets A 32-bit unsigned integer that specifies the index of the logical brush object in the EMF Object Table (section 3.1.1.1). This index MUST be saved so that this object can be reused or modified. |
| [LogBrush](../../aspose.imaging.fileformats.emf.emf.records/emfcreatebrushindirect/logbrush/) { get; set; } | Gets or sets A LogBrushEx object (section 2.2.12) that specifies the style, color, and pattern of the logical brush. The BrushStyle field in this object MUST be BS_SOLID, BS_HATCHED, or BS_NULL. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | Gets or sets the size of the record |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | Gets or sets the type. |

### See Also

* class [EmfObjectCreationRecordType](../emfobjectcreationrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


