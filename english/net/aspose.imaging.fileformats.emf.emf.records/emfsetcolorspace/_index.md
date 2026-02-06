---
title: Class EmfSetColorSpace
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfSetColorSpace class. The EMR_SETCOLORSPACE record defines the current logical color space object for graphics operations
type: docs
weight: 4440
url: /net/aspose.imaging.fileformats.emf.emf.records/emfsetcolorspace/
---
## EmfSetColorSpace class

The EMR_SETCOLORSPACE record defines the current logical color space object for graphics operations.

```csharp
public sealed class EmfSetColorSpace : EmfObjectManipulationRecordType
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfSetColorSpace](emfsetcolorspace/)(EmfRecord) | Initializes a new instance of the `EmfSetColorSpace` class. |

## Properties

| Name | Description |
| --- | --- |
| [IhCS](../../aspose.imaging.fileformats.emf.emf.records/emfsetcolorspace/ihcs/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies the index of a logical color space object in the EMF Object Table (section 3.1.1.1). |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | Gets or sets the size of the record |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | Gets or sets the type. |

## Remarks

The logical color space object defined by this record MUST be used in drawing operations that are specified by subsequent EMF records, until either a different logical color space object is specified by another EMR_SETCOLORSPACE record, or the object is removed by a EMR_DELETECOLORSPACE record.

### See Also

* class [EmfObjectManipulationRecordType](../emfobjectmanipulationrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


