---
title: EmfPenStyle
second_title: Aspose.Imaging for Java API Reference
description: The PenStyle enumeration defines the attributes of pens that can be used in graphics operations.
type: docs
weight: 34
url: /com.aspose.imaging.fileformats.emf.emf.consts/emfpenstyle/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPenStyle extends System.Enum
```

The PenStyle enumeration defines the attributes of pens that can be used in graphics operations. A pen style is a combination of pen type, line style, line cap, and line join.
## Fields

| Field | Description |
| --- | --- |
| [PS_COSMETIC](#PS-COSMETIC) | A pen type that specifies a line with a width of one logical unit and a style that is a solid color |
| [PS_ENDCAP_ROUND](#PS-ENDCAP-ROUND) | A line cap that specifies round ends. |
| [PS_JOIN_ROUND](#PS-JOIN-ROUND) | A line join that specifies round joins |
| [PS_SOLID](#PS-SOLID) | A line style that is a solid color |
| [PS_DASH](#PS-DASH) | A line style that is dashed |
| [PS_DOT](#PS-DOT) | A line style that is dotted. |
| [PS_DASHDOT](#PS-DASHDOT) | A line style that consists of alternating dashes and dots |
| [PS_DASHDOTDOT](#PS-DASHDOTDOT) | A line style that consists of dashes and double dots. |
| [PS_NULL](#PS-NULL) | A line style that is invisible. |
| [PS_INSIDEFRAME](#PS-INSIDEFRAME) | A line style that is a solid color. |
| [PS_USERSTYLE](#PS-USERSTYLE) | A line style that is defined by a styling array, which specifies the lengths of dashes and gaps in the line |
| [PS_ALTERNATE](#PS-ALTERNATE) | A line style in which every other pixel is set. |
| [PS_ENDCAP_SQUARE](#PS-ENDCAP-SQUARE) | A line cap that specifies square ends. |
| [PS_ENDCAP_FLAT](#PS-ENDCAP-FLAT) | A line cap that specifies flat ends. |
| [PS_JOIN_BEVEL](#PS-JOIN-BEVEL) | A line join that specifies beveled joins. |
| [PS_JOIN_MITER](#PS-JOIN-MITER) | A line join that specifies mitered joins when the lengths of the joins are within the current miter length limit that is set in the playback device context. |
| [PS_GEOMETRIC](#PS-GEOMETRIC) | A pen type that specifies a line with a width that is measured in logical units and a style that can contain any of the attributes of a brush. |
| [StyleMask](#StyleMask) | The style mask |
| [EndCapMask](#EndCapMask) | The end cap mask |
| [JoinMask](#JoinMask) | The join mask |
| [TypeMask](#TypeMask) | The type mask |
### PS_COSMETIC {#PS-COSMETIC}
```
public static final int PS_COSMETIC
```


A pen type that specifies a line with a width of one logical unit and a style that is a solid color

### PS_ENDCAP_ROUND {#PS-ENDCAP-ROUND}
```
public static final int PS_ENDCAP_ROUND
```


A line cap that specifies round ends.

### PS_JOIN_ROUND {#PS-JOIN-ROUND}
```
public static final int PS_JOIN_ROUND
```


A line join that specifies round joins

### PS_SOLID {#PS-SOLID}
```
public static final int PS_SOLID
```


A line style that is a solid color

### PS_DASH {#PS-DASH}
```
public static final int PS_DASH
```


A line style that is dashed

### PS_DOT {#PS-DOT}
```
public static final int PS_DOT
```


A line style that is dotted.

### PS_DASHDOT {#PS-DASHDOT}
```
public static final int PS_DASHDOT
```


A line style that consists of alternating dashes and dots

### PS_DASHDOTDOT {#PS-DASHDOTDOT}
```
public static final int PS_DASHDOTDOT
```


A line style that consists of dashes and double dots.

### PS_NULL {#PS-NULL}
```
public static final int PS_NULL
```


A line style that is invisible.

### PS_INSIDEFRAME {#PS-INSIDEFRAME}
```
public static final int PS_INSIDEFRAME
```


A line style that is a solid color. When this style is specified in a drawing record that takes a bounding rectangle, the dimensions of the figure are shrunk so that it fits entirely in the bounding rectangle, taking into account the width of the pen.

### PS_USERSTYLE {#PS-USERSTYLE}
```
public static final int PS_USERSTYLE
```


A line style that is defined by a styling array, which specifies the lengths of dashes and gaps in the line

### PS_ALTERNATE {#PS-ALTERNATE}
```
public static final int PS_ALTERNATE
```


A line style in which every other pixel is set. This style is applicable only to a pen type of PS\_COSMETIC

### PS_ENDCAP_SQUARE {#PS-ENDCAP-SQUARE}
```
public static final int PS_ENDCAP_SQUARE
```


A line cap that specifies square ends.

### PS_ENDCAP_FLAT {#PS-ENDCAP-FLAT}
```
public static final int PS_ENDCAP_FLAT
```


A line cap that specifies flat ends.

### PS_JOIN_BEVEL {#PS-JOIN-BEVEL}
```
public static final int PS_JOIN_BEVEL
```


A line join that specifies beveled joins.

### PS_JOIN_MITER {#PS-JOIN-MITER}
```
public static final int PS_JOIN_MITER
```


A line join that specifies mitered joins when the lengths of the joins are within the current miter length limit that is set in the playback device context. If the lengths of the joins exceed the miter limit, beveled joins are specified

### PS_GEOMETRIC {#PS-GEOMETRIC}
```
public static final int PS_GEOMETRIC
```


A pen type that specifies a line with a width that is measured in logical units and a style that can contain any of the attributes of a brush.

### StyleMask {#StyleMask}
```
public static final int StyleMask
```


The style mask

### EndCapMask {#EndCapMask}
```
public static final int EndCapMask
```


The end cap mask

### JoinMask {#JoinMask}
```
public static final int JoinMask
```


The join mask

### TypeMask {#TypeMask}
```
public static final int TypeMask
```


The type mask

