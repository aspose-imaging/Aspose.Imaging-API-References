---
title: "类 EmfPlgBlt"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfPlgBlt 类。EMR_PLGBLT 记录指定将像素从源位图块传输到目标平行四边形，并应用颜色掩码位图。"
type: docs
weight: 4050
url: /zh/net/aspose.imaging.fileformats.emf.emf.records/emfplgblt/
---
## EmfPlgBlt class

EMR_PLGBLT 记录指定将像素从源位图块传输到目标平行四边形，并应用颜色掩码位图。

```csharp
public sealed class EmfPlgBlt : EmfBitmapRecordType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfPlgBlt](emfplgblt/)(EmfRecord) | 初始化 `EmfPlgBlt` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [AptlDest](../../aspose.imaging.fileformats.emf.emf.records/emfplgblt/aptldest/) { get; set; } | 获取或设置一个包含三个 WMF PointL 对象的数组（[MS-WMF] 第 2.2.2.15 节），该数组指定块传输的目标平行四边形的三个角。源矩形的左上角映射到数组中的第一个点，右上角映射到第二个点，左下角映射到第三个点。源矩形的右下角映射到平行四边形中隐含的第四点，该点通过将前三个点（A、B 和 C）视为向量计算得到。D = B + C A |
| [BkSrcArgb32Color](../../aspose.imaging.fileformats.emf.emf.records/emfplgblt/bksrcargb32color/) { get; set; } | 获取或设置一个 WMF ColorRef 对象（[MS-WMF] 第 2.2.2.8 节），该对象指定源位图的背景颜色。 |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.records/emfplgblt/bounds/) { get; set; } | 获取或设置一个 WMF RectL 对象（[MS-WMF] 第 2.2.2.19 节），该对象以设备单位定义输出到目标的边界矩形。 |
| [CxSrc](../../aspose.imaging.fileformats.emf.emf.records/emfplgblt/cxsrc/) { get; set; } | 获取或设置一个 32 位有符号整数，指定源矩形的逻辑宽度。 |
| [CySrc](../../aspose.imaging.fileformats.emf.emf.records/emfplgblt/cysrc/) { get; set; } | 获取或设置一个 32 位有符号整数，指定源矩形的逻辑高度。 |
| [MaskBitmap](../../aspose.imaging.fileformats.emf.emf.records/emfplgblt/maskbitmap/) { get; set; } | 获取或设置包含掩码位图的缓冲区，该缓冲区不需要与 EMR_PLGBLT 记录的固定部分或彼此连续。因此，此缓冲区中标记为 "UndefinedSpace" 的字段是可选的，必须被忽略。 |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | 获取或设置记录的大小 |
| [SourceBitmap](../../aspose.imaging.fileformats.emf.emf.records/emfplgblt/sourcebitmap/) { get; set; } | 获取或设置包含源位图的缓冲区，该缓冲区不需要与 EMR_PLGBLT 记录的固定部分或彼此连续。因此，此缓冲区中标记为 "UndefinedSpace" 的字段是可选的，必须被忽略。 |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | 获取或设置类型。 |
| [UsageMask](../../aspose.imaging.fileformats.emf.emf.records/emfplgblt/usagemask/) { get; set; } | 获取或设置一个 32 位无符号整数，指定如何解释掩码位图头部颜色表中的值。此值必须属于 DIBColors 枚举。 |
| [UsageSrc](../../aspose.imaging.fileformats.emf.emf.records/emfplgblt/usagesrc/) { get; set; } | 获取或设置一个 32 位无符号整数，指定如何解释源位图头部颜色表中的值。该值必须属于 DIBColors 枚举。 |
| [XFormSrc](../../aspose.imaging.fileformats.emf.emf.records/emfplgblt/xformsrc/) { get; set; } | 获取或设置 XForm 对象（第 2.2.28 节），该对象指定要应用于源位图的世界空间到页面空间的变换。 |
| [XMask](../../aspose.imaging.fileformats.emf.emf.records/emfplgblt/xmask/) { get; set; } | 获取或设置一个 32 位有符号整数，指定掩码位图左上角的逻辑 X 坐标。 |
| [XSrc](../../aspose.imaging.fileformats.emf.emf.records/emfplgblt/xsrc/) { get; set; } | 获取或设置一个 32 位有符号整数，指定源矩形左上角的逻辑 x 坐标。 |
| [YMask](../../aspose.imaging.fileformats.emf.emf.records/emfplgblt/ymask/) { get; set; } | 获取或设置一个 32 位有符号整数，指定掩码位图左上角的逻辑 Y 坐标。 |
| [YSrc](../../aspose.imaging.fileformats.emf.emf.records/emfplgblt/ysrc/) { get; set; } | 获取或设置一个 32 位有符号整数，指定源矩形的逻辑 y 坐标。 |

### 另请参见

* class [EmfBitmapRecordType](../emfbitmaprecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


