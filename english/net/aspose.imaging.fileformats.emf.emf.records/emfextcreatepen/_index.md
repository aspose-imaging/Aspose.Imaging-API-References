---
title: Class EmfExtCreatePen
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfExtCreatePen class. The EMR_EXTCREATEPEN record defines an extended logical pen for graphics operations. An optional DIB can be specified to use as the line style
type: docs
weight: 3730
url: /net/aspose.imaging.fileformats.emf.emf.records/emfextcreatepen/
---
## EmfExtCreatePen class

The EMR_EXTCREATEPEN record defines an extended logical pen for graphics operations. An optional DIB can be specified to use as the line style.

```csharp
public sealed class EmfExtCreatePen : EmfObjectCreationRecordType
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfExtCreatePen](emfextcreatepen/#constructor)() | Initializes a new instance of the `EmfExtCreatePen` class. |
| [EmfExtCreatePen](emfextcreatepen/#constructor_1)(EmfRecord) | Initializes a new instance of the `EmfExtCreatePen` class. |

## Properties

| Name | Description |
| --- | --- |
| [BitmapBuffer](../../aspose.imaging.fileformats.emf.emf.records/emfextcreatepen/bitmapbuffer/) { get; set; } | Gets or sets an optional buffer containing a packed DIB in the form of a WMF DeviceIndependentBitmap object ([MS-WMF] section 2.2.2.9). It is not required to be contiguous with the fixed portion of the EMR_EXTCREATEPEN record |
| [Elp](../../aspose.imaging.fileformats.emf.emf.records/emfextcreatepen/elp/) { get; set; } | Gets or sets a LogPenEx object (section 2.2.20) that specifies an extended logical pen with attributes including an optional line style array. |
| [IhPen](../../aspose.imaging.fileformats.emf.emf.records/emfextcreatepen/ihpen/) { get; set; } | Gets or sets 32-bit unsigned integer that specifies the index of the extended logical pen object in the EMF Object Table (section 3.1.1.1). This index MUST be saved so that this object can be reused or modified. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | Gets or sets the size of the record |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | Gets or sets the type. |

### See Also

* class [EmfObjectCreationRecordType](../emfobjectcreationrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


