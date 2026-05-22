---
title: "TiffStreamFactory.GetTiffReader"
second_title: "Aspose.Imaging for .NET API 参考"
description: "TiffStreamFactory 方法。 获取 tiff 流读取器"
type: docs
weight: 10
url: /zh/net/aspose.imaging.fileformats.tiff.filemanagement/tiffstreamfactory/gettiffreader/
---
## GetTiffReader(StreamContainer, TiffByteOrder, bool) {#gettiffreader}

获取 tiff 流读取器。

```csharp
public static TiffStreamReader GetTiffReader(StreamContainer stream, TiffByteOrder byteOrder, 
    bool isBigTiff = false)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | StreamContainer | 流容器。 |
| byteOrder | TiffByteOrder | 字节顺序。 |
| isBigTiff | Boolean | 指示 TIFF 类型。 |

### 返回值

适用于读取的 Tiff 流。

### 另请参见

* class [TiffStreamReader](../../tiffstreamreader/)
* class [StreamContainer](../../../aspose.imaging/streamcontainer/)
* enum [TiffByteOrder](../../../aspose.imaging.fileformats.tiff.enums/tiffbyteorder/)
* class [TiffStreamFactory](../)
* namespace [Aspose.Imaging.FileFormats.Tiff.FileManagement](../../tiffstreamfactory/)
* assembly [Aspose.Imaging](../../../)

---

## GetTiffReader(byte[], int, int, TiffByteOrder, bool) {#gettiffreader_1}

获取 tiff 流读取器。

```csharp
public static TiffStreamReader GetTiffReader(byte[] bytes, int bytesOffset, int dataLength, 
    TiffByteOrder byteOrder, bool isBigTiff = false)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| bytes | Byte[] | 字节。 |
| bytesOffset | Int32 | 字节偏移。 |
| dataLength | Int32 | 数据的长度。 |
| byteOrder | TiffByteOrder | 字节顺序。 |
| isBigTiff | Boolean | 指示 Tiff 类型：原始或大。 |

### 返回值

适用于读取的 Tiff 流。

### 另请参见

* class [TiffStreamReader](../../tiffstreamreader/)
* enum [TiffByteOrder](../../../aspose.imaging.fileformats.tiff.enums/tiffbyteorder/)
* class [TiffStreamFactory](../)
* namespace [Aspose.Imaging.FileFormats.Tiff.FileManagement](../../tiffstreamfactory/)
* assembly [Aspose.Imaging](../../../)


