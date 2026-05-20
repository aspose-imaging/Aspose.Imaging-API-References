---
title: "PathJumpTypes"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Arten von Übergängen zwischen Punkten des"
type: docs
weight: 18
url: /de/java/com.aspose.imaging.fileformats.cmx.objectmodel.enums/pathjumptypes/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PathJumpTypes extends System.Enum
```

Arten von Übergängen zwischen Punkten des [CmxPathSpec](../../com.aspose.imaging.fileformats.cmx.objectmodel.specs/cmxpathspec)
## Felder

| Feld | Beschreibung |
| --- | --- |
| [MoveTo](#MoveTo) | Der Punkt ist nicht mit dem vorherigen verbunden. |
| [LineTo](#LineTo) | Der Punkt ist über eine gerade Linie mit dem vorherigen verbunden. |
| [BezierTo](#BezierTo) | Der Punkt ist über eine bikubische Bézierkurve mit dem vorherigen sichtbaren Punkt verbunden. |
| [BezierSupport](#BezierSupport) | Verwendung eines unsichtbaren Hilfspunkts zum Erstellen einer bikubischen Bézierkurve. |
### MoveTo {#MoveTo}
```
public static final int MoveTo
```


Der Punkt ist nicht mit dem vorherigen verbunden. Verwendung für sichtbare Punkte.

### LineTo {#LineTo}
```
public static final int LineTo
```


Der Punkt ist über eine gerade Linie mit dem vorherigen verbunden. Verwendung für sichtbare Punkte.

### BezierTo {#BezierTo}
```
public static final int BezierTo
```


Der Punkt ist über eine bikubische Bézierkurve mit dem vorherigen sichtbaren Punkt verbunden. Verwendung für sichtbare Punkte.

### BezierSupport {#BezierSupport}
```
public static final int BezierSupport
```


Verwendung eines unsichtbaren Hilfspunkts zum Erstellen einer bikubischen Bézierkurve.

