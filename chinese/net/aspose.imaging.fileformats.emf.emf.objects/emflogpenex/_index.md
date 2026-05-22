---
title: "类 EmfLogPenEx"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.Emf.Objects.EmfLogPenEx 类。LogPenEx 对象指定扩展逻辑笔的样式宽度和颜色"
type: docs
weight: 3180
url: /zh/net/aspose.imaging.fileformats.emf.emf.objects/emflogpenex/
---
## EmfLogPenEx class

LogPenEx 对象指定了扩展逻辑笔的样式、宽度和颜色。

```csharp
public sealed class EmfLogPenEx : EmfBasePen
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfLogPenEx](emflogpenex/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| override [Argb32ColorRef](../../aspose.imaging.fileformats.emf.emf.objects/emflogpenex/argb32colorref/) { get; set; } | 获取或设置 WMF ColorRef 对象（[MS-WMF] 第 2.2.2.8 节）。此字段的解释取决于 BrushStyle 值，如本节后面的表所示。 |
| [BrushDibPattern](../../aspose.imaging.fileformats.emf.emf.objects/emflogpenex/brushdibpattern/) { get; set; } | 获取或设置画刷 dib 图案。 |
| [BrushHatch](../../aspose.imaging.fileformats.emf.emf.objects/emflogpenex/brushhatch/) { get; set; } | 获取或设置画刷交叉图案。此字段的定义取决于 BrushStyle 值，如本节后面的表所示。 |
| [BrushStyle](../../aspose.imaging.fileformats.emf.emf.objects/emflogpenex/brushstyle/) { get; set; } | 获取或设置一个 32 位无符号整数，指定来自 WMF BrushStyle 枚举（[MS-WMF] 第 2.1.1.4 节）的笔刷样式。如果 PenStyle 字段中的笔类型为 PS_GEOMETRIC，则此值必须是 BS_SOLID 或 BS_HATCHED。此字段的值可以是 BS_NULL，但仅当 PenStyle 中指定的线样式为 PS_NULL 时。应使用 BS_NULL 样式来指定没有效果的画刷。 |
| [NumStyleEntities](../../aspose.imaging.fileformats.emf.emf.objects/emflogpenex/numstyleentities/) { get; } | 获取 StyleEntry 字段中指定的数组的元素数量。如果 PenStyle 未指定 PS_USERSTYLE，则此值应为零。 |
| override [PenStyle](../../aspose.imaging.fileformats.emf.emf.objects/emflogpenex/penstyle/) { get; set; } | 获取或设置笔的样式 |
| [StyleEntry](../../aspose.imaging.fileformats.emf.emf.objects/emflogpenex/styleentry/) { get; set; } | 获取或设置一个可选的 32 位无符号整数数组，用于定义该笔绘制的线条中短划线和间隙的长度，当 PenStyle 的值为笔的 PS_USERSTYLE 线样式时。数组包含由 NumStyleEntries 指定的条目数量，但使用时视为无限重复。数组的第一条目指定第一段短划线的长度。第二条目指定第一段间隙的长度。此后，短划线和间隙的长度交替出现。如果 PenStyle 字段中的笔类型为 PS_GEOMETRIC，则长度以逻辑单位指定；否则，以设备单位指定。 |
| [Width](../../aspose.imaging.fileformats.emf.emf.objects/emflogpenex/width/) { get; set; } | 获取或设置一个 32 位无符号整数，指定笔绘制的线宽。如果 PenStyle 字段中的笔类型为 PS_GEOMETRIC，则该值为逻辑单位的宽度；否则，宽度以设备单位指定。如果 PenStyle 字段中的笔类型为 PS_COSMETIC，则此值必须为 0x00000001。 |

### 另请参见

* class [EmfBasePen](../emfbasepen/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Objects](../../aspose.imaging.fileformats.emf.emf.objects/)
* assembly [Aspose.Imaging](../../)


