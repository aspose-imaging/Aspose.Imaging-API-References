---
title: "PathOperations"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Las operaciones para las formas de ruta que combinan operaciones booleanas."
type: docs
weight: 15
url: /es/java/com.aspose.imaging.fileformats.core.vectorpaths/pathoperations/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PathOperations extends System.Enum
```

Las operaciones para combinar formas de ruta (operaciones booleanas).
## Campos

| Campo | Descripción |
| --- | --- |
| [ExcludeOverlappingShapes](#ExcludeOverlappingShapes) | Excluir formas superpuestas (operación XOR). |
| [CombineShapes](#CombineShapes) | Combinar formas (operación OR). |
| [SubtractFrontShape](#SubtractFrontShape) | Restar forma frontal (operación NOT). |
| [IntersectShapeAreas](#IntersectShapeAreas) | Intersectar áreas de forma (operación AND). |
### ExcludeOverlappingShapes {#ExcludeOverlappingShapes}
```
public static final int ExcludeOverlappingShapes
```


Excluir formas superpuestas (operación XOR).

### CombineShapes {#CombineShapes}
```
public static final int CombineShapes
```


Combinar formas (operación OR). Este es el valor predeterminado en Photoshop.

### SubtractFrontShape {#SubtractFrontShape}
```
public static final int SubtractFrontShape
```


Restar forma frontal (operación NOT).

### IntersectShapeAreas {#IntersectShapeAreas}
```
public static final int IntersectShapeAreas
```


Intersectar áreas de forma (operación AND).

