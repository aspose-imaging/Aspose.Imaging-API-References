---
title: "PathJumpTypes"
second_title: "Aspose.Imaging for Java API 参考文档"
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
| [MoveTo](#MoveTo) | 该点未连接到前一个点。 |
| [LineTo](#LineTo) | 该点通过直线连接到前一个点。 |
| [BezierTo](#BezierTo) | 该点通过双三次贝塞尔曲线连接到前一个可见点。 |
| [BezierSupport](#BezierSupport) | 用于不可见辅助点以构建双三次贝塞尔曲线的用途。 |
### MoveTo {#MoveTo}
```
public static final int MoveTo
```


该点未连接到前一个点。用于可见点的用途。

### LineTo {#LineTo}
```
public static final int LineTo
```


该点通过直线连接到前一个点。用于可见点的用途。

### BezierTo {#BezierTo}
```
public static final int BezierTo
```


该点通过双三次贝塞尔曲线连接到前一个可见点。用于可见点的用途。

### BezierSupport {#BezierSupport}
```
public static final int BezierSupport
```


用于不可见辅助点以构建双三次贝塞尔曲线的用途。

