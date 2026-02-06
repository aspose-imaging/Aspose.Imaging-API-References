---
title: Class EmfCreatePen
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfCreatePen class. The EMR_CREATEPEN record defines a logical pen for graphics operations
type: docs
weight: 3620
url: /net/aspose.imaging.fileformats.emf.emf.records/emfcreatepen/
---
## EmfCreatePen class

The EMR_CREATEPEN record defines a logical pen for graphics operations.

```csharp
public sealed class EmfCreatePen : EmfObjectCreationRecordType
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfCreatePen](emfcreatepen/#constructor)() | Initializes a new instance of the `EmfCreatePen` class. |
| [EmfCreatePen](emfcreatepen/#constructor_1)(EmfRecord) | Initializes a new instance of the `EmfCreatePen` class. |

## Properties

| Name | Description |
| --- | --- |
| [IhPen](../../aspose.imaging.fileformats.emf.emf.records/emfcreatepen/ihpen/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies the index of the logical pen object in the EMF Object Table (section 3.1.1.1). This index MUST be saved so that this object can be reused or modified. |
| [LogPen](../../aspose.imaging.fileformats.emf.emf.records/emfcreatepen/logpen/) { get; set; } | Gets or sets a LogPen object (section 2.2.19) that specifies the style, width, and color of the logical pen. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | Gets or sets the size of the record |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | Gets or sets the type. |

### See Also

* class [EmfObjectCreationRecordType](../emfobjectcreationrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


