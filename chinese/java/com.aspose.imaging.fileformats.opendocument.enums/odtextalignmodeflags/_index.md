---
title: "OdTextAlignModeFlags"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "开放文档文本对齐模式标志"
type: docs
weight: 14
url: /zh/java/com.aspose.imaging.fileformats.opendocument.enums/odtextalignmodeflags/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class OdTextAlignModeFlags extends System.Enum
```

开放文档文本对齐模式标志
## 字段

| 字段 | 描述 |
| --- | --- |
| [Noupdatecp](#Noupdatecp) | 回放设备上下文中的绘图位置在每次文本输出调用后不得更新。 |
| [Left](#Left) | 参考点必须位于边界矩形的左侧边缘。 |
| [Top](#Top) | 参考点必须位于边界矩形的顶部边缘。 |
| [Updatecp](#Updatecp) | 回放设备上下文中的绘图位置在每次文本输出调用后必须更新。 |
| [Right](#Right) | 参考点必须位于边界矩形的右侧边缘。 |
| [Center](#Center) | 参考点必须在水平上与边界矩形的中心对齐。 |
| [Justify](#Justify) | 文本必须对齐，使段落的每行文本具有相同的长度。 |
| [Bottom](#Bottom) | 参考点必须位于边界矩形的底部边缘。 |
| [Baseline](#Baseline) | 参考点必须位于文本的基线位置。 |
| [Rtlreading](#Rtlreading) | 文本必须以从右到左的阅读顺序布局，而不是默认的从左到右顺序。 |
| [Horizontal](#Horizontal) | Represents Horizontal text align sets (Left | Right | Center) |
| [Vertical](#Vertical) | Represents Vertical text align sets (Top | Bottom | Baseline) |
### Noupdatecp {#Noupdatecp}
```
public static final int Noupdatecp
```


回放设备上下文中的绘图位置在每次文本输出调用后不得更新。必须将参考点传递给文本输出函数。

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


回放设备上下文中的绘图位置在每次文本输出调用后必须更新。它必须用作参考点。

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

### Justify {#Justify}
```
public static final int Justify
```


文本必须对齐，使段落的每行文本具有相同的长度。

### Bottom {#Bottom}
```
public static final int Bottom
```


参考点必须位于边界矩形的底部边缘。

### Baseline {#Baseline}
```
public static final int Baseline
```


参考点必须位于文本的基线位置。

### Rtlreading {#Rtlreading}
```
public static final int Rtlreading
```


文本必须以从右到左的阅读顺序布局，而不是默认的从左到右顺序。仅当回放设备上下文中定义的字体是希伯来语或阿拉伯语时才应应用此规则。

### Horizontal {#Horizontal}
```
public static final int Horizontal
```


表示水平文本对齐集合 (Left | Right | Center)

### Vertical {#Vertical}
```
public static final int Vertical
```


表示垂直文本对齐集合 (Top | Bottom | Baseline)

