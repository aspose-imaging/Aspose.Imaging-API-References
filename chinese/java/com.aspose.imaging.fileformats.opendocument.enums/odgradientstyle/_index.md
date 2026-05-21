---
title: "OdGradientStyle"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "渐变样式"
type: docs
weight: 10
url: /zh/java/com.aspose.imaging.fileformats.opendocument.enums/odgradientstyle/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class OdGradientStyle extends System.Enum
```

渐变样式
## 字段

| 字段 | 描述 |
| --- | --- |
| [Axial](#Axial) | 轴向定义一种双线性渐变，也称为反射渐变或镜像线性渐变。 |
| [Ellipsoid](#Ellipsoid) | 椭圆体定义一种渐变，颜色沿从椭圆体中心的半径混合，中心由 draw:cx 和 draw:cy 属性定义。 |
| [Linear](#Linear) | 线性定义一种渐变，颜色沿渐变的线性轴混合。 |
| [Radial](#Radial) | 径向定义一种渐变，颜色沿从圆心的半径混合，圆心由 draw:cx 和 draw:cy 属性定义。 |
| [Rectangle](#Rectangle) | 矩形定义一种渐变，从矩形中心到四条边中最短的边产生矩形混合。 |
| [Square](#Square) | 正方形定义一种渐变，产生正方形混合，模拟走廊中的视觉透视或金字塔的俯视图。 |
| [None](#None) | 渐变样式为无 |
### Axial {#Axial}
```
public static final int Axial
```


轴向定义一种双线性渐变，也称为反射渐变或镜像线性渐变。它被创建为沿其轴镜像（或反射）的线性渐变。

### Ellipsoid {#Ellipsoid}
```
public static final int Ellipsoid
```


椭圆体定义一种渐变，颜色沿从椭圆体中心的半径混合，中心由 draw:cx 和 draw:cy 属性定义。半长轴的长度是填充区域的宽度，半短轴的长度是

### Linear {#Linear}
```
public static final int Linear
```


线性定义一种渐变，颜色沿渐变的线性轴混合。渐变的轴通过 draw:angle 属性相对于垂直轴顺时针指定。

### Radial {#Radial}
```
public static final int Radial
```


径向定义一种渐变，颜色沿从圆心的半径混合，圆心由 draw:cx 和 draw:cy 属性定义。圆的外部填充终止颜色。

### Rectangle {#Rectangle}
```
public static final int Rectangle
```


矩形定义一种渐变，从矩形中心到四条边中最短的边产生矩形混合。矩形的中心由属性 draw:cx 和 draw:cy 定义。矩形的宽度是填充区域的宽度，矩形的高度是填充区域的高度。矩形的外部填充终止颜色。

### Square {#Square}
```
public static final int Square
```


正方形定义一种渐变，产生正方形混合，模拟走廊中的视觉透视或金字塔的俯视图。也称为“盒状渐变”和“金字塔渐变”。正方形的中心由 draw:cx 和 draw:cy 属性定义。正方形的宽度和高度取填充区域宽度和高度的最小值。正方形的外部填充终止颜色。

### None {#None}
```
public static final int None
```


渐变样式为无

