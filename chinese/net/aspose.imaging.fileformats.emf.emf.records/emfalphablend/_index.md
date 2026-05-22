---
title: "类 EmfAlphaBlend"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfAlphaBlend 类。EMR_ALPHABLEND 记录根据指定的混合操作，指定将像素从源位图块传输到目标矩形，包括 alpha 透明度数据。"
type: docs
weight: 3290
url: /zh/net/aspose.imaging.fileformats.emf.emf.records/emfalphablend/
---
## EmfAlphaBlend class

EMR_ALPHABLEND 记录指定将像素块从源位图传输到目标矩形，包括 alpha 透明度数据，依据指定的混合操作。

```csharp
public sealed class EmfAlphaBlend : EmfBitmapRecordType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfAlphaBlend](emfalphablend/)(EmfRecord) | 初始化 `EmfAlphaBlend` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [BkSrcArgb32Color](../../aspose.imaging.fileformats.emf.emf.records/emfalphablend/bksrcargb32color/) { get; set; } | 获取或设置 WMF ColorRef 对象（[MS-WMF] 第 2.2.2.8 节），该对象指定源位图的背景颜色。 |
| [BlendFunction](../../aspose.imaging.fileformats.emf.emf.records/emfalphablend/blendfunction/) { get; set; } | 获取或设置一个结构，指定源位图和目标位图的混合操作。 |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.records/emfalphablend/bounds/) { get; set; } | 获取或设置 WMF RectL 对象（[MS-WMF] 第 2.2.2.19 节），该对象以设备单位定义目标边界矩形。 |
| [CxDest](../../aspose.imaging.fileformats.emf.emf.records/emfalphablend/cxdest/) { get; set; } | 获取或设置一个 32 位有符号整数，指定目标矩形的逻辑宽度。该值必须大于零。 |
| [CxSrc](../../aspose.imaging.fileformats.emf.emf.records/emfalphablend/cxsrc/) { get; set; } | 获取或设置一个 32 位有符号整数，指定源矩形的逻辑宽度。该值必须大于零。 |
| [CyDest](../../aspose.imaging.fileformats.emf.emf.records/emfalphablend/cydest/) { get; set; } | 获取或设置一个 32 位有符号整数，指定目标矩形的逻辑高度。该值必须大于零。 |
| [CySrc](../../aspose.imaging.fileformats.emf.emf.records/emfalphablend/cysrc/) { get; set; } | 获取或设置一个 32 位有符号整数，指定源矩形的逻辑高度。该值必须大于零。 |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | 获取或设置记录的大小 |
| [SourceBitmap](../../aspose.imaging.fileformats.emf.emf.records/emfalphablend/sourcebitmap/) { get; set; } | 获取或设置包含源位图的缓冲区，该缓冲区不需要与 EMR_ALPHABLEND 记录的固定部分连续。因此，缓冲区中标记为 "UndefinedSpace" 的字段是可选的，必须被忽略。 |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | 获取或设置类型。 |
| [UsageSrc](../../aspose.imaging.fileformats.emf.emf.records/emfalphablend/usagesrc/) { get; set; } | 获取或设置一个 32 位无符号整数，指定如何解释源位图头部颜色表中的值。该值必须属于 DIBColors 枚举（第 2.1.9 节）。 |
| [XDest](../../aspose.imaging.fileformats.emf.emf.records/emfalphablend/xdest/) { get; set; } | 获取或设置一个 32 位有符号整数，指定目标矩形左上角的逻辑 x 坐标。 |
| [XformSr](../../aspose.imaging.fileformats.emf.emf.records/emfalphablend/xformsr/) { get; set; } | 获取或设置 XForm 对象（第 2.2.28 节），该对象指定要应用于源位图的世界空间到页面空间的变换。 |
| [XSrc](../../aspose.imaging.fileformats.emf.emf.records/emfalphablend/xsrc/) { get; set; } | 获取或设置一个 32 位有符号整数，指定源矩形左上角的逻辑 x 坐标。 |
| [YDest](../../aspose.imaging.fileformats.emf.emf.records/emfalphablend/ydest/) { get; set; } | 获取或设置一个 32 位有符号整数，指定目标矩形左上角的逻辑 y 坐标。 |
| [YSrc](../../aspose.imaging.fileformats.emf.emf.records/emfalphablend/ysrc/) { get; set; } | 获取或设置一个 32 位有符号整数，指定源矩形的逻辑 y 坐标。 |

### 另请参见

* class [EmfBitmapRecordType](../emfbitmaprecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


