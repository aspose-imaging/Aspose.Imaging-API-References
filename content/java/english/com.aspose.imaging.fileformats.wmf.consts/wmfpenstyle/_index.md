---
title: WmfPenStyle
second_title: Aspose.Imaging for Java API Reference
description: The 16-bit PenStyle Enumeration is used to specify different types of pens that can be used in graphics operations.
type: docs
weight: 28
url: /com.aspose.imaging.fileformats.wmf.consts/wmfpenstyle/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class WmfPenStyle extends System.Enum
```

The 16-bit PenStyle Enumeration is used to specify different types of pens that can be used in graphics operations.
## Fields

| Field | Description |
| --- | --- |
| [Cosmetic](#Cosmetic) | The cosmetic |
| [EndcapRound](#EndcapRound) | The line end caps are round. |
| [JoinRound](#JoinRound) | Line joins are round. |
| [Solid](#Solid) | The pen is solid. |
| [Dash](#Dash) | The pen is dashed. |
| [Dot](#Dot) | The pen is dotted. |
| [Dashdot](#Dashdot) | The pen has alternating dashes and dots. |
| [Dashdotdot](#Dashdotdot) | The pen has dashes and double dots. |
| [Null](#Null) | The pen is invisible. |
| [Insideframe](#Insideframe) | The pen is solid. |
| [Userstyle](#Userstyle) | The pen uses a styling array supplied by the user. |
| [Alternate](#Alternate) | The pen sets every other pixel (this style is applicable only for cosmetic pens). |
| [EndcapSquare](#EndcapSquare) | Line end caps are square. |
| [EndcapFlat](#EndcapFlat) | Line end caps are flat. |
| [JoinBevel](#JoinBevel) | Line joins are beveled. |
| [JoinMiter](#JoinMiter) | Line joins are mitered when they are within the current limit set by the SETMITERLIMIT META\_ESCAPE record. |
### Cosmetic {#Cosmetic}
```
public static final short Cosmetic
```


The cosmetic

### EndcapRound {#EndcapRound}
```
public static final short EndcapRound
```


The line end caps are round.

### JoinRound {#JoinRound}
```
public static final short JoinRound
```


Line joins are round.

### Solid {#Solid}
```
public static final short Solid
```


The pen is solid.

### Dash {#Dash}
```
public static final short Dash
```


The pen is dashed.

### Dot {#Dot}
```
public static final short Dot
```


The pen is dotted.

### Dashdot {#Dashdot}
```
public static final short Dashdot
```


The pen has alternating dashes and dots.

### Dashdotdot {#Dashdotdot}
```
public static final short Dashdotdot
```


The pen has dashes and double dots.

### Null {#Null}
```
public static final short Null
```


The pen is invisible.

### Insideframe {#Insideframe}
```
public static final short Insideframe
```


The pen is solid. When this pen is used in any drawing record that takes a bounding rectangle, the dimensions of the figure are shrunk so that it fits entirely in the bounding rectangle, taking into account the width of the pen.

### Userstyle {#Userstyle}
```
public static final short Userstyle
```


The pen uses a styling array supplied by the user.

### Alternate {#Alternate}
```
public static final short Alternate
```


The pen sets every other pixel (this style is applicable only for cosmetic pens).

### EndcapSquare {#EndcapSquare}
```
public static final short EndcapSquare
```


Line end caps are square.

### EndcapFlat {#EndcapFlat}
```
public static final short EndcapFlat
```


Line end caps are flat.

### JoinBevel {#JoinBevel}
```
public static final short JoinBevel
```


Line joins are beveled.

### JoinMiter {#JoinMiter}
```
public static final short JoinMiter
```


Line joins are mitered when they are within the current limit set by the SETMITERLIMIT META\_ESCAPE record. A join is beveled when it would exceed the limit.

