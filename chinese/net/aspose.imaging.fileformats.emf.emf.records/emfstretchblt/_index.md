---
title: "类 EmfStretchBlt"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfStretchBlt 类。EMR_STRETCHBLT 记录指定将像素从源位图块传输到目标矩形的操作，可选地与刷子图案结合使用，根据指定的光栅操作进行拉伸或压缩，以在必要时将输出拉伸或压缩以适应目标的尺寸。"
type: docs
weight: 4710
url: /zh/net/aspose.imaging.fileformats.emf.emf.records/emfstretchblt/
---
## EmfStretchBlt class

EMR_STRETCHBLT 记录指定将像素从源位图块传输到目标矩形的操作，可选地结合画刷图案，依据指定的光栅操作，根据需要拉伸或压缩输出以适应目标的尺寸。

```csharp
public sealed class EmfStretchBlt : EmfBitmapRecordType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfStretchBlt](emfstretchblt/#constructor)() | 初始化 `EmfStretchBlt` 类的新实例。 |
| [EmfStretchBlt](emfstretchblt/#constructor_1)(EmfRecord) | 初始化 `EmfStretchBlt` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Argb32BkColorSrc](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/argb32bkcolorsrc/) { get; set; } | 获取或设置 WMF ColorRef 对象（[MS-WMF] 第 2.2.2.8 节），该对象指定源位图的背景颜色。 |
| [BitBltRasterOperation](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/bitbltrasteroperation/) { get; set; } | 获取或设置一个 32 位无符号整数，指定光栅操作码。此代码定义如何将源矩形的颜色数据与目标矩形的颜色数据以及可选的画笔图案组合，以获得最终颜色。 |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/bounds/) { get; set; } | 获取或设置 WMF RectL 对象（[MS-WMF] 第 2.2.2.19 节），该对象以设备单位定义目标边界矩形。 |
| [CxDest](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/cxdest/) { get; set; } | 获取或设置一个 32 位有符号整数，指定目标矩形的逻辑宽度。 |
| [CxSrc](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/cxsrc/) { get; set; } | 获取或设置一个 32 位有符号整数，指定源矩形的逻辑宽度。 |
| [CyDest](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/cydest/) { get; set; } | 获取或设置一个 32 位有符号整数，指定目标矩形的逻辑高度。 |
| [CySrc](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/cysrc/) { get; set; } | 获取或设置一个 32 位有符号整数，指定源矩形的逻辑高度。 |
| [DestRect](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/destrect/) { get; set; } | 获取或设置目标矩形。 |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | 获取或设置记录的大小 |
| [SourceBitmap](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/sourcebitmap/) { get; set; } | 获取或设置包含源位图的缓冲区，该缓冲区不需要与 EMR_STRETCHBLT 记录的固定部分连续。因此，此缓冲区中标记为 "UndefinedSpace" 的字段是可选的，必须被忽略。 |
| [SrcRect](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/srcrect/) { get; set; } | 获取或设置源矩形。 |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | 获取或设置类型。 |
| [UsageSrc](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/usagesrc/) { get; set; } | 获取或设置一个 32 位无符号整数，指定如何解释源位图头部颜色表中的值。该值必须属于 DIBColors 枚举（第 2.1.9 节）。 |
| [XDest](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/xdest/) { get; set; } | 获取或设置一个 32 位有符号整数，指定目标矩形左上角的逻辑 x 坐标。 |
| [XformSrc](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/xformsrc/) { get; set; } | 获取或设置 XForm 对象（第 2.2.28 节），该对象指定要应用于源位图的世界空间到页面空间的变换。 |
| [XSrc](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/xsrc/) { get; set; } | 获取或设置一个 32 位有符号整数，指定源矩形左上角的逻辑 x 坐标。 |
| [YDest](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/ydest/) { get; set; } | 获取或设置一个 32 位有符号整数，指定目标矩形左上角的逻辑 y 坐标。 |
| [YSrc](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/ysrc/) { get; set; } | 获取或设置一个 32 位有符号整数，指定源矩形的逻辑 y 坐标。 |

### 另请参见

* class [EmfBitmapRecordType](../emfbitmaprecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


