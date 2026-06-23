---
title: "HatchStyle"
second_title: "Aspose.Imaging for Java API 参考"
description: "指定 HatchBrush 对象可用的不同图案。"
type: docs
weight: 54
url: /zh/java/com.aspose.imaging/hatchstyle/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class HatchStyle extends System.Enum
```

指定 `HatchBrush` 对象可用的不同图案。
## 字段

| 字段 | 描述 |
| --- | --- |
| [Horizontal](#Horizontal) | 水平线的图案。 |
| [Min](#Min) | 指定填充样式 Horizontal。 |
| [Vertical](#Vertical) | 垂直线的图案。 |
| [ForwardDiagonal](#ForwardDiagonal) | 从左上到右下的对角线图案。 |
| [BackwardDiagonal](#BackwardDiagonal) | 从右上到左下的对角线图案。 |
| [Cross](#Cross) | 指定水平和垂直交叉的线条。 |
| [LargeGrid](#LargeGrid) | 指定填充样式 Cross。 |
| [Max](#Max) | 指定填充样式 SolidDiamond。 |
| [DiagonalCross](#DiagonalCross) | 交叉对角线的图案。 |
| [Percent05](#Percent05) | 指定 5% 的填充。 |
| [Percent10](#Percent10) | 指定 10% 的填充。 |
| [Percent20](#Percent20) | 指定 20% 的填充。 |
| [Percent25](#Percent25) | 指定 25% 的填充。 |
| [Percent30](#Percent30) | 指定 30% 的填充。 |
| [Percent40](#Percent40) | 指定 40% 的填充。 |
| [Percent50](#Percent50) | 指定 50% 的填充。 |
| [Percent60](#Percent60) | 指定 60% 的填充图案。 |
| [Percent70](#Percent70) | 指定 70% 的填充图案。 |
| [Percent75](#Percent75) | 指定 75% 的填充图案。 |
| [Percent80](#Percent80) | 指定 80% 的填充图案。 |
| [Percent90](#Percent90) | 指定 90% 的填充图案。 |
| [LightDownwardDiagonal](#LightDownwardDiagonal) | 指定从顶部点到底部点向右倾斜的对角线，其间距比 ForwardDiagonal 小 50%，但未进行抗锯齿处理。 |
| [LightUpwardDiagonal](#LightUpwardDiagonal) | 指定从顶部点到底部点向左倾斜的对角线，其间距比 BackwardDiagonal 小 50%，但未进行抗锯齿处理。 |
| [DarkDownwardDiagonal](#DarkDownwardDiagonal) | 指定从顶部点到底部点向右倾斜的对角线，其间距比 ForwardDiagonal 小 50%，且宽度是 ForwardDiagonal 的两倍。 |
| [DarkUpwardDiagonal](#DarkUpwardDiagonal) | 指定从顶部点到底部点向左倾斜的对角线，其间距比 BackwardDiagonal 小 50%，宽度是其两倍，但未进行抗锯齿处理。 |
| [WideDownwardDiagonal](#WideDownwardDiagonal) | 指定从顶部点到底部点向右倾斜的对角线，其间距与填充样式 ForwardDiagonal 相同，宽度是其三倍，但未进行抗锯齿处理。 |
| [WideUpwardDiagonal](#WideUpwardDiagonal) | 指定从顶部点到底部点向左倾斜的对角线，其间距与填充样式 BackwardDiagonal 相同，宽度是其三倍，但未进行抗锯齿处理。 |
| [LightVertical](#LightVertical) | 指定垂直线，其间距比 Vertical 小 50%。 |
| [LightHorizontal](#LightHorizontal) | 指定水平线，其间距比 Horizontal 小 50%。 |
| [NarrowVertical](#NarrowVertical) | 指定垂直线，其间距比填充样式 Vertical 小 75%（或比 LightVertical 小 25%）。 |
| [NarrowHorizontal](#NarrowHorizontal) | 指定水平线，其间距比填充样式 Horizontal 小 75%（或比 LightHorizontal 小 25%）。 |
| [DarkVertical](#DarkVertical) | 指定垂直线，其间距比 Vertical 小 50%，且宽度是其两倍。 |
| [DarkHorizontal](#DarkHorizontal) | 指定水平线，其间距比 Horizontal 小 50%，且宽度是 Horizontal 的两倍。 |
| [DashedDownwardDiagonal](#DashedDownwardDiagonal) | 指定从顶部点到底部点向右倾斜的虚线对角线。 |
| [DashedUpwardDiagonal](#DashedUpwardDiagonal) | 指定从顶部点到底部点向左倾斜的虚线对角线。 |
| [DashedHorizontal](#DashedHorizontal) | 指定虚线水平线。 |
| [DashedVertical](#DashedVertical) | 指定虚线垂直线。 |
| [SmallConfetti](#SmallConfetti) | 指定外观为彩纸屑的填充图案。 |
| [LargeConfetti](#LargeConfetti) | 指定外观为彩纸屑的填充图案，且其组成的碎片比 SmallConfetti 更大。 |
| [ZigZag](#ZigZag) | 指定由锯齿形组成的水平线。 |
| [Wave](#Wave) | 指定由波浪线组成的水平线。 |
| [DiagonalBrick](#DiagonalBrick) | 指定一种填充图案，其外观为层叠的砖块，左倾，从顶部点到底部点。 |
| [HorizontalBrick](#HorizontalBrick) | 指定一种填充图案，其外观为水平层叠的砖块。 |
| [Weave](#Weave) | 指定一种填充图案，其外观为编织材料。 |
| [Plaid](#Plaid) | 指定一种填充图案，其外观为格子材料。 |
| [Divot](#Divot) | 指定一种填充图案，其外观为凹坑。 |
| [DottedGrid](#DottedGrid) | 指定水平和垂直线条，每条均由点组成，交叉。 |
| [DottedDiamond](#DottedDiamond) | 指定正向对角线和反向对角线，每条均由点组成，交叉。 |
| [Shingle](#Shingle) | 指定一种填充图案，其外观为对角层叠的瓦片，右倾，从顶部点到底部点。 |
| [Trellis](#Trellis) | 指定一种填充图案，其外观为格子结构。 |
| [Sphere](#Sphere) | 指定一种填充图案，其外观为相邻排列的球体。 |
| [SmallGrid](#SmallGrid) | 指定水平和垂直交叉线，其间距比填充样式“Cross”紧50%。 |
| [SmallCheckerBoard](#SmallCheckerBoard) | 指定一种填充图案，其外观为棋盘格。 |
| [LargeCheckerBoard](#LargeCheckerBoard) | 指定一种填充图案，其外观为棋盘格，方格大小为 SmallCheckerBoard 的两倍。 |
| [OutlinedDiamond](#OutlinedDiamond) | 指定正向和反向对角交叉线，但未进行抗锯齿处理。 |
| [SolidDiamond](#SolidDiamond) | 指定一种填充图案，其外观为对角放置的棋盘格。 |
### Horizontal {#Horizontal}
```
public static final int Horizontal
```


水平线的图案。

### Min {#Min}
```
public static final int Min
```


指定填充样式 Horizontal。

### Vertical {#Vertical}
```
public static final int Vertical
```


垂直线的图案。

### ForwardDiagonal {#ForwardDiagonal}
```
public static final int ForwardDiagonal
```


从左上到右下的对角线图案。

### BackwardDiagonal {#BackwardDiagonal}
```
public static final int BackwardDiagonal
```


从右上到左下的对角线图案。

### Cross {#Cross}
```
public static final int Cross
```


指定水平和垂直交叉的线条。

### LargeGrid {#LargeGrid}
```
public static final int LargeGrid
```


指定填充样式 Cross。

### Max {#Max}
```
public static final int Max
```


指定填充样式 SolidDiamond。

### DiagonalCross {#DiagonalCross}
```
public static final int DiagonalCross
```


交叉对角线的图案。

### Percent05 {#Percent05}
```
public static final int Percent05
```


指定 5% 的填充。前景色与背景色的比例为 5:95。

### Percent10 {#Percent10}
```
public static final int Percent10
```


指定 10% 的填充。前景色与背景色的比例为 10:90。

### Percent20 {#Percent20}
```
public static final int Percent20
```


指定 20% 的填充。前景色与背景色的比例为 20:80。

### Percent25 {#Percent25}
```
public static final int Percent25
```


指定 25% 的填充。前景色与背景色的比例为 25:75。

### Percent30 {#Percent30}
```
public static final int Percent30
```


指定 30% 的填充。前景色与背景色的比例为 30:70。

### Percent40 {#Percent40}
```
public static final int Percent40
```


指定 40% 的填充。前景色与背景色的比例为 40:60。

### Percent50 {#Percent50}
```
public static final int Percent50
```


指定 50% 的填充。前景色与背景色的比例为 50:50。

### Percent60 {#Percent60}
```
public static final int Percent60
```


指定 60% 的填充。前景色与背景色的比例为 60:40。

### Percent70 {#Percent70}
```
public static final int Percent70
```


指定 70% 的填充。前景色与背景色的比例为 70:30。

### Percent75 {#Percent75}
```
public static final int Percent75
```


指定 75% 的填充。前景色与背景色的比例为 75:25。

### Percent80 {#Percent80}
```
public static final int Percent80
```


指定 80% 的填充。前景色与背景色的比例为 80:100。

### Percent90 {#Percent90}
```
public static final int Percent90
```


指定 90% 的填充。前景色与背景色的比例为 90:10。

### LightDownwardDiagonal {#LightDownwardDiagonal}
```
public static final int LightDownwardDiagonal
```


指定从顶部点到底部点向右倾斜的对角线，其间距比 ForwardDiagonal 小 50%，但未进行抗锯齿处理。

### LightUpwardDiagonal {#LightUpwardDiagonal}
```
public static final int LightUpwardDiagonal
```


指定从顶部点到底部点向左倾斜的对角线，其间距比 BackwardDiagonal 小 50%，但未进行抗锯齿处理。

### DarkDownwardDiagonal {#DarkDownwardDiagonal}
```
public static final int DarkDownwardDiagonal
```


指定从顶部点到底部点向右倾斜的对角线，间距比 ForwardDiagonal 小 50%，且宽度是其两倍。此填充图案未进行抗锯齿处理。

### DarkUpwardDiagonal {#DarkUpwardDiagonal}
```
public static final int DarkUpwardDiagonal
```


指定从顶部点到底部点向左倾斜的对角线，其间距比 BackwardDiagonal 小 50%，宽度是其两倍，但未进行抗锯齿处理。

### WideDownwardDiagonal {#WideDownwardDiagonal}
```
public static final int WideDownwardDiagonal
```


指定从顶部点到底部点向右倾斜的对角线，其间距与填充样式 ForwardDiagonal 相同，宽度是其三倍，但未进行抗锯齿处理。

### WideUpwardDiagonal {#WideUpwardDiagonal}
```
public static final int WideUpwardDiagonal
```


指定从顶部点到底部点向左倾斜的对角线，其间距与填充样式 BackwardDiagonal 相同，宽度是其三倍，但未进行抗锯齿处理。

### LightVertical {#LightVertical}
```
public static final int LightVertical
```


指定垂直线，其间距比 Vertical 小 50%。

### LightHorizontal {#LightHorizontal}
```
public static final int LightHorizontal
```


指定水平线，其间距比 Horizontal 小 50%。

### NarrowVertical {#NarrowVertical}
```
public static final int NarrowVertical
```


指定垂直线，其间距比填充样式 Vertical 小 75%（或比 LightVertical 小 25%）。

### NarrowHorizontal {#NarrowHorizontal}
```
public static final int NarrowHorizontal
```


指定水平线，其间距比填充样式 Horizontal 小 75%（或比 LightHorizontal 小 25%）。

### DarkVertical {#DarkVertical}
```
public static final int DarkVertical
```


指定垂直线，其间距比 Vertical 小 50%，且宽度是其两倍。

### DarkHorizontal {#DarkHorizontal}
```
public static final int DarkHorizontal
```


指定水平线，其间距比 Horizontal 小 50%，且宽度是 Horizontal 的两倍。

### DashedDownwardDiagonal {#DashedDownwardDiagonal}
```
public static final int DashedDownwardDiagonal
```


指定从顶部点到底部点向右倾斜的虚线对角线。

### DashedUpwardDiagonal {#DashedUpwardDiagonal}
```
public static final int DashedUpwardDiagonal
```


指定从顶部点到底部点向左倾斜的虚线对角线。

### DashedHorizontal {#DashedHorizontal}
```
public static final int DashedHorizontal
```


指定虚线水平线。

### DashedVertical {#DashedVertical}
```
public static final int DashedVertical
```


指定虚线垂直线。

### SmallConfetti {#SmallConfetti}
```
public static final int SmallConfetti
```


指定外观为彩纸屑的填充图案。

### LargeConfetti {#LargeConfetti}
```
public static final int LargeConfetti
```


指定外观为彩纸屑的填充图案，且其组成的碎片比 SmallConfetti 更大。

### ZigZag {#ZigZag}
```
public static final int ZigZag
```


指定由锯齿形组成的水平线。

### Wave {#Wave}
```
public static final int Wave
```


指定由波浪线组成的水平线。

### DiagonalBrick {#DiagonalBrick}
```
public static final int DiagonalBrick
```


指定一种填充图案，其外观为层叠的砖块，左倾，从顶部点到底部点。

### HorizontalBrick {#HorizontalBrick}
```
public static final int HorizontalBrick
```


指定一种填充图案，其外观为水平层叠的砖块。

### Weave {#Weave}
```
public static final int Weave
```


指定一种填充图案，其外观为编织材料。

### Plaid {#Plaid}
```
public static final int Plaid
```


指定一种填充图案，其外观为格子材料。

### Divot {#Divot}
```
public static final int Divot
```


指定一种填充图案，其外观为凹坑。

### DottedGrid {#DottedGrid}
```
public static final int DottedGrid
```


指定水平和垂直线条，每条均由点组成，交叉。

### DottedDiamond {#DottedDiamond}
```
public static final int DottedDiamond
```


指定正向对角线和反向对角线，每条均由点组成，交叉。

### Shingle {#Shingle}
```
public static final int Shingle
```


指定一种填充图案，其外观为对角层叠的瓦片，右倾，从顶部点到底部点。

### Trellis {#Trellis}
```
public static final int Trellis
```


指定一种填充图案，其外观为格子结构。

### Sphere {#Sphere}
```
public static final int Sphere
```


指定一种填充图案，其外观为相邻排列的球体。

### SmallGrid {#SmallGrid}
```
public static final int SmallGrid
```


指定水平和垂直交叉线，其间距比填充样式“Cross”紧50%。

### SmallCheckerBoard {#SmallCheckerBoard}
```
public static final int SmallCheckerBoard
```


指定一种填充图案，其外观为棋盘格。

### LargeCheckerBoard {#LargeCheckerBoard}
```
public static final int LargeCheckerBoard
```


指定一种填充图案，其外观为棋盘格，方格大小为 SmallCheckerBoard 的两倍。

### OutlinedDiamond {#OutlinedDiamond}
```
public static final int OutlinedDiamond
```


指定正向和反向对角交叉线，但未进行抗锯齿处理。

### SolidDiamond {#SolidDiamond}
```
public static final int SolidDiamond
```


指定一种填充图案，其外观为对角放置的棋盘格。

