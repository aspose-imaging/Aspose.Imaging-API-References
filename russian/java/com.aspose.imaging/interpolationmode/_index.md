---
title: "InterpolationMode"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Перечисление com.aspose.imaging.InterpolationMode указывает алгоритм, используемый при масштабировании или вращении изображений."
type: docs
weight: 65
url: /ru/java/com.aspose.imaging/interpolationmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class InterpolationMode extends System.Enum
```

Перечисление `com.aspose.imaging.InterpolationMode` указывает алгоритм, используемый при масштабировании или вращении изображений.
## Поля

| Поле | Описание |
| --- | --- |
| [Invalid](#Invalid) | Недопустимый режим интерполяции. |
| [Default](#Default) | Указывает режим по умолчанию. |
| [Low](#Low) | Указывает интерполяцию низкого качества. |
| [High](#High) | Указывает интерполяцию высокого качества. |
| [Bilinear](#Bilinear) | Указывает билинейную интерполяцию. |
| [Bicubic](#Bicubic) | Указывает бикубическую интерполяцию. |
| [NearestNeighbor](#NearestNeighbor) | Указывает интерполяцию ближайшего соседа. |
| [HighQualityBilinear](#HighQualityBilinear) | Указывает высококачественную билинейную интерполяцию. |
| [HighQualityBicubic](#HighQualityBicubic) | Указывает высококачественную бикубическую интерполяцию. |
### Invalid {#Invalid}
```
public static final int Invalid
```


Недопустимый режим интерполяции.

### Default {#Default}
```
public static final int Default
```


Указывает режим по умолчанию.

### Low {#Low}
```
public static final int Low
```


Указывает интерполяцию низкого качества.

### High {#High}
```
public static final int High
```


Указывает интерполяцию высокого качества.

### Bilinear {#Bilinear}
```
public static final int Bilinear
```


Указывает билинейную интерполяцию. Предфильтрация не выполняется. Этот режим не подходит для уменьшения изображения менее чем на 50 % от его исходного размера.

### Bicubic {#Bicubic}
```
public static final int Bicubic
```


Указывает бикубическую интерполяцию. Предфильтрация не выполняется. Этот режим не подходит для уменьшения изображения менее чем на 25 % от его исходного размера.

### NearestNeighbor {#NearestNeighbor}
```
public static final int NearestNeighbor
```


Указывает интерполяцию ближайшего соседа.

### HighQualityBilinear {#HighQualityBilinear}
```
public static final int HighQualityBilinear
```


Указывает высококачественную билинейную интерполяцию. Выполняется предфильтрация для обеспечения высококачественного уменьшения.

### HighQualityBicubic {#HighQualityBicubic}
```
public static final int HighQualityBicubic
```


Указывает высококачественную бикубическую интерполяцию. Выполняется предфильтрация для обеспечения высококачественного уменьшения. Этот режим обеспечивает наивысшее качество преобразованных изображений.

