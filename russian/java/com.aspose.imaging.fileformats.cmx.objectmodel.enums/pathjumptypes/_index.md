---
title: "PathJumpTypes"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Типы переходов между точками"
type: docs
weight: 18
url: /ru/java/com.aspose.imaging.fileformats.cmx.objectmodel.enums/pathjumptypes/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PathJumpTypes extends System.Enum
```

Типы переходов между точками [CmxPathSpec](../../com.aspose.imaging.fileformats.cmx.objectmodel.specs/cmxpathspec)
## Поля

| Поле | Описание |
| --- | --- |
| [MoveTo](#MoveTo) | Точка не соединена с предыдущей. |
| [LineTo](#LineTo) | Точка соединена с предыдущей прямой линией. |
| [BezierTo](#BezierTo) | Точка соединена с предыдущей видимой точкой посредством бикубической кривой Безье. |
| [BezierSupport](#BezierSupport) | Используется невидимая вспомогательная точка для построения бикубической кривой Безье. |
### MoveTo {#MoveTo}
```
public static final int MoveTo
```


Точка не соединена с предыдущей. Используется для видимых точек.

### LineTo {#LineTo}
```
public static final int LineTo
```


Точка соединена с предыдущей прямой линией. Используется для видимых точек.

### BezierTo {#BezierTo}
```
public static final int BezierTo
```


Точка соединена с предыдущей видимой точкой посредством бикубической кривой Безье. Используется для видимых точек.

### BezierSupport {#BezierSupport}
```
public static final int BezierSupport
```


Используется невидимая вспомогательная точка для построения бикубической кривой Безье.

