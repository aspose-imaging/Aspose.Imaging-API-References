---
title: PathJumpTypes
second_title: Aspose.Imaging for Java API Reference
description: Types of transitions between points of the
type: docs
weight: 18
url: /com.aspose.imaging.fileformats.cmx.objectmodel.enums/pathjumptypes/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PathJumpTypes extends System.Enum
```

Types of transitions between points of the [CmxPathSpec](../../com.aspose.imaging.fileformats.cmx.objectmodel.specs/cmxpathspec)
## Fields

| Field | Description |
| --- | --- |
| [MoveTo](#MoveTo) | The point is not connected to the previous one. |
| [LineTo](#LineTo) | The point is connected to the previous one through a straight line. |
| [BezierTo](#BezierTo) | The point is connected to the previous visible point through a bi-cubic bezier curve. |
| [BezierSupport](#BezierSupport) | Uses for invisible auxiliary point to build a bi-cubic bezier curve. |
### MoveTo {#MoveTo}
```
public static final int MoveTo
```


The point is not connected to the previous one. Uses for visible points.

### LineTo {#LineTo}
```
public static final int LineTo
```


The point is connected to the previous one through a straight line. Uses for visible points.

### BezierTo {#BezierTo}
```
public static final int BezierTo
```


The point is connected to the previous visible point through a bi-cubic bezier curve. Uses for visible points.

### BezierSupport {#BezierSupport}
```
public static final int BezierSupport
```


Uses for invisible auxiliary point to build a bi-cubic bezier curve.

