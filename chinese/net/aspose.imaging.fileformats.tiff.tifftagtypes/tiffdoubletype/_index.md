---
title: "类 TiffDoubleType"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Tiff.TiffTagTypes.TiffDoubleType 类。tiff double 类型"
type: docs
weight: 8090
url: /zh/net/aspose.imaging.fileformats.tiff.tifftagtypes/tiffdoubletype/
---
## TiffDoubleType class

tiff double 类型。

```csharp
public sealed class TiffDoubleType : TiffCommonArrayType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [TiffDoubleType](tiffdoubletype/#constructor)(TiffTags) | 初始化 `TiffDoubleType` 类的新实例。 |
| [TiffDoubleType](tiffdoubletype/#constructor_1)(ushort) | 初始化 `TiffDoubleType` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Count](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffcommonarraytype/count/) { get; } | 获取元素的计数。 |
| virtual [DataSize](../../aspose.imaging.fileformats.tiff/tiffdatatype/datasize/) { get; } | 获取标签值的大小。 |
| override [ElementSize](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffdoubletype/elementsize/) { get; } | 获取元素的字节大小。 |
| [Id](../../aspose.imaging.fileformats.tiff/tiffdatatype/id/) { get; } | 获取标签 ID（数字）。 |
| [IsValid](../../aspose.imaging.fileformats.tiff/tiffdatatype/isvalid/) { get; } | 获取一个值，指示标签数据是否有效。有效的标签包含可保留的数据。无效的标签无法存储。 |
| [TagId](../../aspose.imaging.fileformats.tiff/tiffdatatype/tagid/) { get; } | 获取标签 ID。 |
| override [TagType](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffdoubletype/tagtype/) { get; } | 获取标签类型。 |
| override [Value](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffdoubletype/value/) { get; set; } | 获取或设置此数据类型包含的值。 |
| [Values](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffdoubletype/values/) { get; set; } | 获取或设置这些值。 |
| override [ValuesContainer](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffdoubletype/valuescontainer/) { get; } | 获取值容器。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [CompareTo](../../aspose.imaging.fileformats.tiff/tiffdatatype/compareto/)(object) | 比较当前实例与同类型的另一个对象，并返回一个整数，指示当前实例在排序顺序中是位于前、后还是与另一个对象相同位置。 |
| virtual [DeepClone](../../aspose.imaging.fileformats.tiff/tiffdatatype/deepclone/)() | 对该实例执行深度克隆。 |
| virtual [GetAdditionalDataSize](../../aspose.imaging.fileformats.tiff/tiffdatatype/getadditionaldatasize/)(byte) | 获取附加标签值的字节大小（如果标签无法容纳完整的标签值）。 |
| [GetAlignedDataSize](../../aspose.imaging.fileformats.tiff/tiffdatatype/getaligneddatasize/)(byte) | 获取对齐到 4 字节（int）或 8 字节（long）边界的数据大小。 |
| override [ToString](../../aspose.imaging.fileformats.tiff/tiffdatatype/tostring/)() | 返回表示此实例的 String。 |
| override [WriteAdditionalData](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffdoubletype/writeadditionaldata/)(TiffStreamWriter) | 写入附加标签数据。 |
| [WriteTag](../../aspose.imaging.fileformats.tiff/tiffdatatype/writetag/)(TiffStreamWriter, long) | 写入标签数据。 |

### 另请参见

* class [TiffCommonArrayType](../tiffcommonarraytype/)
* namespace [Aspose.Imaging.FileFormats.Tiff.TiffTagTypes](../../aspose.imaging.fileformats.tiff.tifftagtypes/)
* assembly [Aspose.Imaging](../../)


