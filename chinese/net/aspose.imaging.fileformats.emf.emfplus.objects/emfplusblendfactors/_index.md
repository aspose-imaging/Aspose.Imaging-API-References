---
title: "类 EmfPlusBlendFactors"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects.EmfPlusBlendFactors 类。EmfPlusBlendFactors 对象指定渐变画笔的混合模式的位置信息和因子"
type: docs
weight: 5330
url: /zh/net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendfactors/
---
## EmfPlusBlendFactors class

EmfPlusBlendFactors 对象指定了渐变画笔的混合模式的位置信息和因子。

```csharp
public sealed class EmfPlusBlendFactors : EmfPlusBlendBase
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfPlusBlendFactors](emfplusblendfactors/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [BlendFactors](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendfactors/blendfactors/) { get; set; } | 获取或设置一个包含 PositionCount 个 32 位浮点值的数组，这些值指定 BlendPositions 字段中定义位置的颜色比例。每个值必须是 0.0 到 1.0（含）之间的数字。 |
| [BlendPositions](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendbase/blendpositions/) { get; set; } | 获取或设置混合位置：一个包含 PositionCount 个 32 位浮点值的数组，指定沿渐变线的距离比例。每个元素必须是 0.0 到 1.0（含）之间的数字。对于线性渐变画笔，0.0 表示起始点，1.0 表示结束点。对于路径渐变画笔，0.0 表示中点，1.0 表示端点。 |

### 另请参见

* class [EmfPlusBlendBase](../emfplusblendbase/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../aspose.imaging.fileformats.emf.emfplus.objects/)
* assembly [Aspose.Imaging](../../)


