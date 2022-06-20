---
title: TiffUnknownType
second_title: Aspose.Imaging for .NET API 参考
description: 未知的 tiff 类型如果无法识别 tiff 标签则实例化此类型
type: docs
weight: 8050
url: /zh/net/aspose.imaging.fileformats.tiff.tifftagtypes/tiffunknowntype/
---
## TiffUnknownType class

未知的 tiff 类型。如果无法识别 tiff 标签，则实例化此类型。

```csharp
public sealed class TiffUnknownType : TiffDataType
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [TiffUnknownType](tiffunknowntype)(TiffStreamReader, ushort, ushort, uint, uint) | 初始化[`TiffUnknownType`](../tiffunknowntype)类的新实例。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [AlignedDataSize](../../aspose.imaging.fileformats.tiff/tiffdatatype/aligneddatasize) { get; } | 获取以字节为单位的附加数据大小（如果 12 个字节不足以容纳标签数据）。 |
| override [Count](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffunknowntype/count) { get; } | 获取元素的计数。 |
| override [DataSize](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffunknowntype/datasize) { get; } | 获取以字节为单位的附加数据大小（如果 12 个字节不足以容纳标签数据）。 |
| [Id](../../aspose.imaging.fileformats.tiff/tiffdatatype/id) { get; } | 获取标签 ID 整数表示。 |
| [IsValid](../../aspose.imaging.fileformats.tiff/tiffdatatype/isvalid) { get; } | 获取标签数据是否有效的值。有效标签包含可以保留的数据。无法存储无效标签。 |
| [OffsetOrValue](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffunknowntype/offsetorvalue) { get; } | 在计数为 1 的情况下获取附加数据或值本身的偏移值。 |
| [Stream](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffunknowntype/stream) { get; } | 获取要从中读取附加数据的流。 |
| [TagId](../../aspose.imaging.fileformats.tiff/tiffdatatype/tagid) { get; } | 获取标签 ID。 |
| override [TagType](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffunknowntype/tagtype) { get; } | 获取标签类型。 |
| override [Value](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffunknowntype/value) { get; set; } | 获取或设置此数据类型包含的值。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [CompareTo](../../aspose.imaging.fileformats.tiff/tiffdatatype/compareto)(object) | 将当前实例与另一个相同类型的对象进行比较，并返回一个整数，指示当前实例在排序顺序中是在相同位置之前、之后还是出现在相同位置作为另一个对象。 |
| virtual [DeepClone](../../aspose.imaging.fileformats.tiff/tiffdatatype/deepclone)() | 执行此实例的深度克隆。 |
| override [ToString](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffunknowntype/tostring)() | 返回代表此实例的String。 |
| override [WriteAdditionalData](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffunknowntype/writeadditionaldata)(TiffStreamWriter) | 写入附加标签数据。 |
| [WriteTag](../../aspose.imaging.fileformats.tiff/tiffdatatype/writetag)(TiffStreamWriter, long) | 写入标签数据。 |

### 评论

注意[`TiffUnknownType`](../tiffunknowntype)没有序列化回来流式传输。

### 也可以看看

* class [TiffDataType](../../aspose.imaging.fileformats.tiff/tiffdatatype)
* 命名空间 [Aspose.Imaging.FileFormats.Tiff.TiffTagTypes](../../aspose.imaging.fileformats.tiff.tifftagtypes)
* 部件 [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->