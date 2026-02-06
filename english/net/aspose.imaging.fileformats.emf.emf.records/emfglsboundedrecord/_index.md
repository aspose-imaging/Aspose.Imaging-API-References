---
title: Class EmfGlsBoundedRecord
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfGlsBoundedRecord class. The EMR_GLSBOUNDEDRECORD record specifies an OpenGL function with a bounding rectangle for output
type: docs
weight: 3840
url: /net/aspose.imaging.fileformats.emf.emf.records/emfglsboundedrecord/
---
## EmfGlsBoundedRecord class

The EMR_GLSBOUNDEDRECORD record specifies an OpenGL function with a bounding rectangle for output.

```csharp
public sealed class EmfGlsBoundedRecord : EmfOpenGlRecordType
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfGlsBoundedRecord](emfglsboundedrecord/)(EmfRecord) | Initializes a new instance of the `EmfGlsBoundedRecord` class. |

## Properties

| Name | Description |
| --- | --- |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.records/emfglsboundedrecord/bounds/) { get; set; } | Gets or sets a WMF RectL object ([MS-WMF] section 2.2.2.19) that defines a bounding rectangle, in device units, for output produced by executing the OpenGL function. |
| [CbData](../../aspose.imaging.fileformats.emf.emf.records/emfglsboundedrecord/cbdata/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies the size, in bytes, of the Data field. If this value is zero, no data is attached to this record. |
| [Data](../../aspose.imaging.fileformats.emf.emf.records/emfglsboundedrecord/data/) { get; set; } | Gets or sets an optional array of bytes of cbData length that specifies data for the OpenGL function. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | Gets or sets the size of the record |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | Gets or sets the type. |

### See Also

* class [EmfOpenGlRecordType](../emfopenglrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


