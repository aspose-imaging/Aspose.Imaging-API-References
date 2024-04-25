---
title: LineJoin
second_title: Aspose.Imaging for Java API Reference
description: Specifies how to join consecutive line or curve segments in a figure subpath contained in a GraphicsPath object.
type: docs
weight: 70
url: /com.aspose.imaging/linejoin/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class LineJoin extends System.Enum
```

Specifies how to join consecutive line or curve segments in a figure (subpath) contained in a `GraphicsPath` object.
## Fields

| Field | Description |
| --- | --- |
| [Miter](#Miter) | Specifies a mitered join. |
| [Bevel](#Bevel) | Specifies a beveled join. |
| [Round](#Round) | Specifies a circular join. |
| [MiterClipped](#MiterClipped) | Specifies a mitered join. |
### Miter {#Miter}
```
public static final int Miter
```


Specifies a mitered join. This produces a sharp corner or a clipped corner, depending on whether the length of the miter exceeds the miter limit.

### Bevel {#Bevel}
```
public static final int Bevel
```


Specifies a beveled join. This produces a diagonal corner.

### Round {#Round}
```
public static final int Round
```


Specifies a circular join. This produces a smooth, circular arc between the lines.

### MiterClipped {#MiterClipped}
```
public static final int MiterClipped
```


Specifies a mitered join. This produces a sharp corner or a beveled corner, depending on whether the length of the miter exceeds the miter limit.

