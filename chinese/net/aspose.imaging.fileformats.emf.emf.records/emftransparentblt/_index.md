---
title: "类 EmfTransparentBlt"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfTransparentBlt 类。EMR_TRANSPARENTBLT 记录指定将像素块从源位图传输到目标矩形的操作，将指定颜色视为透明，并在必要时拉伸或压缩输出以适应目标的尺寸。"
type: docs
weight: 4760
url: /zh/net/aspose.imaging.fileformats.emf.emf.records/emftransparentblt/
---
## EmfTransparentBlt class

该 EMR_TRANSPARENTBLT 记录指定将像素块从源位图传输到目标矩形，将指定颜色视为透明，并在必要时拉伸或压缩输出以适应目标的尺寸。

```csharp
public sealed class EmfTransparentBlt : EmfBitmapRecordType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfTransparentBlt](emftransparentblt/)(EmfRecord) | 初始化 `EmfTransparentBlt` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.records/emftransparentblt/bounds/) { get; set; } | 获取或设置 WMF RectL 对象（[MS-WMF] 第 2.2.2.19 节），该对象以设备单位定义目标边界矩形。 |
| [CxDest](../../aspose.imaging.fileformats.emf.emf.records/emftransparentblt/cxdest/) { get; set; } | 获取或设置一个 32 位有符号整数，指定目标矩形的逻辑宽度。 |
| [CxSrc](../../aspose.imaging.fileformats.emf.emf.records/emftransparentblt/cxsrc/) { get; set; } | 获取或设置一个 32 位有符号整数，指定源矩形的逻辑宽度。 |
| [CyDest](../../aspose.imaging.fileformats.emf.emf.records/emftransparentblt/cydest/) { get; set; } | 获取或设置一个 32 位有符号整数，指定目标矩形的逻辑高度。 |
| [CySrc](../../aspose.imaging.fileformats.emf.emf.records/emftransparentblt/cysrc/) { get; set; } | 获取或设置一个 32 位有符号整数，指定源矩形的逻辑高度。 |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | 获取或设置记录的大小 |
| [SourceBitmap](../../aspose.imaging.fileformats.emf.emf.records/emftransparentblt/sourcebitmap/) { get; set; } | 获取或设置包含源位图的缓冲区，该缓冲区不需要与 EMR_TRANSPARENTBLT 记录的固定部分连续。因此，缓冲区中标记为 "UndefinedSpace" 的字段是可选的，必须被忽略。 |
| [SrcBkArgb32Color](../../aspose.imaging.fileformats.emf.emf.records/emftransparentblt/srcbkargb32color/) { get; set; } | 获取或设置一个 WMF ColorRef 对象，指定源位图的背景颜色。 |
| [TransparentArgb32Color](../../aspose.imaging.fileformats.emf.emf.records/emftransparentblt/transparentargb32color/) { get; set; } | 获取或设置一个 WMF ColorRef 对象（[MS-WMF] 第 2.2.2.8 节），指定源位图中应视为透明的颜色。 |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | 获取或设置类型。 |
| [UsageSrc](../../aspose.imaging.fileformats.emf.emf.records/emftransparentblt/usagesrc/) { get; set; } | 获取或设置一个 32 位无符号整数，用于指定如何解释源位图标题中颜色表的值。此值必须属于 DIBColors 枚举（第 2.1.9 节） |
| [XDest](../../aspose.imaging.fileformats.emf.emf.records/emftransparentblt/xdest/) { get; set; } | 获取或设置一个 32 位有符号整数，指定目标矩形左上角的逻辑 x 坐标。 |
| [XformSrc](../../aspose.imaging.fileformats.emf.emf.records/emftransparentblt/xformsrc/) { get; set; } | 获取或设置 XForm 对象（第 2.2.28 节），该对象指定要应用于源位图的世界空间到页面空间的变换。 |
| [XSrc](../../aspose.imaging.fileformats.emf.emf.records/emftransparentblt/xsrc/) { get; set; } | 获取或设置一个 32 位有符号整数，指定源矩形左上角的逻辑 x 坐标。 |
| [YDest](../../aspose.imaging.fileformats.emf.emf.records/emftransparentblt/ydest/) { get; set; } | 获取或设置一个 32 位有符号整数，指定目标矩形左上角的逻辑 y 坐标。 |
| [YSrc](../../aspose.imaging.fileformats.emf.emf.records/emftransparentblt/ysrc/) { get; set; } | 获取或设置一个 32 位有符号整数，指定源矩形的逻辑 y 坐标。 |

### 另请参见

* class [EmfBitmapRecordType](../emfbitmaprecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


