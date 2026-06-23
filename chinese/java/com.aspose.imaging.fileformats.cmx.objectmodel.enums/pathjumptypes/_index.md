---
title: "PathJumpTypes"
second_title: "Aspose.Imaging for Java API 参考"
description: "点之间的过渡类型"
type: docs
weight: 18
url: /zh/java/com.aspose.imaging.fileformats.cmx.objectmodel.enums/pathjumptypes/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PathJumpTypes extends System.Enum
```

点之间的过渡类型 [CmxPathSpec](../../com.aspose.imaging.fileformats.cmx.objectmodel.specs/cmxpathspec)
## 字段

| 字段 | 描述 |
| --- | --- |
| [MoveTo](#MoveTo) | 该点未与前一个点相连。 |
| [LineTo](#LineTo) | 该点通过直线与前一个点相连。 |
| [BezierTo](#BezierTo) | 该点通过双三次贝塞尔曲线与前一个可见点相连。 |
| [BezierSupport](#BezierSupport) | 用于不可见的辅助点来构建双三次贝塞尔曲线。 |
### MoveTo {#MoveTo}
```
public static final int MoveTo
```


该点未与前一个点相连。用于可见点。

### LineTo {#LineTo}
```
public static final int LineTo
```


该点通过直线与前一个点相连。用于可见点。

### BezierTo {#BezierTo}
```
public static final int BezierTo
```


该点通过双三次贝塞尔曲线与前一个可见点相连。用于可见点。

### BezierSupport {#BezierSupport}
```
public static final int BezierSupport
```


用于不可见的辅助点来构建双三次贝塞尔曲线。

