---
title: "EmfPenStyle"
second_title: "Aspose.Imaging for Java API 参考"
description: "PenStyle 枚举定义了可用于图形操作的笔的属性。"
type: docs
weight: 34
url: /zh/java/com.aspose.imaging.fileformats.emf.emf.consts/emfpenstyle/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPenStyle extends System.Enum
```

PenStyle 枚举定义了可用于图形操作的笔的属性。笔样式是笔类型、线条样式、线帽和线段连接的组合。
## 字段

| 字段 | 描述 |
| --- | --- |
| [PS_COSMETIC](#PS-COSMETIC) | 一种笔类型，指定宽度为一个逻辑单位且样式为纯色的线条。 |
| [PS_ENDCAP_ROUND](#PS-ENDCAP-ROUND) | 一种线帽，指定圆形端点。 |
| [PS_JOIN_ROUND](#PS-JOIN-ROUND) | 一种线段连接，指定圆形连接。 |
| [PS_SOLID](#PS-SOLID) | 一种线条样式，为纯色。 |
| [PS_DASH](#PS-DASH) | 一种线条样式，为虚线。 |
| [PS_DOT](#PS-DOT) | 一种线条样式，为点线。 |
| [PS_DASHDOT](#PS-DASHDOT) | 一种线条样式，由交替的短划线和点组成。 |
| [PS_DASHDOTDOT](#PS-DASHDOTDOT) | 一种线条样式，由短划线和双点组成。 |
| [PS_NULL](#PS-NULL) | 一种线条样式，为不可见。 |
| [PS_INSIDEFRAME](#PS-INSIDEFRAME) | 一种线条样式，为纯色。 |
| [PS_USERSTYLE](#PS-USERSTYLE) | 一种线条样式，由样式数组定义，该数组指定线段中短划线和间隙的长度。 |
| [PS_ALTERNATE](#PS-ALTERNATE) | 一种线条样式，其中每隔一个像素被绘制。 |
| [PS_ENDCAP_SQUARE](#PS-ENDCAP-SQUARE) | 一种线帽，指定方形端点。 |
| [PS_ENDCAP_FLAT](#PS-ENDCAP-FLAT) | 一种线帽，指定平直端点。 |
| [PS_JOIN_BEVEL](#PS-JOIN-BEVEL) | 一种线段连接，指定斜角连接。 |
| [PS_JOIN_MITER](#PS-JOIN-MITER) | 一种线段连接，当连接长度在播放设备上下文中设置的当前斜接长度限制范围内时，指定斜接连接。 |
| [PS_GEOMETRIC](#PS-GEOMETRIC) | 一种笔类型，指定宽度以逻辑单位测量的线条，且其样式可以包含画刷的任何属性。 |
| [StyleMask](#StyleMask) | 样式掩码 |
| [EndCapMask](#EndCapMask) | 端帽掩码 |
| [JoinMask](#JoinMask) | 连接掩码 |
| [TypeMask](#TypeMask) | 类型掩码 |
### PS_COSMETIC {#PS-COSMETIC}
```
public static final int PS_COSMETIC
```


一种笔类型，指定宽度为一个逻辑单位且样式为纯色的线条。

### PS_ENDCAP_ROUND {#PS-ENDCAP-ROUND}
```
public static final int PS_ENDCAP_ROUND
```


一种线帽，指定圆形端点。

### PS_JOIN_ROUND {#PS-JOIN-ROUND}
```
public static final int PS_JOIN_ROUND
```


一种线段连接，指定圆形连接。

### PS_SOLID {#PS-SOLID}
```
public static final int PS_SOLID
```


一种线条样式，为纯色。

### PS_DASH {#PS-DASH}
```
public static final int PS_DASH
```


一种线条样式，为虚线。

### PS_DOT {#PS-DOT}
```
public static final int PS_DOT
```


一种线条样式，为点线。

### PS_DASHDOT {#PS-DASHDOT}
```
public static final int PS_DASHDOT
```


一种线条样式，由交替的短划线和点组成。

### PS_DASHDOTDOT {#PS-DASHDOTDOT}
```
public static final int PS_DASHDOTDOT
```


一种线条样式，由短划线和双点组成。

### PS_NULL {#PS-NULL}
```
public static final int PS_NULL
```


一种线条样式，为不可见。

### PS_INSIDEFRAME {#PS-INSIDEFRAME}
```
public static final int PS_INSIDEFRAME
```


一种线条样式，为纯色。当此样式在接受边界矩形的绘图记录中指定时，图形的尺寸会缩小，以便完全适应边界矩形，并考虑笔的宽度。

### PS_USERSTYLE {#PS-USERSTYLE}
```
public static final int PS_USERSTYLE
```


一种线条样式，由样式数组定义，该数组指定线段中短划线和间隙的长度。

### PS_ALTERNATE {#PS-ALTERNATE}
```
public static final int PS_ALTERNATE
```


一种线条样式，其中每隔一个像素被绘制。此样式仅适用于 PS\\_COSMETIC 笔类型。

### PS_ENDCAP_SQUARE {#PS-ENDCAP-SQUARE}
```
public static final int PS_ENDCAP_SQUARE
```


一种线帽，指定方形端点。

### PS_ENDCAP_FLAT {#PS-ENDCAP-FLAT}
```
public static final int PS_ENDCAP_FLAT
```


一种线帽，指定平直端点。

### PS_JOIN_BEVEL {#PS-JOIN-BEVEL}
```
public static final int PS_JOIN_BEVEL
```


一种线段连接，指定斜角连接。

### PS_JOIN_MITER {#PS-JOIN-MITER}
```
public static final int PS_JOIN_MITER
```


一种线段连接，当连接长度在播放设备上下文中设置的当前斜接长度限制范围内时，指定斜接连接。如果连接长度超过斜接限制，则指定斜角连接。

### PS_GEOMETRIC {#PS-GEOMETRIC}
```
public static final int PS_GEOMETRIC
```


一种笔类型，指定宽度以逻辑单位测量的线条，且其样式可以包含画刷的任何属性。

### StyleMask {#StyleMask}
```
public static final int StyleMask
```


样式掩码

### EndCapMask {#EndCapMask}
```
public static final int EndCapMask
```


端帽掩码

### JoinMask {#JoinMask}
```
public static final int JoinMask
```


连接掩码

### TypeMask {#TypeMask}
```
public static final int TypeMask
```


类型掩码

