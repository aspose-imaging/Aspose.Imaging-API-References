---
title: Class EmfCreateDibPatternBrushPt
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfCreateDibPatternBrushPt class. The EMR_CREATEDIBPATTERNBRUSHPT record defines a pattern brush for graphics operations. The pattern is specified by a DIB
type: docs
weight: 3590
url: /net/aspose.imaging.fileformats.emf.emf.records/emfcreatedibpatternbrushpt/
---
## EmfCreateDibPatternBrushPt class

The EMR_CREATEDIBPATTERNBRUSHPT record defines a pattern brush for graphics operations. The pattern is specified by a DIB.

```csharp
public sealed class EmfCreateDibPatternBrushPt : EmfObjectCreationRecordType
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfCreateDibPatternBrushPt](emfcreatedibpatternbrushpt/#constructor)() | Initializes a new instance of the `EmfCreateDibPatternBrushPt` class. |
| [EmfCreateDibPatternBrushPt](emfcreatedibpatternbrushpt/#constructor_1)(EmfRecord) | Initializes a new instance of the `EmfCreateDibPatternBrushPt` class. |

## Properties

| Name | Description |
| --- | --- |
| [BitmapBuffer](../../aspose.imaging.fileformats.emf.emf.records/emfcreatedibpatternbrushpt/bitmapbuffer/) { get; set; } | Gets or sets a buffer containing a packed DIB in the form of a WMF DeviceIndependentBitmap object ([MS-WMF] section 2.2.2.9). It is not required to be contiguous with the fixed portion of the EMR_CREATEDIBPATTERNBRUSHPT record. |
| [IhBrush](../../aspose.imaging.fileformats.emf.emf.records/emfcreatedibpatternbrushpt/ihbrush/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies the index of the pattern brush object in the EMF Object Table (section 3.1.1.1). This index MUST be saved so that this object can be reused or modified. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | Gets or sets the size of the record |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | Gets or sets the type. |
| [Usage](../../aspose.imaging.fileformats.emf.emf.records/emfcreatedibpatternbrushpt/usage/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies how to interpret values in the color table in the DIB header. This value MUST be in the DIBColors enumeration (section 2.1.9). |

## Remarks

The pattern brush object defined by this record can be selected into the playback device context by an EMR_SELECTOBJECT record (section 2.3.8.5), which specifies the pattern brush to use in subsequent graphics operations.

### See Also

* class [EmfObjectCreationRecordType](../emfobjectcreationrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


