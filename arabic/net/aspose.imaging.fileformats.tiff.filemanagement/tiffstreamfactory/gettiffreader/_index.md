---
title: "TiffStreamFactory.GetTiffReader"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة TiffStreamFactory. يحصل على قارئ تدفق TIFF"
type: docs
weight: 10
url: /ar/net/aspose.imaging.fileformats.tiff.filemanagement/tiffstreamfactory/gettiffreader/
---
## GetTiffReader(StreamContainer, TiffByteOrder, bool) {#gettiffreader}

يحصل على قارئ تدفق tiff.

```csharp
public static TiffStreamReader GetTiffReader(StreamContainer stream, TiffByteOrder byteOrder, 
    bool isBigTiff = false)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | StreamContainer | حاوية الدفق. |
| byteOrder | TiffByteOrder | ترتيب البايت. |
| isBigTiff | Boolean | يشير إلى نوع TIFF. |

### قيمة الإرجاع

تدفق TIFF مناسب للقراءة.

### انظر أيضًا

* class [TiffStreamReader](../../tiffstreamreader/)
* class [StreamContainer](../../../aspose.imaging/streamcontainer/)
* enum [TiffByteOrder](../../../aspose.imaging.fileformats.tiff.enums/tiffbyteorder/)
* class [TiffStreamFactory](../)
* namespace [Aspose.Imaging.FileFormats.Tiff.FileManagement](../../tiffstreamfactory/)
* assembly [Aspose.Imaging](../../../)

---

## GetTiffReader(byte[], int, int, TiffByteOrder, bool) {#gettiffreader_1}

يحصل على قارئ تدفق tiff.

```csharp
public static TiffStreamReader GetTiffReader(byte[] bytes, int bytesOffset, int dataLength, 
    TiffByteOrder byteOrder, bool isBigTiff = false)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| bytes | Byte[] | البايتات. |
| bytesOffset | Int32 | إزاحة البايتات. |
| dataLength | Int32 | طول البيانات. |
| byteOrder | TiffByteOrder | ترتيب البايت. |
| isBigTiff | Boolean | يشير إلى نوع Tiff: أصلي أو كبير. |

### قيمة الإرجاع

تدفق TIFF مناسب للقراءة.

### انظر أيضًا

* class [TiffStreamReader](../../tiffstreamreader/)
* enum [TiffByteOrder](../../../aspose.imaging.fileformats.tiff.enums/tiffbyteorder/)
* class [TiffStreamFactory](../)
* namespace [Aspose.Imaging.FileFormats.Tiff.FileManagement](../../tiffstreamfactory/)
* assembly [Aspose.Imaging](../../../)


