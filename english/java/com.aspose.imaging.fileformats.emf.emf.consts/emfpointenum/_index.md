---
title: EmfPointEnum
second_title: Aspose.Imaging for Java API Reference
description: The Point enumeration is used to specify how a point is to be used in a drawing call.
type: docs
weight: 35
url: /java/com.aspose.imaging.fileformats.emf.emf.consts/emfpointenum/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPointEnum extends System.Enum
```

The Point enumeration is used to specify how a point is to be used in a drawing call.
## Fields

| Field | Description |
| --- | --- |
| [PT_CLOSEFIGURE](#PT-CLOSEFIGURE) | A PT\_LINETO or PT\_BEZIERTO type can be combined with this value by using the bitwise operator OR to indicate that the corresponding point is the last point in a figure and the figure is closed |
| [PT_LINETO](#PT-LINETO) | Specifies that a line is to be drawn from the current position to this point, which then becomes the new current position |
| [PT_BEZIERTO](#PT-BEZIERTO) | Specifies that this point is a control point or ending point for a Bezier curve. |
| [PT_MOVETO](#PT-MOVETO) | Specifies that this point starts a disjoint figure. |
### PT_CLOSEFIGURE {#PT-CLOSEFIGURE}
```
public static final byte PT_CLOSEFIGURE
```


A PT\_LINETO or PT\_BEZIERTO type can be combined with this value by using the bitwise operator OR to indicate that the corresponding point is the last point in a figure and the figure is closed

### PT_LINETO {#PT-LINETO}
```
public static final byte PT_LINETO
```


Specifies that a line is to be drawn from the current position to this point, which then becomes the new current position

### PT_BEZIERTO {#PT-BEZIERTO}
```
public static final byte PT_BEZIERTO
```


Specifies that this point is a control point or ending point for a Bezier curve.

### PT_MOVETO {#PT-MOVETO}
```
public static final byte PT_MOVETO
```


Specifies that this point starts a disjoint figure. This point becomes the new current position.

