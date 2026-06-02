---
title: "类 EmfPlusDrawImagePoints"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.EmfPlus.Records.EmfPlusDrawImagePoints 类。EmfPlusDrawImagePoints 记录指定在平行四边形内绘制缩放图像。"
type: docs
weight: 6090
url: /zh/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/
---
## EmfPlusDrawImagePoints class

EmfPlusDrawImagePoints 记录指定在平行四边形内绘制缩放图像。

```csharp
public sealed class EmfPlusDrawImagePoints : EmfPlusDrawingRecordType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfPlusDrawImagePoints](emfplusdrawimagepoints/)(EmfPlusRecord) | 初始化 `EmfPlusDrawImagePoints` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [ApplyingAnEffect](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/applyinganeffect/) { get; set; } | 获取或设置一个值，以指示是否 [applying an effect]。此位指示图像的渲染是否包括应用效果。如果设置，则必须在之前的 EmfPlusSerializableObject 记录（第 2.3.5.2 节）中指定 Effect 类的对象。 |
| [Compressed](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/compressed/) { get; set; } | 获取或设置一个值，以指示 PointData 是否已压缩。此位指示 PointData 字段是否指定压缩数据。如果设置，PointData 指定坐标空间中使用 16 位整数坐标的绝对位置。如果清除，PointData 指定坐标空间中使用 32 位浮点坐标的绝对位置。注意：如果下面的 P 标志被设置，则此标志未定义，必须被忽略。 |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize/) { get; set; } | 获取或设置一个 32 位无符号整数，必须定义随后 RecordData 字段中数据的 32 位对齐字节数。此数字不包括 12 字节的记录头。 |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags/) { get; set; } | 获取或设置一个 16 位无符号整数，包含某些记录的操作执行方式及记录结构的信息。 |
| [ImageAttributesId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/imageattributesid/) { get; set; } | 获取或设置一个 32 位无符号整数，包含可选 EmfPlusImageAttributes 对象（第 2.2.1.5 节）在 EMF+ 对象表中的索引。 |
| [ObjectId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/objectid/) { get; set; } | 获取或设置对象标识符。该标识符是 EMF+ 对象表中 EmfPlusImage 对象（第 2.2.1.4 节）的索引，指定要渲染的图像。该值必须在 0 到 63（含）之间。 |
| [PointData](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/pointdata/) { get; set; } | 获取或设置一个 Count 点数组，指定平行四边形的三个点。三个点分别代表平行四边形的左上、右上和左下角。第四个点由前三个点外推得到。SrcRect 字段指定的图像部分如果需要，应当应用缩放和剪切变换以适应平行四边形。 |
| [Relative](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/relative/) { get; set; } | 获取或设置一个值，以指示此 `EmfPlusDrawImagePoints` 是否为相对坐标。此位指示 PointData 字段是指定相对位置还是绝对位置。如果设置，PointData 中的每个元素指定相对于数组中前一个元素位置的坐标空间位置。对于 PointData 的第一个元素，假定前一个位置为坐标 (0,0)。如果清除，PointData 按 C 标志指定绝对位置。注意：如果此标志被设置，则上面的 C 标志未定义，必须被忽略。 |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size/) { get; set; } | 获取或设置一个 32 位无符号整数，指定整个记录的 32 位对齐字节数，包括 12 字节的记录头和记录特定数据。 |
| [SrcRect](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/srcrect/) { get; set; } | 获取或设置一个 EmfPlusRectF 对象（第 2.2.2.39 节），定义要渲染的图像部分。 |
| [SrcUnit](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/srcunit/) { get; set; } | 获取或设置一个 32 位有符号整数，定义 SrcRect 字段的单位。它必须是 UnitType 枚举（第 2.1.1.33 节）中的 UnitPixel 值。 |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type/) { get; } | 获取一个 16 位无符号整数，标识记录类型。 |

## 备注

EmfPlusImage 可以指定位图或元文件。图像中的颜色可以在渲染过程中进行操作。可以对其进行校正、加暗、加亮或移除。

### 另请参见

* class [EmfPlusDrawingRecordType](../emfplusdrawingrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records/)
* assembly [Aspose.Imaging](../../)


