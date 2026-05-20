---
title: "EmfPlusLineCapType"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "LineCapType 枚举定义了在使用图形笔绘制的线段末端使用的线帽类型。"
type: docs
weight: 31
url: /zh/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfpluslinecaptype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusLineCapType extends System.Enum
```

LineCapType 枚举定义了在使用图形笔绘制的线段末端使用的线帽类型。

--------------------

Graphics 线帽由 [EmfPlusPen](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspen) 对象指定（第 2.2.1.7 节）。
## 字段

| 字段 | 描述 |
| --- | --- |
| [LineCapTypeFlat](#LineCapTypeFlat) | 指定方形线帽。 |
| [LineCapTypeSquare](#LineCapTypeSquare) | 指定方形的线端帽。 |
| [LineCapTypeRound](#LineCapTypeRound) | 指定圆形线帽。 |
| [LineCapTypeTriangle](#LineCapTypeTriangle) | 指定三角形的线端帽。 |
| [LineCapTypeNoAnchor](#LineCapTypeNoAnchor) | 指定线端未锚定。 |
| [LineCapTypeSquareAnchor](#LineCapTypeSquareAnchor) | 指定线端使用方形线帽锚定。 |
| [LineCapTypeRoundAnchor](#LineCapTypeRoundAnchor) | 指定线端使用圆形线帽锚定。 |
| [LineCapTypeDiamondAnchor](#LineCapTypeDiamondAnchor) | 指定线端使用菱形线帽锚定，该线帽是旋转 45 度的方形。 |
| [LineCapTypeArrowAnchor](#LineCapTypeArrowAnchor) | 指定线端使用箭头形状锚定。 |
| [LineCapTypeAnchorMask](#LineCapTypeAnchorMask) | 用于检查线帽是否为锚定帽的掩码。 |
| [LineCapTypeCustom](#LineCapTypeCustom) | 指定自定义线帽。 |
### LineCapTypeFlat {#LineCapTypeFlat}
```
public static final int LineCapTypeFlat
```


指定方形线帽。线的末端必须是该线的最后一个点。

### LineCapTypeSquare {#LineCapTypeSquare}
```
public static final int LineCapTypeSquare
```


指定方形线帽。方形的中心必须位于该线的最后一个点。方形的宽度即为线宽。

### LineCapTypeRound {#LineCapTypeRound}
```
public static final int LineCapTypeRound
```


指定圆形线帽。圆心必须位于该线的最后一个点。圆的直径即为线宽。

### LineCapTypeTriangle {#LineCapTypeTriangle}
```
public static final int LineCapTypeTriangle
```


指定三角形线帽。三角形的底部必须位于该线的最后一个点。三角形的底部宽度即为线宽。

### LineCapTypeNoAnchor {#LineCapTypeNoAnchor}
```
public static final int LineCapTypeNoAnchor
```


指定线端未锚定。

### LineCapTypeSquareAnchor {#LineCapTypeSquareAnchor}
```
public static final int LineCapTypeSquareAnchor
```


指定线端使用方形线帽锚定。方形的中心必须位于该线的最后一个点。方形的高度和宽度均为线宽。

### LineCapTypeRoundAnchor {#LineCapTypeRoundAnchor}
```
public static final int LineCapTypeRoundAnchor
```


指定线端使用圆形线帽锚定。圆心必须位于该线的最后一个点。圆的宽度应大于线宽。

### LineCapTypeDiamondAnchor {#LineCapTypeDiamondAnchor}
```
public static final int LineCapTypeDiamondAnchor
```


指定线端使用菱形线帽锚定，该线帽是旋转 45 度的方形。菱形的中心必须位于该线的最后一个点。菱形的宽度应大于线宽。

### LineCapTypeArrowAnchor {#LineCapTypeArrowAnchor}
```
public static final int LineCapTypeArrowAnchor
```


指定线端使用箭头形状锚定。箭头尖端必须位于该线的最后一个点。箭头的宽度应大于线宽。

### LineCapTypeAnchorMask {#LineCapTypeAnchorMask}
```
public static final int LineCapTypeAnchorMask
```


用于检查线帽是否为锚定帽的掩码。

### LineCapTypeCustom {#LineCapTypeCustom}
```
public static final int LineCapTypeCustom
```


指定自定义线帽。

