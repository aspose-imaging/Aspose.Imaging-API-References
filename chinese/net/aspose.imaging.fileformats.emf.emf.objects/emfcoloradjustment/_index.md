---
title: "Class EmfColorAdjustment"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.Emf.Objects.EmfColorAdjustment 类。ColorAdjustment 对象定义了在位块传输中调整源位图颜色的值"
type: docs
weight: 3020
url: /zh/net/aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/
---
## EmfColorAdjustment class

ColorAdjustment 对象定义了在位块传输中调整源位图颜色的值。

```csharp
public sealed class EmfColorAdjustment : EmfObject
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfColorAdjustment](emfcoloradjustment/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [BlueGamma](../../aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/bluegamma/) { get; set; } | 获取或设置一个 16 位无符号整数，指定源颜色中蓝色基色的 nth 次幂伽马校正值。该值应在 2,500 到 65,000 之间。值为 10,000 表示不得执行伽马校正。 |
| [Brightness](../../aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/brightness/) { get; set; } | 获取或设置一个 16 位有符号整数，指定要应用于源对象的亮度量。该值应在 –100 到 100 之间。值为零表示不得执行亮度调整。 |
| [Colorfullness](../../aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/colorfullness/) { get; set; } | 获取或设置一个 16 位有符号整数，指定要应用于源对象的色彩饱和度量。该值应在 –100 到 100 之间。值为零表示不得执行色彩饱和度调整 |
| [Contrast](../../aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/contrast/) { get; set; } | 获取或设置一个 16 位有符号整数，指定要应用于源对象的对比度量。该值应在 –100 到 100 之间。值为零表示不得执行对比度调整。 |
| [GreenGamma](../../aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/greengamma/) { get; set; } | 获取或设置一个 16 位无符号整数，指定源颜色中绿色基色的 nth 次幂伽马校正值。该值应在 2,500 到 65,000 之间。值为 10,000 表示不得执行伽马校正。 |
| [IlluminantIndex](../../aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/illuminantindex/) { get; set; } | 获取或设置一个 16 位无符号整数，指定图像观看时的标准光源类型，取自 Illuminant 枚举（第 2.1.19 节）。 |
| [RedGamma](../../aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/redgamma/) { get; set; } | 获取或设置一个 16 位无符号整数，指定源颜色中红色基色的 nth 次幂伽马校正值。该值应在 2,500 到 65,000 之间。值为 10,000 表示不得执行伽马校正。 |
| [RedGreenTint](../../aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/redgreentint/) { get; set; } | 获取或设置 16 位有符号整数，指定要应用于源对象的红色或绿色色调调整量。该值应在 –100 到 100 之间。正数向红色调整，负数向绿色调整。值为零表示不得执行色调调整 |
| [ReferenceBlack](../../aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/referenceblack/) { get; set; } | 获取或设置一个 16 位无符号整数，指定源颜色的黑色参考值。任何比此更暗的颜色都视为黑色。该值应在 0 到 4,000 之间 |
| [ReferenceWhite](../../aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/referencewhite/) { get; set; } | 获取或设置一个 16 位无符号整数，指定源颜色的白色参考值。任何比此更亮的颜色都视为白色。该值应在 6,000 到 10,000 之间。 |
| [Size](../../aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/size/) { get; set; } | 获取或设置一个 16 位无符号整数，指定此对象的字节大小。该值必须为 0x0018。 |
| [Values](../../aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/values/) { get; set; } | 获取或设置一个 16 位无符号整数，指定如何准备输出图像。此字段可以设为 NULL，或设为 ColorAdjustment 枚举（第 2.1.5 节）中的任意组合值。 |

### 另请参见

* class [EmfObject](../emfobject/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Objects](../../aspose.imaging.fileformats.emf.emf.objects/)
* assembly [Aspose.Imaging](../../)


