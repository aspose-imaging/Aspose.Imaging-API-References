---
title: "类 EmfPlusBlendColors"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects.EmfPlusBlendColors 类。EmfPlusBlendColors 对象指定渐变画刷混合模式的位置信息和颜色。"
type: docs
weight: 5320
url: /zh/net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendcolors/
---
## EmfPlusBlendColors class

EmfPlusBlendColors 对象指定了渐变画笔的混合模式的位置信息和颜色。

```csharp
public sealed class EmfPlusBlendColors : EmfPlusBlendBase
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfPlusBlendColors](emfplusblendcolors/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [BlendArgb32Colors](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendcolors/blendargb32colors/) { get; set; } | 获取或设置一个包含 PositionCount 个 EmfPlusARGB 对象的数组 (section 2.2.2.1)，这些对象在 BlendPositions 字段定义的位置上指定颜色。 |
| [BlendPositions](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendbase/blendpositions/) { get; set; } | 获取或设置混合位置：一个包含 PositionCount 个 32 位浮点值的数组，指定沿渐变线的距离比例。每个元素必须是 0.0 到 1.0（含）之间的数字。对于线性渐变画笔，0.0 表示起始点，1.0 表示结束点。对于路径渐变画笔，0.0 表示中点，1.0 表示端点。 |

### 另请参见

* class [EmfPlusBlendBase](../emfplusblendbase/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../aspose.imaging.fileformats.emf.emfplus.objects/)
* assembly [Aspose.Imaging](../../)


