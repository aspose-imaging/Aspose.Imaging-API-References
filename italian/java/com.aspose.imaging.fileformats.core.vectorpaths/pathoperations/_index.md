---
title: "PathOperations"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Le operazioni per le forme del percorso che combinano operazioni booleane."
type: docs
weight: 15
url: /it/java/com.aspose.imaging.fileformats.core.vectorpaths/pathoperations/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PathOperations extends System.Enum
```

Le operazioni per la combinazione delle forme del percorso (operazioni booleane).
## Campi

| Campo | Descrizione |
| --- | --- |
| [ExcludeOverlappingShapes](#ExcludeOverlappingShapes) | Escludi forme sovrapposte (operazione XOR). |
| [CombineShapes](#CombineShapes) | Combina forme (operazione OR). |
| [SubtractFrontShape](#SubtractFrontShape) | Sottrai forma anteriore (operazione NOT). |
| [IntersectShapeAreas](#IntersectShapeAreas) | Interseca aree delle forme (operazione AND). |
### ExcludeOverlappingShapes {#ExcludeOverlappingShapes}
```
public static final int ExcludeOverlappingShapes
```


Escludi forme sovrapposte (operazione XOR).

### CombineShapes {#CombineShapes}
```
public static final int CombineShapes
```


Combina forme (operazione OR). Questo è il valore predefinito in Photoshop.

### SubtractFrontShape {#SubtractFrontShape}
```
public static final int SubtractFrontShape
```


Sottrai forma anteriore (operazione NOT).

### IntersectShapeAreas {#IntersectShapeAreas}
```
public static final int IntersectShapeAreas
```


Interseca aree delle forme (operazione AND).

