---
title: "类 EmfStretchDiBits"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfStretchDiBits 类。EMR_STRETCHDIBITS 记录指定将像素块从源位图传输到目标矩形的操作，可选地结合刷子图案，根据指定的光栅操作在必要时拉伸或压缩输出以适应目标的尺寸。"
type: docs
weight: 4720
url: /zh/net/aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/
---
## EmfStretchDiBits class

EMR_STRETCHDIBITS 记录指定将像素从源位图块传输到目标矩形的操作，可选地结合画刷图案，依据指定的光栅操作，根据需要拉伸或压缩输出以适应目标的尺寸。

```csharp
public sealed class EmfStretchDiBits : EmfBitmapRecordType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfStretchDiBits](emfstretchdibits/)(EmfRecord) | 初始化 `EmfStretchDiBits` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [BitBltRasterOperation](../../aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/bitbltrasteroperation/) { get; set; } | 获取或设置一个 32 位无符号整数，指定光栅操作代码。这些代码定义了如何将源矩形的颜色数据与目标矩形的颜色数据以及可选的刷子图案组合，以实现最终颜色。 |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/bounds/) { get; set; } | 获取或设置 WMF RectL 对象（[MS-WMF] 第 2.2.2.19 节），该对象以设备单位定义目标边界矩形。 |
| [CxDest](../../aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/cxdest/) { get; set; } | 获取或设置一个 32 位有符号整数，指定目标矩形的逻辑宽度。 |
| [CxSrc](../../aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/cxsrc/) { get; set; } | 获取或设置一个 32 位有符号整数，指定源矩形的像素宽度。 |
| [CyDest](../../aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/cydest/) { get; set; } | 获取或设置一个 32 位有符号整数，指定目标矩形的逻辑高度。 |
| [CySrc](../../aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/cysrc/) { get; set; } | 获取或设置一个 32 位有符号整数，指定源矩形的像素高度。 |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | 获取或设置记录的大小 |
| [SourceBitmap](../../aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/sourcebitmap/) { get; set; } | 获取或设置一个包含源位图的缓冲区，该缓冲区不需要与 EMR_STRETCHDIBITS 记录的固定部分连续。因此，缓冲区中标记为 "UndefinedSpace" 的字段是可选的，必须被忽略。 |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | 获取或设置类型。 |
| [UsageSrc](../../aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/usagesrc/) { get; set; } | 获取或设置一个 32 位无符号整数，指定如何解释源位图头部颜色表中的值。该值必须属于 DIBColors 枚举（第 2.1.9 节）。 |
| [XDest](../../aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/xdest/) { get; set; } | 获取或设置一个 32 位有符号整数，指定目标矩形左上角的逻辑 x 坐标。 |
| [XSrc](../../aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/xsrc/) { get; set; } | 获取或设置一个 32 位有符号整数，指定源矩形左上角的 x 坐标（像素）。 |
| [YDest](../../aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/ydest/) { get; set; } | 获取或设置一个 32 位有符号整数，指定目标矩形左上角的逻辑 y 坐标。 |
| [YSrc](../../aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/ysrc/) { get; set; } | 获取或设置一个 32 位有符号整数，指定源矩形左上角的 y 坐标（像素）。 |

## 备注

此记录支持 JPEG 和 PNG 格式的源图像。源位图头部的 Compression 字段指定图像格式。如果源和目标的高度或宽度字段符号不同，则此记录指定将源位图的镜像复制到目标。即，如果 cxSrc 和 cxDest 符号不同，则在 x 轴上对源位图进行镜像复制；如果 cySrc 和 cyDest 符号不同，则在 y 轴上进行镜像复制。

### 另请参见

* class [EmfBitmapRecordType](../emfbitmaprecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


