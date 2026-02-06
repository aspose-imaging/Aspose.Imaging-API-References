---
title: Class EmfPlusSetClipRect
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.EmfPlus.Records.EmfPlusSetClipRect class. The EmfPlusSetClipRect record combines the current clipping region with a rectangle
type: docs
weight: 6420
url: /net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetcliprect/
---
## EmfPlusSetClipRect class

The EmfPlusSetClipRect record combines the current clipping region with a rectangle.

```csharp
public sealed class EmfPlusSetClipRect : EmfPlusClippingRecordType
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfPlusSetClipRect](emfplussetcliprect/)(EmfPlusRecord) | Initializes a new instance of the `EmfPlusSetClipRect` class. |

## Properties

| Name | Description |
| --- | --- |
| [ClipRect](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussetcliprect/cliprect/) { get; set; } | Gets or sets an EmfPlusRectF object (section 2.2.2.39) that defines the rectangle to use in the CombineMode operation. |
| [Cm](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussetcliprect/cm/) { get; set; } | Gets or sets the CM (4 bits): Specifies the logical operation for combining two regions. See the CombineMode enumeration (section 2.1.1.4) for the meanings of the values. |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize/) { get; set; } | Gets or sets a 32-bit unsigned integer that MUST define the 32-bit–aligned number of bytes of data in the RecordData field that follows. This number does not include the 12-byte record header. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags/) { get; set; } | Gets or sets a 16-bit unsigned integer that contains information for some records on how the operation is to be performed and on the structure of the record. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies the 32-bit-aligned number of bytes in the entire record, including the 12-byte record header and record-specific data. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type/) { get; } | Gets a 16-bit unsigned integer that identifies the record type. |

### See Also

* class [EmfPlusClippingRecordType](../emfplusclippingrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records/)
* assembly [Aspose.Imaging](../../)


