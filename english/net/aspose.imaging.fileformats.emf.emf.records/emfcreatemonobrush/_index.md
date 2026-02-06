---
title: Class EmfCreateMonoBrush
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfCreateMonoBrush class. The EMR_CREATEMONOBRUSH record defines a monochrome pattern brush for graphics operations. The pattern is specified by a monochrome DIB
type: docs
weight: 3600
url: /net/aspose.imaging.fileformats.emf.emf.records/emfcreatemonobrush/
---
## EmfCreateMonoBrush class

The EMR_CREATEMONOBRUSH record defines a monochrome pattern brush for graphics operations. The pattern is specified by a monochrome DIB.

```csharp
public sealed class EmfCreateMonoBrush : EmfObjectCreationRecordType
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfCreateMonoBrush](emfcreatemonobrush/)(EmfRecord) | Initializes a new instance of the `EmfCreateMonoBrush` class. |

## Properties

| Name | Description |
| --- | --- |
| [BitmapBuffer](../../aspose.imaging.fileformats.emf.emf.records/emfcreatemonobrush/bitmapbuffer/) { get; set; } | Gets or sets a buffer containing a packed DIB in the form of a WMF DeviceIndependentBitmap object ([MS-WMF] section 2.2.2.9). It is not required to be contiguous with the fixed portion of the EMR_CREATEDIBPATTERNBRUSHPT record. |
| [IhBrush](../../aspose.imaging.fileformats.emf.emf.records/emfcreatemonobrush/ihbrush/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies the index of the monochrome pattern brush object in the EMF Object Table (section 3.1.1.1). This index MUST be saved so that this object can be reused or modified. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | Gets or sets the size of the record |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | Gets or sets the type. |
| [Usage](../../aspose.imaging.fileformats.emf.emf.records/emfcreatemonobrush/usage/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies how to interpret values in the color table in the DIB header. This value MUST be in the DIBColors enumeration (section 2.1.9). |

### See Also

* class [EmfObjectCreationRecordType](../emfobjectcreationrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


