---
title: "类 TiffUnknownType"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Tiff.TiffTagTypes.TiffUnknownType 类。未知的 tiff 类型。如果无法识别 tiff 标记，则实例化此类型"
type: docs
weight: 8230
url: /zh/net/aspose.imaging.fileformats.tiff.tifftagtypes/tiffunknowntype/
---
## TiffUnknownType class

未知的 tiff 类型。如果无法识别 tiff 标记，则实例化此类型。

```csharp
public sealed class TiffUnknownType : TiffDataType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [TiffUnknownType](tiffunknowntype/)(TiffStreamReader, ushort, ushort, ulong, ulong) | 初始化 `TiffUnknownType` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| override [Count](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffunknowntype/count/) { get; } | 获取元素的计数。 |
| virtual [DataSize](../../aspose.imaging.fileformats.tiff/tiffdatatype/datasize/) { get; } | 获取标签值的大小。 |
| virtual [ElementSize](../../aspose.imaging.fileformats.tiff/tiffdatatype/elementsize/) { get; } | 获取元素的字节大小。 |
| [Id](../../aspose.imaging.fileformats.tiff/tiffdatatype/id/) { get; } | 获取标签 ID（数字）。 |
| [IsValid](../../aspose.imaging.fileformats.tiff/tiffdatatype/isvalid/) { get; } | 获取一个值，指示标签数据是否有效。有效的标签包含可保留的数据。无效的标签无法存储。 |
| [OffsetOrValue](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffunknowntype/offsetorvalue/) { get; } | 获取附加数据的偏移值，或在计数为 1 时获取值本身。 |
| [Stream](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffunknowntype/stream/) { get; } | 获取用于读取附加数据的流。 |
| [TagId](../../aspose.imaging.fileformats.tiff/tiffdatatype/tagid/) { get; } | 获取标签 ID。 |
| override [TagType](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffunknowntype/tagtype/) { get; } | 获取标签类型。 |
| override [Value](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffunknowntype/value/) { get; set; } | 获取或设置此数据类型包含的值。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [CompareTo](../../aspose.imaging.fileformats.tiff/tiffdatatype/compareto/)(object) | 比较当前实例与同类型的另一个对象，并返回一个整数，指示当前实例在排序顺序中是位于前、后还是与另一个对象相同位置。 |
| virtual [DeepClone](../../aspose.imaging.fileformats.tiff/tiffdatatype/deepclone/)() | 对该实例执行深度克隆。 |
| override [GetAdditionalDataSize](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffunknowntype/getadditionaldatasize/)(byte) | 获取附加标签值的字节大小（如果标签无法容纳完整的标签值）。 |
| [GetAlignedDataSize](../../aspose.imaging.fileformats.tiff/tiffdatatype/getaligneddatasize/)(byte) | 获取对齐到 4 字节（int）或 8 字节（long）边界的数据大小。 |
| override [ToString](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffunknowntype/tostring/)() | 返回表示此实例的 String。 |
| override [WriteAdditionalData](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffunknowntype/writeadditionaldata/)(TiffStreamWriter) | 写入附加标签数据。 |
| [WriteTag](../../aspose.imaging.fileformats.tiff/tiffdatatype/writetag/)(TiffStreamWriter, long) | 写入标签数据。 |

## 备注

注意 `TiffUnknownType` 不会序列化回流中。

### 另请参见

* class [TiffDataType](../../aspose.imaging.fileformats.tiff/tiffdatatype/)
* namespace [Aspose.Imaging.FileFormats.Tiff.TiffTagTypes](../../aspose.imaging.fileformats.tiff.tifftagtypes/)
* assembly [Aspose.Imaging](../../)


