---
title: "Delegate MagicWandSettings.ColorComparison"
second_title: "Aspose.Imaging for .NET API 参考"
description: "用于颜色比较的委托，具有定义的阈值"
type: docs
weight: 10920
url: /zh/net/aspose.imaging.magicwand/magicwandsettings.colorcomparison/
---
## MagicWandSettings.ColorComparison delegate

用于 [`Color`](../../aspose.imaging/color/) 比较的委托，具有定义的阈值。

```csharp
public delegate bool ColorComparison(Color p1, Color p2, int threshold);
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| p1 | 颜色 | 要比较的第一种颜色。 |
| p2 | 颜色 | 要比较的第二种颜色。 |
| threshold | Int32 | 颜色差异的允许阈值。 |

### 返回值

如果颜色比较满足阈值则为 true；否则为 false。

### 另请参见

* struct [Color](../../aspose.imaging/color/)
* class [MagicWandSettings](../magicwandsettings/)
* namespace [Aspose.Imaging.MagicWand](../../aspose.imaging.magicwand/)
* assembly [Aspose.Imaging](../../)


