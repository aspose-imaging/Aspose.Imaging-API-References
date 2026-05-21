---
title: "PathOperations"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Операции для форм пути, объединяющие булевы операции."
type: docs
weight: 15
url: /ru/java/com.aspose.imaging.fileformats.core.vectorpaths/pathoperations/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PathOperations extends System.Enum
```

Операции для комбинирования форм пути (логические операции).
## Поля

| Поле | Описание |
| --- | --- |
| [ExcludeOverlappingShapes](#ExcludeOverlappingShapes) | Исключить перекрывающиеся формы (операция XOR). |
| [CombineShapes](#CombineShapes) | Объединить формы (операция OR). |
| [SubtractFrontShape](#SubtractFrontShape) | Вычесть переднюю форму (операция NOT). |
| [IntersectShapeAreas](#IntersectShapeAreas) | Пересечь области форм (операция AND). |
### ExcludeOverlappingShapes {#ExcludeOverlappingShapes}
```
public static final int ExcludeOverlappingShapes
```


Исключить перекрывающиеся формы (операция XOR).

### CombineShapes {#CombineShapes}
```
public static final int CombineShapes
```


Объединить формы (операция OR). Это значение по умолчанию в Photoshop.

### SubtractFrontShape {#SubtractFrontShape}
```
public static final int SubtractFrontShape
```


Вычесть переднюю форму (операция NOT).

### IntersectShapeAreas {#IntersectShapeAreas}
```
public static final int IntersectShapeAreas
```


Пересечь области форм (операция AND).

