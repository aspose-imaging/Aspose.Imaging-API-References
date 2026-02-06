---
title: Class EmfDeleteColorSpace
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfDeleteColorSpace class. The EMR_DELETECOLORSPACE record deletes a logical color space object
type: docs
weight: 3630
url: /net/aspose.imaging.fileformats.emf.emf.records/emfdeletecolorspace/
---
## EmfDeleteColorSpace class

The EMR_DELETECOLORSPACE record deletes a logical color space object.

```csharp
public sealed class EmfDeleteColorSpace : EmfObjectManipulationRecordType
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfDeleteColorSpace](emfdeletecolorspace/)(EmfRecord) | Initializes a new instance of the `EmfDeleteColorSpace` class. |

## Properties

| Name | Description |
| --- | --- |
| [IhCS](../../aspose.imaging.fileformats.emf.emf.records/emfdeletecolorspace/ihcs/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies the index of a logical color space object in the EMF Object Table (section 3.1.1.1). |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | Gets or sets the size of the record |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | Gets or sets the type. |

## Remarks

An EMR_DELETEOBJECT record SHOULD be used instead of EMR_DELETECOLORSPACE to delete a logical color space object.

### See Also

* class [EmfObjectManipulationRecordType](../emfobjectmanipulationrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


