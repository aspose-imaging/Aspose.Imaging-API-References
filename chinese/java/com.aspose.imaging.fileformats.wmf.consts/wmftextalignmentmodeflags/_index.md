---
title: "WmfTextAlignmentModeFlags"
second_title: "Aspose.Imaging for Java API 参考"
description: "TextAlignmentMode 标志指定参考点与用于文本对齐的边界矩形之间的关系。"
type: docs
weight: 36
url: /zh/java/com.aspose.imaging.fileformats.wmf.consts/wmftextalignmentmodeflags/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class WmfTextAlignmentModeFlags extends System.Enum
```

TextAlignmentMode 标志指定参考点与用于文本对齐的边界矩形之间的关系。这些标志可以组合以指定多个选项，但限制只能选择一个会改变回放设备上下文中绘制位置的标志。当字体具有水平默认基线时，会执行水平文本对齐。

--------------------

TextAlignmentMode 标志指定文本对齐的三个不同组成部分：- 参考点的水平位置由 TA\_RIGHT 和 TA\_CENTER 决定；如果这些位被清除，则对齐必须为 TA\_LEFT。- 参考点的垂直位置由 TA\_BOTTOM 和 TA\_BASELINE 决定；如果这些位被清除，则对齐必须为 TA\_TOP。- 是否在文本输出后更新回放设备上下文中的输出位置由 TA\_UPDATECP 决定；如果该位被清除，则位置必须不更新。这就是在枚举中定义三个不同零值的原因；它们代表文本对齐三个组成部分的默认状态。
## 字段

| 字段 | 描述 |
| --- | --- |
| [Noupdatecp](#Noupdatecp) | 回放设备上下文中的绘制位置在每次文本输出调用后必须不更新。 |
| [Left](#Left) | 参考点必须位于边界矩形的左侧边缘。 |
| [Top](#Top) | 参考点必须位于边界矩形的顶部边缘。 |
| [Updatecp](#Updatecp) | 回放设备上下文中的绘制位置在每次文本输出调用后必须更新。 |
| [Right](#Right) | 参考点必须位于边界矩形的右侧边缘。 |
| [Center](#Center) | 参考点必须在水平上与边界矩形的中心对齐。 |
| [Bottom](#Bottom) | 参考点必须位于边界矩形的底部边缘。 |
| [Baseline](#Baseline) | 参考点必须位于文本的基线。 |
| [Rtlreading](#Rtlreading) | 文本必须以从右到左的阅读顺序布局，而不是默认的从左到右顺序。 |
| [Horizontal](#Horizontal) | Represents Horizontal text align sets (Left | Right | Center) |
| [Vertical](#Vertical) | Represents Vertical text align sets (Top | Bottom | Baseline) |
### Noupdatecp {#Noupdatecp}
```
public static final int Noupdatecp
```


回放设备上下文中的绘制位置在每次文本输出调用后必须不更新。必须将参考点传递给文本输出函数。

### Left {#Left}
```
public static final int Left
```


参考点必须位于边界矩形的左侧边缘。

### Top {#Top}
```
public static final int Top
```


参考点必须位于边界矩形的顶部边缘。

### Updatecp {#Updatecp}
```
public static final int Updatecp
```


回放设备上下文中的绘制位置在每次文本输出调用后必须更新。它必须用作参考点。

### Right {#Right}
```
public static final int Right
```


参考点必须位于边界矩形的右侧边缘。

### Center {#Center}
```
public static final int Center
```


参考点必须在水平上与边界矩形的中心对齐。

### Bottom {#Bottom}
```
public static final int Bottom
```


参考点必须位于边界矩形的底部边缘。

### Baseline {#Baseline}
```
public static final int Baseline
```


参考点必须位于文本的基线。

### Rtlreading {#Rtlreading}
```
public static final int Rtlreading
```


文本必须以从右到左的阅读顺序布局，而不是默认的从左到右顺序。仅当回放设备上下文中定义的字体为希伯来语或阿拉伯语时才应这样做。

### Horizontal {#Horizontal}
```
public static final int Horizontal
```


表示水平文本对齐集合（左 | 右 | 居中）

### Vertical {#Vertical}
```
public static final int Vertical
```


表示垂直文本对齐集合（上 | 下 | 基线）

