---
title: "类 EmfMaskBlt"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfMaskBlt 类。EMR_MASKBLT 记录指定将像素块从源位图传输到目标矩形的操作，可选地结合画刷图案，并根据指定的前景和背景光栅操作应用颜色掩码位图。"
type: docs
weight: 3900
url: /zh/net/aspose.imaging.fileformats.emf.emf.records/emfmaskblt/
---
## EmfMaskBlt class

EMR_MASKBLT 记录指定将像素从源位图块传输到目标矩形的操作，可选地结合画刷图案并应用颜色掩码位图，依据指定的前景和背景光栅操作。

```csharp
public sealed class EmfMaskBlt : EmfBitmapRecordType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfMaskBlt](emfmaskblt/)(EmfRecord) | 初始化 `EmfMaskBlt` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Argb32BkColorSrc](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/argb32bkcolorsrc/) { get; set; } | 获取或设置 WMF ColorRef 对象（[MS-WMF] 第 2.2.2.8 节），该对象指定源位图的背景颜色。 |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/bounds/) { get; set; } | 获取或设置 WMF RectL 对象（[MS-WMF] 第 2.2.2.19 节），该对象以设备单位定义目标边界矩形。 |
| [CxDest](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/cxdest/) { get; set; } | 获取或设置一个 32 位有符号整数，指定目标矩形的逻辑宽度。 |
| [CyDest](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/cydest/) { get; set; } | 获取或设置一个 32 位有符号整数，指定目标矩形的逻辑高度。 |
| [MaskBitmap](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/maskbitmap/) { get; set; } | 获取或设置一个包含掩码位图的缓冲区，这些位图不需要与 EMR_MASKBLT 记录的固定部分或彼此连续。因此，此缓冲区中标记为 "UndefinedSpace" 的字段是可选的，必须被忽略。 |
| [Rop4](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/rop4/) { get; set; } | 获取或设置一个四元光栅操作，该操作为位图的前景色和背景色指定三元光栅操作。这些值定义了如何将源矩形的颜色数据与目标矩形的颜色数据组合。 |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | 获取或设置记录的大小 |
| [SourceBitmap](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/sourcebitmap/) { get; set; } | 获取或设置一个包含源位图的缓冲区，这些位图不需要与 EMR_MASKBLT 记录的固定部分或彼此连续。因此，此缓冲区中标记为 "UndefinedSpace" 的字段是可选的，必须被忽略。 |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | 获取或设置类型。 |
| [UsageMask](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/usagemask/) { get; set; } | 获取或设置一个 32 位无符号整数，指定如何解释掩码位图头部颜色表中的值。此值必须属于 DIBColors 枚举。 |
| [UsageSrc](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/usagesrc/) { get; set; } | 获取或设置一个 32 位无符号整数，指定如何解释源位图头部颜色表中的值。该值必须属于 DIBColors 枚举（第 2.1.9 节）。 |
| [XDest](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/xdest/) { get; set; } | 获取或设置一个 32 位有符号整数，指定目标矩形左上角的逻辑 x 坐标。 |
| [XformSrc](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/xformsrc/) { get; set; } | 获取或设置 XForm 对象（第 2.2.28 节），该对象指定要应用于源位图的世界空间到页面空间的变换。 |
| [XMask](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/xmask/) { get; set; } | 获取或设置一个 32 位有符号整数，指定掩码位图左上角的逻辑 X 坐标。 |
| [XSrc](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/xsrc/) { get; set; } | 获取或设置一个 32 位有符号整数，指定源矩形左上角的逻辑 x 坐标。 |
| [YDest](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/ydest/) { get; set; } | 获取或设置一个 32 位有符号整数，指定目标矩形左上角的逻辑 y 坐标。 |
| [YMask](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/ymask/) { get; set; } | 获取或设置一个 32 位有符号整数，指定掩码位图左上角的逻辑 Y 坐标。 |
| [YSrc](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/ysrc/) { get; set; } | 获取或设置一个 32 位有符号整数，指定源矩形的逻辑 y 坐标。 |

### 另请参见

* class [EmfBitmapRecordType](../emfbitmaprecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


