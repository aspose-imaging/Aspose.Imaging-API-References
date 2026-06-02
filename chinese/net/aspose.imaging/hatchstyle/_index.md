---
title: "枚举 HatchStyle"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.HatchStyle 枚举。指定 HatchBrush 对象可用的不同图案"
type: docs
weight: 9570
url: /zh/net/aspose.imaging/hatchstyle/
---
## HatchStyle enumeration

指定 [`HatchBrush`](../../aspose.imaging.brushes/hatchbrush/) 对象可用的不同图案。

```csharp
public enum HatchStyle
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| Horizontal | `0` | 水平线图案。 |
| Min | `0` | 指定填充样式 Horizontal。 |
| Vertical | `1` | 垂直线图案。 |
| ForwardDiagonal | `2` | 从左上到右下的对角线图案。 |
| BackwardDiagonal | `3` | 从右上到左下的对角线图案。 |
| Cross | `4` | 指定水平和垂直交叉的线条。 |
| LargeGrid | `4` | 指定填充样式 Cross。 |
| Max | `4` | 指定填充样式 SolidDiamond。 |
| DiagonalCross | `5` | 交叉对角线图案。 |
| Percent05 | `6` | 指定 5% 的填充。前景色与背景色的比例为 5:95。 |
| Percent10 | `7` | 指定 10% 的填充。前景色与背景色的比例为 10:90。 |
| Percent20 | `8` | 指定 20% 的填充图案。前景色与背景色的比例为 20:80。 |
| Percent25 | `9` | 指定 25% 的填充图案。前景色与背景色的比例为 25:75。 |
| Percent30 | `10` | 指定 30% 的填充图案。前景色与背景色的比例为 30:70。 |
| Percent40 | `11` | 指定 40% 的填充图案。前景色与背景色的比例为 40:60。 |
| Percent50 | `12` | 指定 50% 的填充图案。前景色与背景色的比例为 50:50。 |
| Percent60 | `13` | 指定 60% 的填充图案。前景色与背景色的比例为 60:40。 |
| Percent70 | `14` | 指定 70% 的填充图案。前景色与背景色的比例为 70:30。 |
| Percent75 | `15` | 指定 75% 的填充图案。前景色与背景色的比例为 75:25。 |
| Percent80 | `16` | 指定 80% 的填充图案。前景色与背景色的比例为 80:100。 |
| Percent90 | `17` | 指定 90% 的填充图案。前景色与背景色的比例为 90:10。 |
| LightDownwardDiagonal | `18` | 指定从顶部点到底部点向右倾斜的对角线，间距比 ForwardDiagonal 缩小 50%，但不进行抗锯齿处理。 |
| LightUpwardDiagonal | `19` | 指定从顶部点到底部点向左倾斜的对角线，间距比 BackwardDiagonal 缩小 50%，但不进行抗锯齿处理。 |
| DarkDownwardDiagonal | `20` | 指定从顶部点到底部点向右倾斜的对角线，间距比 ForwardDiagonal 缩小 50%，且宽度是其两倍。此填充图案不进行抗锯齿处理。 |
| DarkUpwardDiagonal | `21` | 指定从顶部点到底部点向左倾斜的对角线，间距比 BackwardDiagonal 缩小 50%，且宽度是其两倍，但这些线条不进行抗锯齿处理。 |
| WideDownwardDiagonal | `22` | 指定从顶部点到底部点向右倾斜的对角线，间距与 ForwardDiagonal 相同，且宽度是其三倍，但不进行抗锯齿处理。 |
| WideUpwardDiagonal | `23` | 指定从顶部点到底部点向左倾斜的对角线，间距与 BackwardDiagonal 相同，且宽度是其三倍，但不进行抗锯齿处理。 |
| LightVertical | `24` | 指定垂直线，其间距比 Vertical 缩小 50%。 |
| LightHorizontal | `25` | 指定水平线，其间距比 Horizontal 缩小 50%。 |
| NarrowVertical | `26` | 指定垂直线，其间距比填充样式 Vertical 缩小 75%（或比 LightVertical 缩小 25%）。 |
| NarrowHorizontal | `27` | 指定水平线，其间距比填充样式 Horizontal 缩小 75%（或比 LightHorizontal 缩小 25%）。 |
| DarkVertical | `28` | 指定垂直线，其间距比 Vertical 缩小 50%，且宽度是其两倍。 |
| DarkHorizontal | `29` | 指定水平线，其间距比 Horizontal 缩小 50%，且宽度是 Horizontal 的两倍。 |
| DashedDownwardDiagonal | `30` | 指定从顶部点到底部点向右倾斜的虚线对角线。 |
| DashedUpwardDiagonal | `31` | 指定从顶部点到底部点向左倾斜的虚线对角线。 |
| DashedHorizontal | `32` | 指定虚线水平线。 |
| DashedVertical | `33` | 指定虚线垂直线。 |
| SmallConfetti | `34` | 指定外观为五彩纸屑的填充图案。 |
| LargeConfetti | `35` | 指定外观为五彩纸屑的填充图案，且其组成的碎片大于 SmallConfetti。 |
| ZigZag | `36` | 指定由锯齿组成的水平线。 |
| Wave | `37` | 指定由波浪线（~）组成的水平线。 |
| DiagonalBrick | `38` | 指定外观为从上到下向左倾斜的层叠砖块的填充图案。 |
| HorizontalBrick | `39` | 指定外观为水平层叠砖块的填充图案。 |
| Weave | `40` | 指定外观为编织材料的填充图案。 |
| Plaid | `41` | 指定外观为格子材料的填充图案。 |
| Divot | `42` | 指定外观为凹痕的填充图案。 |
| DottedGrid | `43` | 指定水平线和垂直线交叉，且每条线由点组成。 |
| DottedDiamond | `44` | 指定正向对角线和反向对角线交叉，且每条线由点组成。 |
| Shingle | `45` | 指定外观为从上到下向右倾斜的对角层叠瓦片的填充图案。 |
| Trellis | `46` | 指定外观为格架的填充图案。 |
| Sphere | `47` | 指定外观为相邻排列球体的填充图案。 |
| SmallGrid | `48` | 指定水平线和垂直线交叉，且间距比 Cross 填充样式小 50%。 |
| SmallCheckerBoard | `49` | 指定外观为棋盘格的填充图案。 |
| LargeCheckerBoard | `50` | 指定外观为棋盘格的填充图案，方格大小为 SmallCheckerBoard 的两倍。 |
| OutlinedDiamond | `51` | 指定正向和反向对角线交叉，但未进行抗锯齿处理。 |
| SolidDiamond | `52` | 指定外观为对角放置的棋盘格的填充图案。 |

### 另请参见

* namespace [Aspose.Imaging](../../aspose.imaging/)
* assembly [Aspose.Imaging](../../)


