---
title: "PathOperations"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Les opérations pour les formes de chemin combinant des opérations booléennes."
type: docs
weight: 15
url: /fr/java/com.aspose.imaging.fileformats.core.vectorpaths/pathoperations/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PathOperations extends System.Enum
```

Les opérations de combinaison des formes de chemin (opérations booléennes).
## Champs

| Champ | Description |
| --- | --- |
| [ExcludeOverlappingShapes](#ExcludeOverlappingShapes) | Exclure les formes qui se chevauchent (opération XOR). |
| [CombineShapes](#CombineShapes) | Combiner les formes (opération OR). |
| [SubtractFrontShape](#SubtractFrontShape) | Soustraire la forme avant (opération NOT). |
| [IntersectShapeAreas](#IntersectShapeAreas) | Intersecter les zones de forme (opération AND). |
### ExcludeOverlappingShapes {#ExcludeOverlappingShapes}
```
public static final int ExcludeOverlappingShapes
```


Exclure les formes qui se chevauchent (opération XOR).

### CombineShapes {#CombineShapes}
```
public static final int CombineShapes
```


Combiner les formes (opération OR). C’est la valeur par défaut dans Photoshop.

### SubtractFrontShape {#SubtractFrontShape}
```
public static final int SubtractFrontShape
```


Soustraire la forme avant (opération NOT).

### IntersectShapeAreas {#IntersectShapeAreas}
```
public static final int IntersectShapeAreas
```


Intersecter les zones de forme (opération AND).

