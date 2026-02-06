---
title: Class EmfPlusSetTsClip
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.EmfPlus.Records.EmfPlusSetTsClip class. The EmfPlusSetTSClip record specifies clipping areas in the graphics device context for a terminal server
type: docs
weight: 6520
url: /net/aspose.imaging.fileformats.emf.emfplus.records/emfplussettsclip/
---
## EmfPlusSetTsClip class

The EmfPlusSetTSClip record specifies clipping areas in the graphics device context for a terminal server.

```csharp
public sealed class EmfPlusSetTsClip : EmfPlusTerminalServerRecordType
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfPlusSetTsClip](emfplussettsclip/)(EmfPlusRecord) | Initializes a new instance of the `EmfPlusSetTsClip` class. |

## Properties

| Name | Description |
| --- | --- |
| [Compressed](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsclip/compressed/) { get; } | Gets a value indicating whether this `EmfPlusSetTsClip` is compressed. This bit specifies the format of the rectangle data in the rects field. If set, each rectangle is defined in 4 bytes. If clear, each rectangle is defined in 8 bytes. |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize/) { get; set; } | Gets or sets a 32-bit unsigned integer that MUST define the 32-bit–aligned number of bytes of data in the RecordData field that follows. This number does not include the 12-byte record header. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags/) { get; set; } | Gets or sets a 16-bit unsigned integer that contains information for some records on how the operation is to be performed and on the structure of the record. |
| [NumRects](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsclip/numrects/) { get; } | Gets the number rects. This field specifies the number of rectangles that are defined in the rect field. |
| [Rects](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsclip/rects/) { get; set; } | Gets or sets an array of NumRects rectangles that define clipping areas. The format of this data is determined by the C bit in the Flags field. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies the 32-bit-aligned number of bytes in the entire record, including the 12-byte record header and record-specific data. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type/) { get; } | Gets a 16-bit unsigned integer that identifies the record type. |

## Remarks

The compression scheme for data in this record uses the following algorithm. Each point of each rectangle is encoded in either a single byte or 2 bytes. If the point is encoded in a single byte, the high bit (0x80) of the byte MUST be set, and the value is a signed number represented by the lower 7 bits. If the high bit is not set, then the value is encoded in 2 bytes, with the high-order byte encoded in the 7 lower bits of the first byte, and the low-order byte value encoded in the second byte. Each point is encoded as the difference between the point in the current rect and the point in the previous rect. The bottom point of the rect is encoded as the difference between the bottom coordinate and the top coordinate on the current rect.

### See Also

* class [EmfPlusTerminalServerRecordType](../emfplusterminalserverrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records/)
* assembly [Aspose.Imaging](../../)


